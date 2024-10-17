# UDELAR_FireBall. Detección de Bólidos en Videos del Cielo Nocturno

Este repositorio contiene cuatro archivos en formato **notebook** de Google Colab (Python) que gestionan un estudio de *Deep Learning* orientado a detectar bólidos en videos del cielo nocturno.  

## Archivos disponibles

1. **Colapsar Videos:**  
   - Este archivo procesa los videos para reducirlos a un solo frame por video, utilizando una técnica que toma el valor máximo de cada píxel en todas las frames.  
   - **Objetivo:** Optimizar los datos de entrada eliminando redundancia temporal y conservando los elementos más brillantes (como los bólidos).

2. **Modelo de Deep Learning basado en ResNet-152:**  
   - En este notebook se entrena un modelo de *Convolutional Neural Network (CNN)* utilizando la arquitectura **ResNet-152**.  
   - **Objetivo:** Identificar patrones en los frames colapsados para detectar la presencia de bólidos.

3. **Predicciones sobre Conjunto de Datos:**  
   - Este archivo permite realizar predicciones utilizando el modelo entrenado sobre un conjunto de datos específico.  
   - **Objetivo:** Evaluar el desempeño del modelo aplicando predicciones y observando resultados sobre datos reales.

4. **Análisis de Resultados:**  
   - Este archivo realiza un análisis detallado de los resultados obtenidos por el modelo entrenado. Incluye visualización de métricas, interpretación de predicciones y posibles mejoras.

## Requisitos

- **Google Colab:** Los notebooks están diseñados para ejecutarse en Colab, donde se aprovecha el entorno con GPU.
- **Python 3.7+**
- Bibliotecas utilizadas: TensorFlow, OpenCV, NumPy, entre otras (ver cada notebook para más detalles).

## Instrucciones de Uso

1. Sube los videos del cielo nocturno al entorno de Google Colab.
2. Ejecuta el notebook correspondiente para **colapsar los videos**.
3. Usa el archivo del **modelo CNN** para entrenar la red basada en ResNet-152.
4. Ejecuta el notebook de **predicciones** para evaluar el modelo con datos reales.
5. Usa el **notebook de análisis** para interpretar los resultados obtenidos.

## Objetivo del Proyecto

Este proyecto busca detectar bólidos (meteoros brillantes) en videos del cielo nocturno mediante técnicas de *Deep Learning*, contribuyendo al estudio astronómico y a la observación de eventos naturales en el espacio.

---

¡Gracias por visitar este repositorio! 🚀
