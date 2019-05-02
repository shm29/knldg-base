###Создание Ui в Photoshop и перевод в QML (для Qt Creator)###

Для правильного создания **ui** в Photoshop для QML, нам понадобиться правильное распределение слоев. Где каждый слой/папка это отдельный фрагмент в _'.qml_'.

![Layers](https://i.imgur.com/CGkBebD.png)

С помощью скрипта _"[photoshop-qmlexporter](https://github.com/qt-labs/photoshop-qmlexporter)"_ для фотошоп, экспортируем psd в qml.

Скрипт (**.jsx** файл) устаналиваем в папку **_\Adobe\Adobe Photoshop CC 2018\Presets\Scripts_**.
Открываем наш готовый psd файл, заходим в **_Файл->Сценарии->Export QML_** (Files->Scripts->Export QML).
Готово. На выходе получаем обычный .qml файл который можно открыть в Qt Creator

![Qt Creator](https://i.imgur.com/ED1P6l3.png)


И вот все наши "слои" с которыми мы можем взаимодействовать.

![Слои](https://i.imgur.com/4L7hw11.png)
