# Actualizar y configurar Python

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
Actualizar el cache del repositorio de paquetes 
```sh
sudo dnf makecache
```
Actualizar a Python 3.8
```sh
sudo dnf install python38
```
Seleccionar Python 3.8 como python3 predeterminado
```sh
sudo ln -fs /usr/bin/python3.8 /usr/bin/python3
```
## Agregar carpetas de instalación al PATH
Verificar carpetas en PATH
```sh
echo $PATH
```
Agregar carpetas de instalación al PATH
```sh
PATH=$PATH:/usr/local/bin
PATH=$PATH:/root/.local/bin
export PATH
```
```sh
source ~/.bash_profile
```
Verificar carpetas en PATH
```sh
echo $PATH
```
## Actualizar pip
Instalar pip de la versión de python instalada previamente
```sh
python3.8 pip install --user --upgrade --force-reinstall pip
```
