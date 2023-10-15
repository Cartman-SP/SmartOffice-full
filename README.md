# Ссылки
| Описание | Репозиторий |
| ------ | ------ |
| Server repo | [https://github.com/Cartman-SP/SmartOfficeServe](https://github.com/Cartman-SP/SmartOfficeServer) |
| App repo | [[https://github.com/Cartman-SP/SmartOffices](https://github.com/Cartman-SP/SmartOffices)](https://github.com/Cartman-SP/SmartOffices) |
# Руководство по запуску сервера
```sh
pip install django
pip install djangorestframework
```
```sh
ipconfig
```
в результате получить что-то типо такого, отсюда нам нужен Ipv4
```sh
Адаптер беспроводной локальной сети Беспроводная сеть:

   DNS-суффикс подключения . . . . . :
   Локальный IPv6-адрес канала . . . : fe80::da8e:7b4a:2ef4:db17%8
   IPv4-адрес. . . . . . . . . . . . : 192.168.1.127
   Маска подсети . . . . . . . . . . : 255.255.255.0
   Основной шлюз. . . . . . . . . : 192.168.1.1

```
после чего запускаем из папки с проектом
```sh
python manage.py runserver 'ваш ipv4'
```
