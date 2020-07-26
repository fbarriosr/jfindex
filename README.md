## JFINDEX

Es un proyecto "UNIX" para calcular las Energías de los archivos generados por los experimentos Químicos.
## Requerimientos

Requiere python 3.

## Installation

Copia la carpeta JFINDEX en tu computador. 

Descomprime el archivo
```
$ tar -xvf  jfindex.tar
```
También puedes crear un alias en $ .bashrc. Utiliza un editor de texto 
```
$ vi ~.bashrc
```
Y agrega esta ultima linea: 
```
alias jfindex='python /home/user/jfindex/jfindex.py'
```

## Ejecución
Debes tener los 3 archivos .log (proyecto JFINDEX), luego ejecutar el programa mediante el comando python

Versión Gráfica:
```
$ python /home/user/jfindex/jfindex.py'
```
Version Linea de Comandos:
```
$ python /home/user/jfindex/jfindex.py' more
```
o simplemente usado el alias jfindex:

Versión Gráfica:
```
$ jfindex
```
![](https://webdesign.s3-us-west-2.amazonaws.com/jfindex/jfindex.png)

Version Linea de Comandos:
```
$ jfindex more
```
![](https://webdesign.s3-us-west-2.amazonaws.com/jfindex/jfindex_more.png)
