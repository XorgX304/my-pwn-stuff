# my-pwn-stuff

Название  |  Описание
----  |  ----
[dirsearch](https://github.com/maurosoria/dirsearch) | веб-кроулер, поиск скрытых директорий и файлов
[mitmproxy](https://github.com/mitmproxy/mitmproxy) | универсальный сниффер http/https трафика
[adminer](https://github.com/vrana/adminer) | аналог phpmyadmin из одного файла
[rogue mysql server](https://github.com/Gifts/Rogue-MySql-Server) | фейковый mysql сервер
[nmap](https://github.com/nmap/nmap) | сканирование сетей

CMS  |  Admin URL | DB | Version
----  |  ---- | ---- | ----
Wordpress | /wp-admin/ | /wp-config.php | /wp-includes/version.php
Joomla | /administrator/ | /configuration.php | 
Modx Evo | /manager/ | /manager/includes/config.inc.php | 
Bitrix | /bitrix/admin/ | /bitrix/php_interface/dbconn.php | 
Drupal | /user/ | /sites/default/settings.php | /modules/system/system.info
Opencart | /admin/ | /config.php | 
Magento | | | 
Netcat | | /vars.inc.php | 

[Yandex Safebrowsing](https://yandex.ru/support/webmaster-troubleshooting/threats/dangerous-sites.html)  
[Avira](https://analysis.avira.com/ru/submit-urls)  
[BitDefender](https://www.bitdefender.com/submit/)  
[AVG](https://secure.avg.com/submit-sample)  
[Dr.Web](https://support.drweb.ru/new/urlfilter/?lng=ru)  
[Facebook](https://www.facebook.com/help/contact/571927962827151)  
[VK](https://vk.com/support?act=new&from=hd)  
[Eset Nod32](mailto:sdd@esetnod32.ru)  
[Trustwave](https://www3.trustwave.com/support/submit-url.asp)


Запуск веб-сервера на Python:  
```python3 -m http.server```
  
Проверка скорости записи на диск:  
```dd if=/dev/zero of=tempfile count=512 bs=1024k conv=fdatasync```
  
Проверка скорости чтения:  
```dd if=tempfile of=/dev/null count=512 bs=1024k```  
Не забыть потом удалить файл:  
```rm tempfile```
