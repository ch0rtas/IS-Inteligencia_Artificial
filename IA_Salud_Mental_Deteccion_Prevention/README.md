# IA en Salud Mental: Detección y Prevención

Este repositorio contiene el proyecto **IA en Salud Mental: Detección y Prevención**, desarrollado como parte del curso _"Inteligencia Artificial"_ en el grado de Ingeniería de Software. El objetivo principal fue aplicar técnicas de IA para la detección temprana de trastornos mentales, utilizando modelos de aprendizaje automático para identificar patrones en los datos clínicos y mejorar la prevención.

[Ir al proyecto en GitHub](https://github.com/ch0rtas/SWE-Inteligencia_Artificial/tree/main/IA_Salud_Mental_Deteccion_Prevention)

## Descripción del Proyecto

La salud mental es un componente esencial del bienestar humano, sin embargo, millones de personas en todo el mundo enfrentan trastornos mentales como ansiedad, depresión y estrés, los cuales representan una carga significativa para los individuos y las sociedades. Según la Organización Mundial de la Salud (OMS), una de cada ocho personas vive con algún tipo de trastorno mental, y esta cifra ha aumentado considerablemente tras la pandemia de COVID-19. A pesar de su alta prevalencia, el acceso a diagnóstico y tratamiento oportunos sigue siendo limitado debido a barreras como la falta de recursos, estigmas sociales y la insuficiencia de profesionales capacitados. 

En este contexto, la inteligencia artificial (IA) emerge como una herramienta prometedora para abordar estas limitaciones. La IA permite analizar grandes volúmenes de datos provenientes de texto, voz, patrones de uso de dispositivos móviles, e incluso redes sociales, para identificar signos tempranos de trastornos mentales. Además, su capacidad para personalizar análisis y recomendaciones la convierte en una aliada potencial para la prevención y la intervención temprana. 

Este proyecto busca explorar el papel de la IA en la salud mental, destacando sus aplicaciones actuales, limitaciones y oportunidades futuras. Como complemento, se entrenará un modelo propio para evaluar la viabilidad de utilizar IA en el análisis de síntomas comunes, proporcionando un enfoque práctico a este análisis teórico.

## Estructura del Proyecto

Este repositorio se organiza en los siguientes archivos y carpetas:

### **Archivos principales**

- **IA en salud mental - Manuel Martínez Ramón.pdf**: Documento con la descripción completa del proyecto, incluyendo los objetivos, metodología, resultados y conclusiones.
- **IA_en_salud_mental_Manuel_Martinez_Ramon.ipynb**: Notebook donde se implementan los modelos de IA para la detección y prevención en salud mental.
- **LICENSE**: Archivo con la licencia del proyecto (MIT License).
- **README.md**: Este archivo con la descripción y detalles del proyecto.

### **Estructura de carpetas**

- **EjemplosDocumentos/**: Contiene archivos de ejemplo utilizados en la evaluación del proyecto.
  - `Beatriz Ruiz_evaluacion.pdf`: Evaluación de los resultados de los modelos con el caso de Beatriz Ruiz.
  - `Javier Gómez_evaluacion.xlsx`: Evaluación de los resultados de los modelos con el caso de Javier Gómez.
  - `Laura Martínez_evaluacion.pdf`: Evaluación de los resultados de los modelos con el caso de Laura Martínez.

## Evaluación

Para evaluar el rendimiento del modelo, se utilizaron varias métricas de rendimiento: precisión, recall, F1-score y accuracy. Estas métricas son fundamentales para comprender no solo qué tan preciso es el modelo, sino también cómo maneja las diferentes clases de emociones. La precisión mide qué porcentaje de las predicciones del modelo son correctas, el recall mide qué porcentaje de las emociones verdaderas fueron detectadas, y el F1-score es la media armónica entre la precisión y el recall.

Los resultados de la evaluación en el conjunto de prueba mostraron una precisión del 92.95%, lo que indica que el modelo tiene un alto rendimiento en la clasificación de emociones. Además, se observó un rendimiento equilibrado en las métricas de precisión y recall, lo que sugiere que el modelo es capaz de identificar correctamente las emociones sin mostrar un sesgo hacia ninguna clase en particular. Este rendimiento es comparable con otros modelos de vanguardia en el campo de PLN para clasificación de emociones, como BERT y RoBERTa. 

El modelo desarrollado ha demostrado ser altamente efectivo en la clasificación de emociones, alcanzando una precisión de 92.95% en el conjunto de prueba. Esto sugiere que la IA podría ser útil en la detección de emociones en textos relacionados con salud mental, ayudando a identificar trastornos emocionales como la depresión o la ansiedad. Sin embargo, se reconoce que este modelo aún tiene limitaciones, y que es necesario seguir mejorando tanto el modelo como la metodología para implementarlo en entornos clínicos reales.

## Conclusión

### Resumen de los aprendizajes del trabajo teórico y práctico

Este proyecto ha proporcionado una comprensión profunda de cómo la Inteligencia Artificial (IA) puede ser aplicada al campo de la salud mental, enfocándose en el análisis de emociones y la predicción de trastornos emocionales. A través de la creación de un modelo de clasificación de emociones basado en el dataset "emotion", hemos aprendido los principios fundamentales del procesamiento de lenguaje natural (PLN), tokenización, y cómo trabajar con modelos preentrenados, en este caso, DistilBERT.

En el ámbito práctico, se ha logrado entrenar un modelo de IA con una precisión de evaluación del 92.95%, lo que demuestra la efectividad del uso de modelos basados en transformers en tareas de clasificación de emociones en texto. Además, el proyecto ha incluido el desarrollo de una interfaz interactiva que permite a los usuarios interactuar directamente con el modelo, recopilando datos de pacientes en tiempo real y generando informes en PDF y Excel. Este enfoque práctico ha consolidado nuestra comprensión sobre la integración de la IA en aplicaciones del mundo real, permitiendo su uso potencial para apoyar el diagnóstico y la evaluación de trastornos emocionales.

## Cómo usar este repositorio

1. **Clona este repositorio:**  
   ```bash
   git clone https://github.com/ch0rtas/SWE-Inteligencia_Artificial.git
   cd IA_Salud_Mental_Deteccion_Prevention
   ```

2. **Ejecuta el notebook:**  
   - Abre `IA_en_salud_mental_Manuel_Martinez_Ramon.ipynb` para entrenar y evaluar los modelos de detección y prevención.

3. **Carga los datos y modelos entrenados:**  
   - Los datos clínicos de ejemplo se encuentran en la carpeta `EjemplosDocumentos/`. Puedes usar los archivos de evaluación para analizar los resultados.

4. **Analiza y personaliza:**  
   - Experimenta con las configuraciones de los modelos y el preprocesamiento de datos para mejorar los resultados.

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE). Puedes usar, modificar y distribuir el código siempre que incluyas atribución al autor original.

---

¡Esperamos que este proyecto sea útil para tus investigaciones y aprendizaje en el campo de la Inteligencia Artificial aplicada a la salud mental!
