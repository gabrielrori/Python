


# Intalación de sphinx

### Instalación
Instalar sphinx
```sh
pip3 install -U sphinx
```
Instalar paquete para Markdown
```sh
pip3 install --upgrade myst-parser
```
Instalar paquete para jupyter notebook
```sh
pip3 install nbsphinx --upgrade --user
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
