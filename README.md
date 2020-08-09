
# Laboratorio 1: Reconociendo razas de équidos

> Corresponde a un modelo de clasificación de imágenes . En este caso corresponde la clasificación de tres especies de la clase équidos (caballo, cebras y asnos)

La aplicación está disponible en https://claseudd-horse.herokuapp.com/


## Antes de empezar

El modelo corresponde a una red neurnal artificial Resnet, que fue entrenada con imágenes de 3 tipos de distinos de animales de la clase équidos:
Éstos son:
 -Caballos
 -Cebras
 -Asnos


## Las librerías necesarias son:

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

## Créditos

-La construcción del modelo está basada en las clases de Alonso Astroza de producto de datos del magister de Data Science, Universidad del desarrollo.
En particular este laboratorio se basa en las clases de [Francisco Ingham y Jeremy Howard](https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson2-download.ipynb). La aplicacion web está inspirada en el trabajo de [Shankar Jha](https://github.com/shankarj67/Water-classifier-fastai).
