# Librerías básicas de python

## Comprobar la versión de python3 y pip3

```sh
python3 --version
```
```sh
pip3 --version
```

## Actualizar python 

Actualizar los paquetes y volver a cargar el repositorio
```sh
sudo dnf update -y 
```
Actualizar a Python 3.8
```sh
sudo dnf install python38
```

Actualizar pip

```sh
pip3 install --upgrade pip
```
## Instalar librerías básicas

Instalar y actualizar la librería de setuptools

```sh
pip3 install --upgrade setuptools
```
Instalar librerías de científicas de python

```sh
pip3 instlal matplotlib
pip3 install --user numpy scipy matplotlib ipython jupyter pandas sympy nose
