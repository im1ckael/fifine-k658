# Настройка микрофона Fifine K658

<br>

НАСТРОЙКА:

Для начала необходимо установить <a href="https://sourceforge.net/projects/equalizerapo/files/1.3/EqualizerAPO64-1.3.exe/download">Equalizer APO</a>.

* Уровень громкости микрофона в системе: 100<br>
* Ручка регулятора громкости на корпусе: 50% (по центру)<br>

Порядок настройки:

1. Скачать и открыть config.txt в текстовом редакторе<br>
2. Поменять пути до плагинов с "D:\Soft\VST\" на свои<br>
3. Закинуть config.txt в "C:\Program Files\EqualizerAPO\config" либо скопировать текст и вставить частично<br>

Если пути горят красным (File not found), путь неверный, выбирать плагин в Equalizer APO не нужно, настройки собъются. Лучше в редакторе подправить путь на правильный, пока при запуске Equalizer APO не пропадёт красная надпись.<br>

ReaPlugs скачиваем здесь: https://www.reaper.fm/reaplugs/<br>
LoudMax можно скачать здесь: https://loudmax.blogspot.com/<br>

config-def.txt содержит дефолтные настройки АЧХ микрофона. Используется только лимитер.

config.txt содержит также отключенный рэк с brickwall нижних частот до 90Гц (FabFilter Pro-Q 2). Получается довольно интересный популярный эффект like LIVE. Найти фаб плагины, которые используются в пресете можно ВКонтакте в файлах по запросу "FabFilter2.7z", размер файла для сверки 13.2 МБ.

config-dark.txt содержит более глубокие настройки с утопленной АЧХ и компрессией, которые позволят записывать звук без раздражающих сибилянтов. Найти De-Esser, который используется в пресете можно ВКонтакте в файлах по запросу "accusonus4.7z", размер файла для сверки 50.8 МБ.

Необходимо включить отображение расширений файлов в системе для установки VST плагинов.
