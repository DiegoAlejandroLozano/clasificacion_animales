# Clasificación de animales

Librerías utilizadas: `Keras`, `Pandas`, `Numpy`  y `Scikit-Learn`

Este proyecto tiene como objetivo principal la clasificación de imágenes para determinar si pertenecen a la categoría de perro o gato. Para alcanzar este propósito, se ha implementado una red neuronal convolucional que consta de tres capas convolucionales. En la primera capa convolucional, se ha aplicado un filtro de 32 características, seguido por un filtro de 64 características en la segunda capa y un filtro de 128 características en la última capa. Todos estos filtros tienen un tamaño de 3x3.

Adicionalmente, se ha incorporado una capa completamente conectada con 64 neuronas, seguida por una capa de salida que utiliza una función de activación tipo sigmoide. El conjunto de datos utilizado para el entrenamiento consta de 8000 imágenes, mientras que se reservaron 2000 imágenes para la fase de prueba. Los resultados obtenidos muestran una precisión durante el entrenamiento de 0.8708 y una precisión en la validación de 0.8480.

Para correr el repositorio de forma local se debe crear un entorno virtual con el siguiente comando:

    Python3 -m venv nombre_entorno_virtual

Se debe activar el entorno virtual e instalar las librerías requeridas a través del archivo requirements.txt

    pip install -r requirements.txt
