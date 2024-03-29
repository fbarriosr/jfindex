[Spanish Version](https://github.com/fbarriosr/jfindex/blob/master/README.ES.md)

## JFINDEX

This program generates indices that estimate the quality of a density functional by evaluating its compliance with Koopmans' theorem. Gaussian output files of single point calculations with N, N+1, and N-1 electrons are required as input files. JFINDEX generates two files (one with a csv extension and the other with a latex extension), which contain the values of the aforementioned indexes in a tabular format. They can be used on personal computers with Mac or Windows (JFINDEX) or on servers with Linux operating system (version JFINDEX-SERVER).

## Limitations

The program was developed using base python without any package, because the gaussian program was in a cluster without internet connection. Therefore, data structures such as lists, stacks, and trees, among others, were used.

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
