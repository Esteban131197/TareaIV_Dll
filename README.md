# TareaIV_Dll

Tarea #4 de Algoritmos y estructuras de datos 2.

Estudiantes: Esteban Morales y Bryan Solano.
Profesor: Antonio Gonzales.

*Preferible ejecutar en linux.

Comandos necesarios:

>>>Primeramente se debe ingresar la carpeta donde se haya descargado la totalidad del proyecto.

$docker build -tag geekflade_mongodb
$sudo docker run -it -v /data/db:/mongodata -p 27017:27017 --name geekflare_mongodb -d mongo

-_Apache:

$sudo docker build -t httdp:latest
$sudo docker run -dit --name my-running-app -p 8080:80 httdp:latest
localhost:8080/index.html

-_Node:

$sudo docker build -t node:nodejs
$sudo docker run -dit --name my-running-logic -p 3000:3000 -d node:nodejs
localhost:3000
