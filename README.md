
# Laboratorio 1: Publicando un modelo de deep learning en Heroku


> Corresponde a un modelo de clasificación de imágenes . En este caso corresponde la clasificación de tres especies de la clase équidos (caballo, cebras y asnos)

La aplicación está disponible en https://claseudd-horse.herokuapp.com/


## Antes de empezar


## Instalación de librerías necesarias

### Pytorch

- Seguir las [instrucciones oficiales](https://pytorch.org/get-started/locally/) seleccionando el sistema operativo correspondiente.
Para este ejemplo se instaló pytorch 1.5.0 versión para cpu

### fastai [(instrucciones)](https://docs.fast.ai/install.html)
```
pip install fastai
```

### Flask [(instrucciones)](https://flask.palletsprojects.com/en/1.1.x/installation/)
```
pip install Flask
```
### Si se desea modificar aún más la aplicación web, se recomienda usar un [ambiente virtual](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/) (además es una muy buena práctica al momento de programar en Python)

## Construcción del Modelo de Deep Learning

- Se deben seguir las instrucciones explicadas en este [notebook](https://github.com/aastroza/clase_productodatos_2019_udd/blob/master/notebooks/ejemplo_clasificador_fastai.ipynb).

## Modificación de la aplicación web

### Poner el modelo (archivo .pkl) en la carpeta `models` 

### Cambiar los nombres de las clases

- Abrir "app.py" y buscar la variable llamada `classes` y cambiar su contenido con las clases del clasificador propio.

### Modificaciones de la Interfaz

- Modificar los archivos en los directorios `templates` y `static`.

- `index.html` maneja la parte gráfica y `main.js` el comportamiento.



## Conexión con Heroku

- El primer paso es crear una aplicación y darle un nombre.

- En "Deployment Method" escoger "Connect to Github" y seguir las instrucciones.

- Una vez que esté listo, aparecerá un link para revisar la aplicacion en el navegador, como este: https://facemask-udd.herokuapp.com/

## Créditos

- La construcción del modelo está basada en las clases de [Francisco Ingham y Jeremy Howard](https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson2-download.ipynb). La aplicacion web está inspirada en el trabajo de [Shankar Jha](https://github.com/shankarj67/Water-classifier-fastai).
