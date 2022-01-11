

# Installación de Jupyter Notebook

Actualizar el cache de repositorio de paquetes 

```sh
sudo dnf makecache
```
Instalar python y herramientas necesarias

```sh
sudo dnf install gcc python3-devel kernel-headers-$(uname -r)
```

Comprobar instalación y revisar la version de python

```sh
python3 --version
```

Instalar la biblioteca de setuptools

```sh
pip3 install -U pip setuptools
```
Instalar Jupyter Notebook

```sh
pip3 install --user jupyter
```
Comprobar instalación y revisar la versión de Jupyter

```sh
jupyter --version
```
Abrir Jupyer Notebook
```sh
jupyter notebook
```
