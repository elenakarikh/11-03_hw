## Домашнее задание к занятию "ELK" - Карих Елена
---
### Задание 1 Elasticsearch

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.
Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty',
сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

### Решение 1

Скачала все модули через VPN с официального сайта.
Приложенный запрос для ДЗ ни как не получался(( нашла в доке, что начиная с 8 версии необходимо указывать логин/пароль..
Прошу разрешить изменить команду.

![scrin](scrin0.png) 
![scrin](scrin1.png)
---
### Задание 2 Kibana

Установите и запустите Kibana.
Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console,
где будет выполнен запрос GET /_cluster/health?pretty.

### Решение 2

![scrin](scrin2.png)

---
### Задание 3 Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

### Решение 3

![scrin](scrin3.png)

---
### Задание 4 Filebeat

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

### Решение 4

![scrin](scrin4.png)

---
