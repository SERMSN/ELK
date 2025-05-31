# Домашнее задание к занятию «ELK» - Малявко Сергей (11-03)

### Задание 1. Elasticsearch

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

#### Ответ к заданию 1.

##### Скриншот результата команды скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty':
![Скриншот результата команды скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty' рис. 1](images/elk-1.png)

### Задание 2. Kibana

Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

#### Ответ к заданию 2.

##### Скриншот интерфейса Kibana с запросом GET /_cluster/health?pretty:
![Скриншот интерфейса Kibana рис. 2](images/elk-2.png)

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

#### Ответ к заданию 3.

##### Скриншот интерфейса Kibana с собераеммым логом от Nginx:
![Скриншот интерфейса Kibana с собераеммым логом от Nginx рис. 3](images/elk-3.png)

### Задание 4. Filebeat.

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

##### Скриншот интерфейса Kibana с собераеммым логом от Nginx поставленные Filebeat:
![Скриншот интерфейса Kibana с собераеммым логом от Nginx поставленные Filebeat рис. 4](images/elk-4.png)
