---
layout: default
title: Быстрый старт
parent: xArm6
grand_parent: UFactory
nav_order: 1
---
# Быстрый старт

В данном разделе будут описанные основыне действия, необходимые для начала работы с xArm6
 
## Подключение

1. Закрепите основание робота на прочной поверхости

![Крепление](/assets/images/x6_basehold.png){: width="500px" height="250px" style="display: block"}

2. Подключите робота через нижний разъем к ответной части на Блок управление;

{: .note}
Подключение робота к AC/DC Блоку управления не отличается, а лишь зависит от удобности использования источника постоянного или переменного тока

2. Соедините ПК и Блок управления используя Ethernet-корд;

![Сетевое подключение](/assets/images/x6_networkbox.jpg){: width="450px" height="250px" style="display: block"}

В итоге должно получиться в соотвествии с изображением ниже

![Готовое подключение](/assets/images/x6_controlbox.jpg){: width="450px" height="250px" style="display: block"}

Подключив Блок управления к сети на нем должен зажечься **Зеленый светодиод**, индицирующий поданное питание на манипулятор;

3. Установите ПК и блок управления в общую сеть (Адрес Блока управления указан на передней панели)

**Инструкция для OC Windows**

Перейдите в сетевые адаптеры и перейдите в параметры проводного сетевого устройства
![Общая сеть1](/assets/images/x6_ipwin1.png){: width="450px" height="250px" style="display: block"}

Во вкладке подробно выбрать Ipv4 метод
![Общая сеть2](/assets/images/x6_ipwin2.png){: width="450px" height="250px" style="display: block"}

Переключить radiobox на установку IP и задать адрес в подсети Блока управления
![Общая сеть3](/assets/images/x6_ipwin3.png){: width="450px" height="250px" style="display: block"}


**Инструкция для Linux**
4. Подключение к роботу доступно через приложение для Windows и MAC-xArmStudio и требует ввода IP-адреса Блока управления

![WindowsApp](/assets/images/x6_winapp.png){: width="450px" height="250px" style="display: block"}

Либо используя WEB-интерфейc. Для доступа в поле адреса в Браузере введи *ip:18333*

![WEBconn](/assets/images/x6_directconnect.jpg){: width="450px" height="250px" style="display: block"}

## Python SDK

[В РАЗРАБОТКЕ]