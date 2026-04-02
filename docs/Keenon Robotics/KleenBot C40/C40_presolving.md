
# Нужно придумать как назвать

Для работы и связи робота с облаком рекомендуется использовать последнюю актуальную версию робота. Ввиду ограничений мы предлагаем нашим клиентам специализированное приложение, которое будет иметь беспроблемный доступ к облаку из России. Внимательно следуйте инструкции, чтобы обновить ПО, а так же навигационные алгоритмы.

Это решение так же устраняет проблему, когда робот отображается как Не в сети, будучи подключенным к WiFi или при передаче данных по SIM.

Все действия будут описаны на английском интерфейсе, который установлен по умолчанию.

## Обновление

Подготовьте флешку отформатированную в формате FAT, exFAT или FAT32.

Скачайте специализированную версию приложения: [ссылка на приложение](https://drive.google.com/file/d/1CvhPAc7e7yb_ISulvE2eYs1DlepPcG6H/view?usp=sharing) 

### Обнаружение USB-накопителя

Начинать весь процесс будем с главного меню приложения уборки

![Главное меню приложения уборки](/assets/images/){:.image style="display: block; margin: 20px auto"}

1. Нажмите несколько раз на логотип Keenon в левом верхнем углу экрана

![Жми лого](/assets/images/){:.image style="display: block; margin: 20px auto"}
2. Введите пароль от настроек администратора **870051**

![Пароль к меню администратора](/assets/images/){:.image style="display: block; margin: 20px auto"}
3. Оказавшить в меню администратора, сперва перейдите в раздел **With regard to**, чтобы увидеть текущую версию пакета обновлений. Код в конце версии пакета обновлений отображает релиз, начиная с V203 поддержка станции, последняя стабильная V210. Необходимо обновить до V210.

![Версия текущего пакета обновлений](/assets/images/){:.image style="display: block; margin: 20px auto"}
4. Перейдите к разделу System setting

![Системные настройки](/assets/images/){:.image style="display: block; margin: 20px auto"}
5. Отключите три верхних ползунка, чтобы была возможность выйти в операционную систему

![Три ползунка выкл](/assets/images/){:.image style="display: block; margin: 20px auto"}
6. Снизу должен появиться трей, нажимая на кружок, вы свернете приложения.

![Нажми чтобы свернуть](/assets/images/){:.image style="display: block; margin: 20px auto"}
7. Свайпните вниз, чтобы открыть трей функций операционной системы

![Свайптрей](/assets/images/){:.image style="display: block; margin: 20px auto"}
8. Нажмите шестеренку для перехода к настройкам

![Нажмите шестеренку](/assets/images/){:.image style="display: block; margin: 20px auto"}
9. Перейдите в самый последний раздел настроек **About tablet**

![Раздел обо мне](/assets/images/){:.image style="display: block; margin: 20px auto"}
10. Нажимайте на **Build version**, пока сообщение не станет **No need more you a already developer**

![Я разработчик](/assets/images/){:.image style="display: block; margin: 20px auto"}
11. Вернитесь в меню разделов и перейдите в ((((Вспомнить))

![выы](/assets/images/){:.image style="display: block; margin: 20px auto"}
12. Раскройте настройку **advanced** и зайдите в **Developer options**

![Настройка Dev](/assets/images/){:.image style="display: block; margin: 20px auto"}
13. Найдите пункт USB debugging и включите его

![Отладка USB](/assets/images/){:.image style="display: block; margin: 20px auto"}
14. Найдите в этом же меню USB preferences by default и установите в положение File Transfer

![По умолчанию](/assets/images/){:.image style="display: block; margin: 20px auto"}
15. Вставьте флешку в слот с обратной стороны экрана робота

![Куда вставлять флешку](/assets/images/){:.image style="display: block; margin: 20px auto"}
16. Вернитесь на главный экран операционной системы и свайпните снизу вверх, чтобы открыть меню приложений

![Меню приложений](/assets/images/){:.image style="display: block; margin: 20px auto"}
17. Запустите приложение Explorer, в домашнем меню выбора носителя должно отображаться как на изображении ниже: Internal memory и USB

![Домашняя страница](/assets/images/){:.image style="display: block; margin: 20px auto"}
Если носитель не отображается, проверьте настройки из пунктов 13 и 14.

### Подготовка к обновлению

![Приложение на флешке](/assets/images/){:.image style="display: block; margin: 20px auto"}
1. Откройте настройки Android и перейдите в раздел **Apps and blablabla**

![Apps and blablabla](/assets/images/){:.image style="display: block; margin: 20px auto"}
2. Нажмите **See all**

![Внутри apps](/assets/images/){:.image style="display: block; margin: 20px auto"}
3. Найдите приложение **Robot Clean app**, остановите его нажав **[Force stop]** и удалите нажав **[Uninstall]**

![Останови и удали](/assets/images/){:.image style="display: block; margin: 20px auto"}
4. Перейдите в приложение Explorer из меню приложений Android (свайп снизу вверх на главном экране)

![Explorer в меню](/assets/images/){:.image style="display: block; margin: 20px auto"}
5. Перейдите по следующему пути **Internal memory/keenon**

![Папка кинон](/assets/images/){:.image style="display: block; margin: 20px auto"}
6. Тут нужно найти папку **db/**, удерживать на ней палец пока не откроется контекстное меню и выберите функцию **Delete**

![Внутрипапкиобвестиdb](/assets/images/){:.image style="display: block; margin: 20px auto"}
![Удаление](/assets/images/){:.image style="display: block; margin: 20px auto"}

### Установка приложения и обновление всего ПО

1. Проверьте формат USB-накопителя в свойствах

![Формат флешки](/assets/images/){:.image style="display: block; margin: 20px auto"}
2. Переместите скачанный файл специализированного приложения на флешку. **Eсли в конце расширения у вас добавилось .apk.1 удалите .1**

![Приложение на флешке](/assets/images/){:.image style="display: block; margin: 20px auto"}
3. Вставьте флешку в слот с обратной стороны экрана робота

![Куда вставлять флешку](/assets/images/){:.image style="display: block; margin: 20px auto"}
4.  Запустите приложение Explorer из меню приложений и перейдите в USB

![Чтонафлешке?](/assets/images/){:.image style="display: block; margin: 20px auto"}
5. Найдите файл приложения и дважды нажмите на него, чтобы установить

![Установка](/assets/images/){:.image style="display: block; margin: 20px auto"}
6. После установки приложение должно само запуститься, запустите его из меню приложений, если этого не произошло

![Новое приложение в меню приложений](/assets/images/){:.image style="display: block; margin: 20px auto"}
7. Оказавшить в главном меню приложений нажмите несколько раз на логотип Keenon в левом верхнем углу экрана и введите пароль 870051

![Новое приложение в меню приложений](/assets/images/){:.image style="display: block; margin: 20px auto"}
8. В пункте настроек *General** скачайте русский языковой пакет в пункте Language

![General меню](/assets/images/){:.image style="display: block; margin: 20px auto"}
![Language вкладка](/assets/images/){:.image style="display: block; margin: 20px auto"}
9. Перейдите во вкладку **Обо мне**

![Во вкладке обо мне](/assets/images/){:.image style="display: block; margin: 20px auto"}
10. Зайдите в облачный аккаунт на платформе

![В облачном аккаунте](/assets/images/){:.image style="display: block; margin: 20px auto"}
11. Перейдите во вкладку **OTA Management**
![Меню вкладок](/assets/images/){:.image style="display: block; margin: 20px auto"}
12. Установите следующие критерии поиска: **Whole package name** значение *clean*, а так же введите в поле **System software version** значение *V210*, и нажмите **[Search]** справа
![Параметры поиска обновления](/assets/images/){:.image style="display: block; margin: 20px auto"}
13. Сверьте **Whole package version** с вашей версией робота по наклейке с обратной стороны экрана
![Стикер сзади робота с версией робота](/assets/images/){:.image style="display: block; margin: 20px auto"}
14. Во пунтке **Operate** выберите **Push** у соотвествующего обновления
![Пушобновления](/assets/images/){:.image style="display: block; margin: 20px auto"}
15. Выберите во вкладке **Store Name** вашу точку и нажмите **[Search]**
![Push настройка](/assets/images/){:.image style="display: block; margin: 20px auto"}
16. Выберите робота, которого хотите обновить и нажмите Confirm
![Выбор и подтверждение](/assets/images/){:.image style="display: block; margin: 20px auto"}
17. Через небольшой промежуток времени во вкладке **Обо мне** администраторских настроек робота напротив версии пакета появится красный "пузырик", это означает, что обновление поступило и готово к загрузке
![ПришлаобноваУРА](/assets/images/){:.image style="display: block; margin: 20px auto"}
18. Нажмите на пункт с версией пакета и кнопку **[Update]**, чтобы начать обновление.
![Внутриверсиикнопкаобновить](/assets/images/){:.image style="display: block; margin: 20px auto"}
Процесс занимает продолжительное время, если он прервался - обновление не удалось скачать, и вам необходимо повторить действия с 11 шага.

После обновления в этой вкладке версия должна измениться и глобальная версия всего пакета обновления должна быть как та, которую вы указали при отправке.
![Смотри на версию](/assets/images/){:.image style="display: block; margin: 20px auto"}

{: .note}
Если несколько попыток загрузки обновления оказались неудачными, сообщите на портал поддержки, мы предоставим способ для оффлайн обновления робота.






