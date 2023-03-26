[Spanish Version](https://github.com/fbarriosr/jfindex/blob/master/README.ES.md)

## JFINDEX

This program generates indices that estimate the quality of a density functional by evaluating compliance with the Koopmans theorem. You need the Gaussian output files of single point calculations with N, N+1, and N-1 electrons, as input files. JFINDEX generates two files (one with a csv extension and the other with a tex extension), which contain the values of the aforementioned indexes in a tabular manner. They can be used on personal computers with Mac or Windows (jfindex) or on servers with Linux operating system (version jfindex-server).

## Requirements

It requires python 3.

## Installation

Download the project from Github using the zip or git clone option. Move the JFINDEX project to a folder on your computer.

Unzip the zip file via console or using the operating system tools (right click unzip)
```
$unzip jfindex.zip
```
You can also create an alias in $ .bashrc. (on MAC OS it is called "bash_profile") Use a text editor (vi, vim, nano or other)
```
$ nano ~.bashrc
```
And add this last line:
```
alias jfindex='python /home/user/jfindex/jfindex.py'
```
the path is where the project is saved on your computer

## Execution
You should have all 3 .log files (JFINDEX project), then run the program via python command

Graphic version:
```
$ python /home/user/jfindex/jfindex.py'
```
Command Line Version:
```
$ python /home/user/jfindex/jfindex.py' more
```
or just used the alias jfindex:

Graphic version:
```
$jfindex
```
![](https://webdesign.s3-us-west-2.amazonaws.com/jfindex/jfindex.png)

Command Line Version:
```
$jfindex more
```
![](https://webdesign.s3-us-west-2.amazonaws.com/jfindex/jfindex_more.png)
