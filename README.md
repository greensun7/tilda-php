= Класс для работы с API Tilda.cc и примеры использования

== Установка

Копируете архив и разворачиваете его в корне.

== Содержание

Файл config.php.example нужно переименовать (убрать .example) и указать свои параметры (это файл настроек)

Файл index.php - на него можно вести все запросы и он должен отображать HTML-страницы

Файл webhook.php - прописывается в личном кабинет на сайте Tilda.cc

Файл tildasync.php - скрипт занимающийся синхронизаций файлов (с использованием класса classes/Tilda.php). Его лучше подключать в кроне (хотя он может работать и в ручном режиме)

Файл classes/Tilda.php - класс, содержит методы обращения к API, а также вспомогательные методы

