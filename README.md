# Настройка микрофона Fifine K658

<br>

НАСТРОЙКА:

Для начала необходимо установить <a href="https://sourceforge.net/projects/equalizerapo/files/1.3/EqualizerAPO64-1.3.exe/download">Equalizer APO</a> и выбрать микрофон на вкладке Capture devices в Configurator. Компьютер перезагрузится.

* Уровень громкости микрофона в системе: 100<br>
* Ручка регулятора громкости на корпусе: 50% (по центру)<br>

Порядок настройки:

1. Разместить нужные 64-битные DLL плагины в папке "C:\Program Files\VSTPlugins\". Если папки нет, создать.<br>
2. Закинуть config.txt в папку "C:\Program Files\EqualizerAPO\config\"<br>
3. Выбрать микрофон в качестве устройства ввода в Configuration Editor (самый первый фильтр)<br>

Если пути горят красным (File not found), значит нужных плагинов нет по адресу "C:\Program Files\VSTPlugins\", выбирать плагины вручную в Equalizer APO не нужно, настройки собъются. Лучше положить нужные плагины в эту папку и перезапускать программу пока при запуске Equalizer APO не пропадёт красная надпись. Сравните имя файла в папке VSTPlugins и имя файла, которое написано в config.txt, они должны совпадать.<br>

ПЛАГИНЫ:

* LoudMax можно скачать здесь: https://loudmax.blogspot.com/<br>

<b>config.txt</b> содержит настройки, которые исправляют очевидные проблемы АЧХ микрофона, добавляет компрессию и лимитер. Здесь также есть отключенный рэк с brickwall нижних частот до 95Гц (см. FabFilter Pro-Q 2). Если включить, получается довольно интересный популярный эффект like LIVE, который используется на телевидении. Найти фаб плагины, которые используются в пресете можно ВКонтакте в файлах по запросу "FabFilter2", размер файла для сверки 4.8 МБ, расширение ".7z". Для распаковки можно использовать архиватор 7-Zip.

<b>config-shure.txt</b> содержит более глубокие настройки, микрофон звучит как Shure SM7B. Настраивался по референсу - мексиканский оригинальный Shure SM7B 2022.
