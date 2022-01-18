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
Seleccionar Python 3.8 como python3 predeterminado
```sh
sudo ln -fs /usr/bin/python3.8 /usr/bin/python3
```
Agregar carpeta de instalación al PATH de python
```sh
export PYTHONPATH="${PYTHONPATH}:/usr/local/bin"
export PATH=/usr/local/bin:$PATH
export PATH="/usr/local/bin:$PATH"
export PATH="/gabrokcy/local/bin:$PATH"
```
Actualizar pip

```sh
python3.8 -m pip install --upgrade --force-reinstall pip
```
## Instalar librerías básicas

Instalar y actualizar la librería de setuptools
```sh
sudo python3.8 -m pip install --upgrade setuptools
```

Instalar librerías de científicas de python3
```sh
sudo python3.8 -m pip install numpy scipy matplotlib ipython jupyter pandas sympy nose
```
