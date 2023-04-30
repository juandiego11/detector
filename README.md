# detector de señales de transito

Este proyecto tiene como objetivo desarrollar un sistema aautimatico de reconicimiento de señales de transito, utilizando redes neuronales convolucionales.

## Imagenes de testeo y prueba 

Para desarrollar este tipo de modelo, es necesario tener datasets para el entrenamiento [Test](Test) y para hacer pruebas [train](Train)

## Creación del modelo 

Este [modelo](modelo.ipynb) es desarrollado en el lenguaje de Python debido a que tiene una gran cantidad de librerías que facilitan mucho el Machine Learning y el manejo de datos en general. Una vez se entrenan y prueban los datos se genera un [archivo](modelo.h5) que almacena los datos del modelo de aprendizaje generado.

## Aplicacion para detectar

Este es el producto final que tiene la capacidad de reconocer señales de tránsito en tiempo real, tiene dos modos, uno automático en el que identifica en tiempo real todas las imágenes que captura, y otro modo en el que su reconocimiento se activa al presionar una tecla.
En caso de que se quiera probar este [código](Detector.py) tener en cuenta lo siguiente:
-	Comprobar que el sistema cuenta con las librerías necesarias para correr el programa.
-	El dispositivo debe contar con una web cam.
-	La imagen a identificar se debe ubicar en el cuadro establecido en el ejecutable.



