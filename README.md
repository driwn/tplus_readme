#tplus

###Установка глобальных пакетов

```bash
npm i -g typescript @nestjs/cli pm2
``` 

###Установка клиента

Из файла /client

```bash
npm run i
``` 
```bash
npm run build
``` 

###Установка сервера

Из файла /server

```bash
npm run i
``` 
```bash
npm run build
``` 


###Запуск

Из файла /server

```bash
pm2 start ecosystem.config.js
``` 

##Мониторинг (см. больше https://pm2.keymetrics.io/docs/usage/process-management/)

###С логами
```bash
pm2 monit
``` 
###Показать процессы
```bash
pm2 l
``` 
