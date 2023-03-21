﻿# Homebridge setup script

Что  делает этот скрипт?

* Добавляет репозиторий nodejs 19.x
* Ставит `nodejs` и `libavahi-compat-libdnssd-dev`
* Через npm ставит `homebridge`
* Создает папку `.homebridge` в домашнем каталоге текущего пользователя
* Копирует туда файл конфигурации с данными для запуска веб-интерфейса
* Устанавливает автоматически плагин веб-интерфейса  `homebridge-config-ui-x`
* Создает `homebridge.service` и запускает его

* Запустив этот скрипт на Raspberry Pi, имеющем доступ в сеть, через 5-7 минут Вы получите доступ к веб-интерфейсу homebridge по адресу http://raspberrypi.local:4444 в локальной сети.
* имя пользователя:`admin`
* пароль:`admin`
