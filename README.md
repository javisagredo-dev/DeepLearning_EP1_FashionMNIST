# DeepLearning_EP1_FashionMNIST

Clasificación de imágenes de Fashion-MNIST con un perceptrón multicapa (MLP) en TensorFlow/Keras.
Evaluación Parcial 1 de DLY0100 Deep Learning.

## Contenido

- `notebooks/fashion_mnist_mlp_v3.ipynb`: cuaderno con todo el desarrollo. Incluye la carga y el
  preprocesamiento de los datos, el modelo base, los experimentos con hiperparámetros, funciones
  de activación, funciones de pérdida y regularización, el modelo final y las conclusiones.
- `images/`: figuras del modelo base.

## Ejecución en Google Colab

1. Abrir el cuaderno en Colab:
   https://colab.research.google.com/github/javisagredo-dev/DeepLearning_EP1_FashionMNIST/blob/main/notebooks/fashion_mnist_mlp_v3.ipynb
2. Ejecutar todas las celdas en orden desde Entorno de ejecución > Ejecutar todas.

El dataset se descarga automáticamente desde Keras. La ejecución completa tarda cerca de
1 hora y 40 minutos en CPU.

## Ejecución local

Requiere Python 3.10, 3.11 o 3.12.

```
pip install -r requirements.txt
jupyter notebook notebooks/fashion_mnist_mlp_v3.ipynb
```

## Referencias

- Fashion-MNIST (Xiao, Rasul y Vollgraf, 2017): https://github.com/zalandoresearch/fashion-mnist
- Documentación de Keras: https://keras.io/api/
- Documentación de TensorFlow: https://www.tensorflow.org/api_docs/python/tf
- Métricas de scikit-learn: https://scikit-learn.org/stable/modules/model_evaluation.html
- Dropout (Srivastava et al., 2014): https://jmlr.org/papers/v15/srivastava14a.html

## Autores

- Javier (javisagredo-dev)
- Diego (diegoiarm)
