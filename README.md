# Настройка микрофона Fifine K658

<br>

НАСТРОЙКА:

Для начала необходимо установить <a href="https://sourceforge.net/projects/equalizerapo/files/1.3/EqualizerAPO64-1.3.exe/download">Equalizer APO</a> и выбрать микрофон на вкладке Capture devices в Configurator. Компьютер перезагрузится.

* Уровень громкости микрофона в системе: 100<br>
* Ручка регулятора громкости на корпусе: 50% (по центру)<br>

Порядок настройки:

1. Скачать и открыть config.txt в текстовом редакторе<br>
2. Поменять пути до плагинов с "D:\Soft\VST\" на свои<br>
3. Закинуть config.txt в "C:\Program Files\EqualizerAPO\config" либо скопировать нужные строки и вставить<br>
4. Выбрать микрофон в качестве устройства ввода в Configuration Editor<br>

Если пути горят красным (File not found), путь неверный, выбирать плагин в Equalizer APO не нужно, настройки собъются. Лучше в редакторе подправить путь на правильный, пока при запуске Equalizer APO не пропадёт красная надпись.<br>

* LoudMax можно скачать здесь: https://loudmax.blogspot.com/<br>

<b>config.txt</b> содержит настройки, которые исправляют очевидные проблемы АЧХ микрофона, добавляет мягкую компрессию и лимитер. Здесь также есть отключенный рэк с brickwall нижних частот до 95Гц (см. FabFilter Pro-Q 2). Если включить, получается довольно интересный популярный эффект like LIVE, который используется на телевидении. Найти фаб плагины, которые используются в пресете можно ВКонтакте в файлах по запросу "FabFilter2.7z", размер файла для сверки 13.2 МБ.
