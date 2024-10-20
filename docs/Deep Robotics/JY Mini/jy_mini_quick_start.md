---
layout: default
title: Быстрый старт
parent: JY Mini
grand_parent: Deep Robotics
nav_order: 2
---

Этот мануал черновой и еще не одобрен администратором
{: .label .label-red }

# Быстрый старт

> Данное руководство дает базовую информацию по эксплуатация робособаки модели JY mini.


## Начало работы

{: .note }
> Обязательным пунктом на этапе эксплуатации служит предварительный внешний осмотр робота перед каждым включением на наличие дефектов: повреждение проводки, отсутствие защищающих элементов корпуса, раскрученных винтов и прочих моментов, отличающихся от первоначального вида робота (в случае обнаружения дефектов дальнейшая эксплуатация робота возможна, однако мы не сможем гарантировать дальнейшее обслуживание в рамках гарантийного договора). 
> 
> В этом случае требуется обратиться к инженерам в службу поддержки в чате, они смогут оперативно ответить на любые интересующие вопросы.


### Включение робота 
Положите робота в **стартовую позицию**: корпус лежит на земле горизонтально, без наклона, подставки на животе робота плотно прилегают к земле. Ноги робота собраны (четыре локтевых/коленных сустава и резиновые ступни должны касаться земли).


Для **включения робота** необходимо провести следующие действия:
 1. Нажмите кнопку включения(Робот будет включен только при условии отжатой кнопки аварийного
останова, ее нужно повернуть по часовой стрелке, тогда кнопка вернется в обычное положение и позволит подать питание на робота.)
 2. Ожидайте около 25 секунд до полного включения робота (перед
каждым новым запуском робота)
 3.  Подключитесь к Wi-Fi робота с пульта дистанционного управления(см. далее настройка пульта управления)
 4. Откройте приложение от Deep Robotics на рабочем столе пульта
управления.

Робот готов к работе
![Задняя панель](/assets/images/miniBack.jpg){: width="600px" style="display: block; margin: 0 auto"}

### Включение пульта управления
Для **включения пульта** необходимо провести следующие действия:

1. Зажамите кнопку включения на верхней части устройства
![Пульт управления](/assets/images/rcjy.png){: width="600px" style="display: block; margin: 0 auto"}
2. Откройте настройки WI-FI
3. Подключитесь к сети с названием модели имеющегося робота (YSC-JUM-******)

   Пароль: quadruped
4. Перейдите обратно на рабочий стол, на нем вы найдете приложение Deep Robotics. Запустите его.

Устройство готово к работе
## Управление роботом
После того, как пульт управления и робот синхронизированы, можно
приступать управлению роботом, используя различные комбинации.
Чтобы поднять робота нажмите кнопку 1, затем кнопку 2, чтобы разблокировать суставы.
Теперь вы можете вращать корпусом робота, чтобы начать движение нажмите кнопку Y.
Остальное описание клавиш и комбинаций приведено в списке ниже:

![Пульт управления](/assets/images/rcjy1.png){: width="600px" style="display: block; margin: 0 auto"}

Кнопка 1: встать / присесть / снять блокировку (когда все суставы
заблокированы)

Кнопка 2: переключение режима управления / режим «ползти»

Кнопка Y. начать движение / остановить движение

Кнопка B: Зарезервировано

Кнопка X: начать / остановить танец (если робот стоит на месте)

Кнопка A: зарезервировано

Кнопка 3: перемещение вперед / назад / влево / вправо

Кнопка 4: поворот налево / поворот направо

Кнопка 5: переход в режим навигации

Кнопка 6: переход в автономный режим движения.

Кнопка 7: переключиться на походку FLY-TROT / переключиться на походку TROT

Кнопка 8: прыжок

кнопка 9-Джойстик управления(стрелка влево + кнопка B - переход на режим ходьбы по лестнице)

Кнопка 10: переключиться на режим ходьбы по лестнице / переключиться на походку TROT

Кнопка 11 - запись логов(нажать 12 раз)


## Экстренные ситуации

**Аварийная остановка**

Когда робот теряет контроль над своими конечностями, сильно трясется или возникают другие ненормальные явления во время использования, нажмите ① и ④ одновременно или одиночное нажатие ⑬, чтобы вызвать аварийную остановку, которая переводит робота в состояние самоблокирующейся защиты и автоматически опускается. Затем нажмите ⑤ чтобы снять самоблокирующуюся защиту и выявить проблему. После устранения неполадок нажмите ④ и ⑥ по очереди, чтобы возобновить работу робота.

В случае аварийной остановки, если робот встает не сразу, необходимо подождать около 30 секунд, прежде чем робот отреагирует на команду.

**Перегрев**

Робот поставляется с датчиком температуры. Если робот работает в течение длительного времени,двигатель или привод можгут перегреться, в этом случае робот автоматически включает защиту от перегрева, после чего прекращает движение и опускается на землю.

**Падение**

Если робот внезапно упадет, суставы будут автоматически заблокированы.Нажмите кнопку Y в приложении, убедившись, что вокруг нет препятствий. Если робот по-прежнему не может подняться, нажмите кнопку аварийной остановки в задней части робота, затем нажмите [Сохранить данные] на странице настроек приложения и выключите робота.

**Низкий заряд батареи**

Когда заряд батареи робота ниже 10%, сработает защита от пониженного энергопотребления и робот не будет реагировать на команды дистанционного управления с джойстика.

**Экстренная аварийная остановка**

Экстренная аварийная остановка осущетвляется нажатием кнопки аварийной остановки на задней панели робота. После срабатывания экстренной аварийной остановки робот полностью отключается и падает на землю. Существует риск повреждения поверхности или робота, поэтому категорически запрещается нажимать кнопку экстренной аварийной остановки во время обычного движения!

**Другие обстоятельства**

• Если суставы не заблокированы или продолжают качаться после внезапного падения робота, подождите 30 секунд после того, как суставы робота полностью перестанут двигаться, прежде чем нажимать кнопку экстренной аварийной остановки на задней части корпуса.
• В случае пожара не используйте воду для его тушения. Пожалуйста, используйте один из следующих типов огнетушителей: пенный огнетушитель, сухой порошковый огнетушитель или углекислотный огнетушитель.
• В случае отказа кнопки аварийной остановки, появления дыма или воды в роботе или других непредвиденных ситуаций немедленно отключите питание робота. Затем сообщите о ситуации в сервисный центр, и мы поможем устранить проблему и отремонтировать или заменить вашего робота. Пожалуйста, обратите внимание на безопасность!

**Выключение питания**

Перед выполнением следующих операций убедитесь, что робот лежит на ровной поверхности. Нажмите кнопку питания, чтобы выключить робота. После выключения накройте робота антистатической тканью, чтобы избежать попадания пыли на лидар и другие устройства.

{: .highlight }
Обратите внимание на пломбировочную этикетку на роботе. Категорически запрещается разбирать робота лично. После разборки гарантия аннулируется!

**Зарядка**
1. Сначала подключите зарядное устройство к зарядному порту (зарядное устройство имеет разъем для защиты), затем подключите его к сети переменного тока 220 В.
2. Во время зарядки индикатор питания и индикатор зарядки на зарядном устройстве горят красным цветом.
3. Когда зарядка завершена, на дисплее батареи отображается 100%, а индикатор зарядки становится зеленым.

Всегда обращайте внимание на состояние зарядного устройства во время зарядки, чтобы избежать несчастных случаев.

---

**Часто задаваемые вопросы**

Q1: Что делать, если приложение не может подключиться к роботу?

A: Сначала проверьте, включено ли питание на роботе и нет ли другой версии приложения (обновления) в фоновом режиме. Если приложение по-прежнему не может подключиться к роботу, перезапустите робота и приложение и повторите попытку.

---

Q2: Нормально ли, что робот перестает двигаться самостоятельно?

A: Двигатель или привод могут быть защищены от перегрева. Пожалуйста, подождите 10 минут и повторите попытку. Если вы по-прежнему не можете управлять движением робота, проверьте, полностью ли заряжена батарея, отключена ли кнопка жесткой аварийной остановки (в выключенном состоянии она светится синим цветом) и подключен ли джойстик к Wi-Fi робота.

---

Q3: Что делать, если нет ответа на команды из приложения после подключения?

A: Сначала проверьте, отключена ли аварийная остановка (кнопка горит синим, когда она выключена). Затем убедитесь, что джойстик подключен к правильному роботу. Если приложение по-прежнему не может управлять роботом, подождите 10 секунд и повторите попытку.

---

Q4: Что делать, если столкнулись с проблемой, которую невозможно решить даже после ознакомления с данным руководством?

A: Нажмите **Сохранить данные** на странице настроек приложения и своевременно свяжитесь с отделом послепродажного обслуживания.


