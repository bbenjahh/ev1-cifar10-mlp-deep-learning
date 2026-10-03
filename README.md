# ev1-cifar10-mlp-deep-learning
### Implementación de una Red Neuronal Multicapa (MLP) en TensorFlow/Keras para clasificar imágenes de CIFAR-10. Incluye preprocesamiento, diseño de arquitectura, optimización con Dropout, ajuste de Learning Rate y Early Stopping (40 épocas) para evitar overfitting, evaluando métricas como Accuracy, Precision y F1-Score.

# Instrucciones de Ejecución

### Este proyecto fue desarrollado para ejecutarse de manera directa y sin configuraciones locales complejas utilizando Google Colab, cumpliendo con los entregables de la evaluación.

*1)* Descargar el archivo: Clona este repositorio en tu equipo local o descarga directamente el archivo Deep_Learning_Evaluacion_1_Benjamin_Patiño.ipynb.

*2)* Cargar en el entorno: Ingresa a Google Colab, selecciona la opción Subir (Upload) en la ventana emergente y carga el archivo .ipynb.

*3)* Carga de Datos Integrada: No es necesario descargar ni adjuntar archivos .zip o .csv externos. La segunda celda del cuaderno utiliza la API nativa de TensorFlow/Keras para descargar, estructurar y preprocesar el dataset CIFAR-10 automáticamente.

*4)* Ejecución secuencial: Ejecuta cada bloque de código y celda Markdown en orden descendente (presionando el botón de Ejecutar Todo en el entorno de Google Colab, presionando el ícono de "Play" a la izquierda de cada celda o usando el atajo Shift + Enter).

*5)* Despliegue de Resultados: Permite que los bucles de entrenamiento finalicen (el modelo definitivo llegará a la época 40) para visualizar correctamente la extracción de los cuadros de métricas (Accuracy, Precision, Recall, F1-Score) y las gráficas de impacto de hiperparámetros.
