# Кластеризация и балансировка нагрузки

# Домашнее задание к занятию 2 «Кластеризация и балансировка нагрузки»
## Михеев Алексей

# Задание 1
### Запустите два simple python сервера на своей виртуальной машине на разных портах
### Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
### Настройте балансировку Round-robin на 4 уровне.
### На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

[HAPROXY conf file](https://github.com/Alm798/9.03/blob/main/haproxy.cfg)

![Screen2](https://github.com/Alm798/9.03/blob/main/2.png)		

# Задание 2
### Запустите три simple python сервера на своей виртуальной машине на разных портах
### Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
### HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
### На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

[HAPROXY conf file 2](https://github.com/Alm798/9.03/blob/main/haproxy1.cfg)

![Screen4](https://github.com/Alm798/9.03/blob/main/Screenshot_5.jpg)
