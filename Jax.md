


# Instalación de jax

## Instalación

### Instalación de jax para procesamiento por CPU
```sh
pip3 install --upgrade pip
```
```sh
pip3 install --upgrade "jax[cpu]"
```

### Instalación de jax para procesamiento por GPU 

```sh
pip install --upgrade pip
```
```sh
pip3 install --upgrade "jax[cuda]" -f https://storage.googleapis.com/jax-releases/jax_releases.html
```
#### Para una versión en particular

Requisito previo: CUDA y CuDNN. CUDA 10 JAX requiere CuDNN 7, mientras CUDA 11 JAX requiere CuDNN 8. 
```sh
pip install --upgrade pip
```

```sh
pip3 install jax[cuda11_cudnn82] -f https://storage.googleapis.com/jax-releases/jax_releases.html
```
```sh
pip3 install jax[cuda11_cudnn805] -f https://storage.googleapis.com/jax-releases/jax_releases.html
```


Revisar archivos.py realizados


----------------------------------------------------------------------------
