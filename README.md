# Covid19-Detection-Computervision
Este proyecto desarrolla un modelo de clasificación multiclase para la detección automática de COVID-19, Neumonía Viral y pulmones sanos a partir de radiografías de tórax. Utiliza técnicas avanzadas de Computer Vision para apoyar el diagnóstico médico temprano.

# COVID-19 Detection via Chest X-Ray using Deep Learning

## Descripción
Este proyecto desarrolla un modelo de clasificación multiclase para la detección automática de COVID-19, Neumonía Viral y pulmones sanos a partir de radiografías de tórax. Utiliza técnicas avanzadas de **Computer Vision** para apoyar el diagnóstico médico temprano.

## Stack Tecnológico
* **Framework:** TensorFlow / Keras
* **Arquitectura:** VGG16 (Transfer Learning)
* **Librerías:** OpenCV, Pandas, Matplotlib, Scikit-learn

## Estrategia de Ingeniería de IA
* **Transfer Learning & Fine-Tuning:** Uso de la red pre-entrenada VGG16, adaptando las últimas capas para la clasificación específica de patologías respiratorias.
* **Data Augmentation:** Implementación de rotaciones, zooms y desplazamientos, lo cual **incrementó la precisión en un 14%**, vital debido al tamaño reducido del dataset.
* **Optimización de Red:** Incorporación de funciones de activación **ReLU** y capas de **Dropout** para prevenir el sobreajuste y asegurar la generalización en datos clínicos reales.

## Resultados Técnicos
* **Precisión (Accuracy):** 90% en el set de prueba.
* **Métricas por Clase:** El modelo presenta un rendimiento excepcional identificando casos de COVID-19, minimizando los falsos negativos en esta categoría crítica.

<img width="673" height="477" alt="image" src="https://github.com/user-attachments/assets/b4030665-a766-4a22-9d22-fe15e90820fe" />


<img width="653" height="214" alt="image" src="https://github.com/user-attachments/assets/92aa3fc5-2ca8-4bbe-afa3-13ec3ab06c1c" />


## ⚙️ Instalación
1. Clonar el repositorio.
2. Asegurar entorno con GPU (Recomendado: Google Colab T4).
3. Ejecutar `Proyecto_final_Deep_learning_R.ipynb
