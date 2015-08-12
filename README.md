#Это конфиг для nginx+php-fpm
Стандартный конфиг хостов для php-fpm
<p>В файле nginx-fpm - конфиг работы php(стандартный)</p>
В файле nginx-drupal-fpm - конфиг для работы Drupal 7 nginx
#Подводные камни
<p>В конфиге nginx.conf /etc/nginx/nginx.conf,добавтье в раздел http строчку, client_max_body_sixe 100m;</p>
<p>Перезагрузите сервер sudo service nginx restart</p>
