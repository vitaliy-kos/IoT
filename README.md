# IoT

Выполнена сборка контейнеров через скрипт install.sh

![Изображение](./img/image2.png)

## Mosquitto

В shell контейнера mosquitto отправка mqtt события из терминала
```
$ docker exec -it mosquitto sh
/ # mosquitto_pub -h 192.168.1.8 -p 1883 -t "GB/Temp" -m "28.5" -u "admin" -P "students"
```

## Telegraf
![Изображение](./img/image1.png)

## InfluxDB
![Изображение](./img/image3.png)

## Grafana
![Изображение](./img/image4.png)

## Node-red
![Изображение](./img/image5.png)

## Результат
![Изображение](./img/image6.png)