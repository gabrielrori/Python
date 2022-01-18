


# Intalación de sphinx

### Instalación
Instalar sphinx
```sh
sudo python3.8 -m pip install --user -U sphinx
```
Instalar paquete para Markdown
```sh
sudo python3.8 -m pip install --user --upgrade myst-parser
```
Instalar paquete para jupyter notebook
```sh
sudo python3.8 -m pip install nbsphinx --user --upgrade --user
```
### Crear un documento
```sh
sphinx-quickstart
```
Modificación de config.rst
```sh
Descomentar las 3 línas de import
```
 Agregar extensiones
- Markdown
- Jupyter

Agregar temas

Modificación de index.rst

Finalmente, crear el html:
```sh
make html
```
----------------------------------------------------------------------------
