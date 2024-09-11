---
layout: default
title: Автозапуск пользовательских программ
parent: Go1
grand_parent: Unitree Robotics
nav_order: 4
---

# Автозапуск пользовательских программ

Когда вы познакомитесь с SDK и напишите свою управляющую программу, встанет вопрос ее автоматического запуска при включении робота. В Linux существуют разные способы для автозапуска. Широкоизвестный способ через файл `/etc/rc.local` является устаревшим. 

Ниже описан актуальный способ обеспечения автозапуска. Этот способ используется и самим производителем робота [Unitree] для старта своих исполняемых файлов и скриптов (программы управления движением, спорт-режима, веб-интерфейса, настройки сети и т.п.)

Представим, что вы скомпилировали пример из SDK и имеете следующий исполняемый файл:

`/home/pi/Unitree/sdk/unitree_legged_sdk/build/example_walk`

Для обеспечения дополнительного функционала, будем запускать этот файл на исполнение из скрипта. Таким образом, мы сможем, к примеру, сделать небольшую отстрочку запуска (для ожидания запуска всех систем робота) или запускать несколько исполняемых файлов. 

Создаем скрипт `myscript.sh` в домашнем каталоге (пользователь pi) на Raspberry Pi CM4 со следующим содержимым:

```bash
cd /home/pi/Unitree/sdk/unitree_legged_sdk/build
Sleep 500  # отсрочка запуска
sudo ./example_walk
```


После этого для файла скрипта устанавливаем возможность исполнения:

```bash
sudo chmod +x myscript.sh
```

Далее настраиваем автозапуск этого скрипта методом - _"через каталог .config"_. Для этого по пути `/home/pi/.config/autostart/` создаем файл `myscript.desktop` со следующим содержимым:

```
[Desktop Entry]
Name=myscript
Comment=for start my programms
Exec=bash /home/pi/myscript.sh
Terminal=false
Type=Application
Categories=System;Utility;Archiving;
StartupNotify=false
NoDisplay=true
```

{: .note }
> В каталоге уже лежит файл **unitree.desktop**, используемый для запуска стартового скрипта программ производителя. Можно скопировать его и использовать для запуска своего скрипта, немного подправив.

После этого при включении робот будет исполнять этот скрипт и исполнять прописанные в нем инструкции, в том числе команду запуска исполняемого файла.

