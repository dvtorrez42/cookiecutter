# Cookiecutter Proyectos GOCDD

_Estructura estandarizada de proyecto para la Gerencia Operativa de Ciencia de Datos / SSPPBE / SECITD / GCBA._

### Requerimientos para usar este template de cookiecutter:
-----------
 - Python 2.7 ó 3.5+
 - [Paquete Cookiecutter de Python](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: Se puede instalar con pip o con conda:

``` bash
$ pip install cookiecutter
```

ó

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### Para comenzar un nuevo proyecto:
------------
1. Crear o navegar a la carpeta donde se creará el proyecto
2. Escribir uno de los siguientes comandos, dependiendo si se está usando GIT con http o ssh:

Con http

    cookiecutter -c master https://gitlab.com/gocdd/cookiecutter-gocdd/

Para ssh

    cookiecutter -c master git@gitlab.com:gocdd/cookiecutter-gocdd.git



### Estructura del proyecto resultante:
------------

La estructura de proyecto resultante se ve así: 

```
├── data                <- Para datos
├── Dockerfile          <- Dockerfile
├── Makefile            <- Makefile
├── notebooks           <- Notebooks para exploración
│   └── figures         <- Visualizaciones, reportes, etc.
├── README.md           <- Información e instrucciones
├── requierements.txt   <- Requerimientos
└── src                 <- Código
    └── __main__.py

```

