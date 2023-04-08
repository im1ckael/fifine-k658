# Настройка микрофона Fifine K658

<br>

НАСТРОЙКА:

Для начала необходимо установить <a href="https://sourceforge.net/projects/equalizerapo/files/1.3/EqualizerAPO64-1.3.exe/download">Equalizer APO</a> и выбрать микрофон на вкладке Capture devices в Configurator. Компьютер перезагрузится.

* Уровень громкости микрофона в системе: 100<br>
* Ручка регулятора громкости на корпусе: 50% (по центру)<br>

Порядок настройки:

2. Разместить нужные 64-битные DLL плагины в папке "C:\Program Files\VSTPlugins\". Если папки нет, создать. Без подпапок, то есть никаких папок в этой директории быть не должно, только файлы.<br>
3. Закинуть config.txt в "C:\Program Files\EqualizerAPO\config" либо скопировать нужные строки и вставить<br>
4. Выбрать микрофон в качестве устройства ввода в Configuration Editor<br>

Если пути горят красным (File not found), значит нужных плагинов нет по адресу "C:\Program Files\VSTPlugins\", выбирать плагин в Equalizer APO не нужно, настройки собъются. Лучше положить нужные плагины в эту папку и перезапускать программу пока при запуске Equalizer APO не пропадёт красная надпись.<br>

ПЛАГИНЫ:

* LoudMax можно скачать здесь: https://loudmax.blogspot.com/<br>

<b>config.txt</b> содержит настройки, которые исправляют очевидные проблемы АЧХ микрофона, добавляет компрессию и лимитер. Здесь также есть отключенный рэк с brickwall нижних частот до 95Гц (см. FabFilter Pro-Q 2). Если включить, получается довольно интересный популярный эффект like LIVE, который используется на телевидении. Найти фаб плагины, которые используются в пресете можно ВКонтакте в файлах по запросу "FabFilter2", размер файла для сверки 13.2 МБ, расширение ".7z".

<b>config-shure.txt</b> содержит более глубокие настройки, микрофон звучит как Shure SM7B. Настраивался по референсу - мексиканский оригинальный Shure SM7B 2022.
