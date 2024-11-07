
# Proyecto de Clasificación de Reseñas de Películas

Este proyecto desarrolla un modelo de machine learning para detectar automáticamente las reseñas negativas de películas. La plataforma Film Junky Union busca mejorar la experiencia de los usuarios al categorizar y filtrar las reseñas en su comunidad de aficionados al cine clásico.

## Descripción del Proyecto

Usando un conjunto de datos de reseñas de IMDB, se entrena un modelo de clasificación para diferenciar reseñas positivas de negativas. El modelo debe alcanzar una métrica de **F1 Score** de al menos 0.85 para considerarse satisfactorio.

## Estructura del Análisis

1. **Inicialización y Carga de Datos**
   - Se cargan las librerías necesarias para el análisis y se prepara el entorno de trabajo.
   - Se cargan los datos de reseñas de IMDB, y se examina su estructura inicial.

2. **Preprocesamiento de Datos**
   - Se limpian y transforman los datos para el análisis.
   - Se implementan técnicas de tokenización y procesamiento de texto para preparar las reseñas como entrada del modelo.

3. **Entrenamiento de Modelos de Clasificación**
   - Se prueban varios algoritmos de clasificación y se ajustan los hiperparámetros para maximizar la precisión del modelo.
   - Los modelos se evalúan en función de su **F1 Score** para asegurar que cumplan con el umbral de 0.85.

4. **Evaluación y Selección del Modelo Óptimo**
   - Los modelos se evalúan en un conjunto de prueba y se selecciona el que mejor clasifica las reseñas de manera precisa y confiable.

5. **Conclusiones**
   - Se finaliza el análisis con recomendaciones para la implementación del modelo en la plataforma Film Junky Union.

## Requisitos

- **Python 3.7+**
- Librerías: `numpy`, `pandas`, `matplotlib`, `seaborn`, `tqdm`

## Cómo Ejecutar el Proyecto

1. Clona el repositorio.
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecuta el notebook `Project_14.1.ipynb` para reproducir el análisis y entrenar el modelo.
