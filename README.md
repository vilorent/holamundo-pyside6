# holamundo-pyside6

Hola mundo con PySide6

Para ejecutar el *hola mundo*, necesitamos instalar antes Python3 y sus dependencias.

## Clonamos el proyecto en local y entramos en la carpeta del proyecto


```bash
$ git clone https://github.com/di-mcgrawhill/holamundo-pyside6.git
$ cd holamundo-pyside6/
```
## Instalación de Python3
![Logotipo de Python](https://es.schoolofdata.org/files/2017/07/python-logo-master-v3-TM-flattened.png)

### Linux
Python3 viene preinstalado en la mayoría de las distribuciones Linux, se puede comprobar so está instalado ejecutando la siguiente
orden en una terminal:
```bash
$ python3 --version
```
De no estar instalada puedes descargarla desde [aquí](https://www.python.org/downloads/)

Para más información de como instalar, consultar la [documentación](https://docs.python.org/3/)

### Windows
Descargar el instalador haciendo click [aquí](https://www.python.org/ftp/python/3.13.2/python-3.13.2-amd64.exe)

Se dispone de mas información sobre su instalación en el siguiente [enlace](https://www.python.org/downloads/windows/)

### macOS
Se dispone del binario ejecutable en el siguiente [enlace](https://www.python.org/ftp/python/3.13.2/python-3.13.2-macos11.pkg)

Se dispone de mas información sobre su instalación en el siguiente [enlace](https://www.python.org/downloads/release/python-3132/)

## Creación de un entorno virtual (venv)
Para crear un entorno virtual y poder aislar la ejecución del resto del sistema (sandbox), ejecutamos la siguiente instrucción en una
terminal.
```bash
$ python3 -m venv venv
```
## Activación del entorno virtual
### Linux y macOS
```bash
$ source venv/bin/activate
```
### Windows
```bash
$ venv\Scripts\activate.bat
```
## Instalación de dependencias
```bash
$ pip install -r requeriments.txt
```
## Ejecución
```bash
$ python3 src/holamundo_pyside6/holamundo.py
```
Nos mostrará la aplicación *holamundo_pyside6* en ejecución

![holamundo](https://doc.qt.io/qtcreator/images/qtcreator-new-qt-for-python-app-widgets-ready.webp)




