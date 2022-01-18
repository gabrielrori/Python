# Instalación de librerías básicas para Python

## Instalar herrmaientas necesarias

Actualizar los paquetes y volver a cargar el repositorio
```sh
sudo dnf update -y 
```
Actualizar el cache del repositorio de paquetes 
```sh
sudo dnf makecache
```
Instalar las build tools necesarias

```sh
sudo dnf install gcc python3-devel kernel-headers-$(uname -r)
```
Instalar y actualizar la librería de setuptools
```sh
sudo python3.8 -m pip install --user --upgrade - U setuptools
```


## Instalar librerías básicas


Instalar librerías de científicas de python3
```sh
sudo python3.8 -m pip install --user numpy scipy matplotlib ipython jupyter pandas sympy nose
```
