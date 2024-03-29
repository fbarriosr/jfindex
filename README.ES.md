
## JFINDEX

Este programa genera índices que estiman la calidad de una funcional de la densidad mediante evaluación del cumplimiento del teorema de Koopmans. Necesita los archivos de salida de Gaussian de cálculos de punto sencillo (single point) con N, N+1 y N-1 electrones, como archivos de entrada. JFINDEX genera dos archivos (uno con extensión csv y otro extensión tex),  los cuales contienen de manera tabular los valores de los índices aludidos. Se pueden en emplear en computadores personales con Mac o Windows (jfindex) o en servidores con sistema operativo Linux (version jfindex-server).

## Limitaciones

El programa se desarrollo utilizando python base sin ningun package, debido a que el programa gaussian se encontraba en un clouster sin conexión a internet. Por ende se utilizaron estructuras de datos como listas,  stack y  arboles entre otras.

## Requerimientos

Requiere python 3.

Descarga el proyecto desde Github usando la opción zip o git clone. Mueve el proyecto JFINDEX a una carpeta en tu computador. 

Descomprime el archivo zip mediante consola o usando las herramientas del sistema operativo (click derecho descomprimir)
```
$unzip jfindex.zip
```
También puedes crear un alias en $ .bashrc. (en MAC OS se llama "bash_profile") Utiliza un editor de texto (vi, vim, nano u otro)
```
$ nano ~.bashrc
```
Y agrega esta ultima linea: 
```
alias jfindex='python /home/user/jfindex/jfindex.py'
```
la ruta es donde esta guardado el proyecto en tu computadora

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
