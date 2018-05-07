# my-pwn-stuff

Название  |  Описание
----  |  ----
[dirsearch](https://github.com/maurosoria/dirsearch) | веб-кроулер, поиск скрытых директорий и файлов
[mitmproxy](https://github.com/mitmproxy/mitmproxy) | универсальный сниффер http/https трафика
[adminer](https://github.com/vrana/adminer) | аналог phpmyadmin из одного файла
[rogue mysql server](https://github.com/Gifts/Rogue-MySql-Server) | фейковый mysql сервер
[nmap](https://github.com/nmap/nmap) | сканирование сетей

CMS  |  Admin URL | DB
----  |  ---- | ----
Wordpress | /wp-admin/ | /wp-config.php
Joomla | /administrator/ | /configuration.php
Modx Evo | /manager/ | /manager/includes/config.inc.php
Bitrix | /bitrix/admin/ | /bitrix/php_interface/dbconn.php
Drupal | /user/ | /sites/default/settings.php
Opencart | | 
Magento | |
Netcat | | /vars.inc.php

Запуск веб-сервера на Python:  
```python3 -m http.server```
  
Проверка скорости записи на диск:  
```dd if=/dev/zero of=tempfile count=512 bs=1024k conv=fdatasync```
  
Проверка скорости чтения:  
```dd if=tempfile of=/dev/null count=512 bs=1024k```  
Не забыть потом удалить файл:  
```rm tempfile```
