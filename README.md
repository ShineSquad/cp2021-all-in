# Shine Squad
## Кейс Ростелеком

### Посмотреть
http://45.134.255.154:30365/cp-vue/dist/

### Содержание
1. Docker-flask - контейнер python-flask
1. front - vue-app, основное приложение
1. kubernetes-script - скрипты для запуска контейнеров в kubernetes + configfile
1. TVS-auth - авторизация через ЕСИА
1. bigdata - анализ тестового датасета с Яндекс диска

### Kubernetes (team6)

Два контейнера:
1. httpd - основной сервер, http://45.134.255.154:30365
1. solr555 - поиск по hadoop, http://45.134.255.154:31454