# Generación de Texto y Diálogo con Modelos de Redes Neuronales y Transformers

Este repositorio contiene el proyecto **Generación de Texto y Diálogo con Modelos de Redes Neuronales y Transformers**, desarrollado como parte del curso _"Inteligencia Artificial"_ en el grado de Ingeniería de Software. El objetivo principal fue entrenar y evaluar diferentes modelos de redes neuronales, incluidos RNN, LSTM, GRU, y Transformers, para la generación de texto y simulación de diálogos entre parlamentarios.

[Ir al proyecto en GitHub](https://github.com/ch0rtas/IS-Inteligencia_Artificial/tree/main/Generacion_Texto_Dialogo_Redes_Neuronales_Transformers)

## Descripción del proyecto

Este proyecto implementa y evalúa varios modelos para la generación de texto, con énfasis en el uso de redes neuronales recurrentes (RNN), LSTM, GRU y Transformers. El objetivo es generar texto coherente a partir de un conjunto de datos de discursos de parlamentarios y simular un diálogo entre tres de ellos.

### Características principales
- **Modelos RNN, LSTM, y GRU:** Comparación de rendimiento entre diferentes arquitecturas de redes neuronales.
- **Transformers:** Exploración de la aplicación de Transformers para la generación de texto (aunque con limitaciones).
- **Evaluación de calidad:** Uso de métricas como perplejidad, BLEU y ROUGE para evaluar la calidad del texto generado.
- **Generación de Diálogo:** Implementación de un sistema de diálogo entre tres parlamentarios, con 5 rondas de interacción.
- **Optimización de modelos:** Ajustes en la arquitectura y los parámetros de los modelos para mejorar la coherencia y relevancia del texto generado.

## Estructura del proyecto

Este repositorio contiene los siguientes archivos clave:  
- `Generacion_Texto.ipynb`: Notebook principal con la implementación de la generación de texto usando RNN, LSTM, GRU y Transformers.  
- `benchmarkAbascal.ipynb`: Notebook con la evaluación del modelo entrenado para el parlamentario Abascal.  
- `benchmarkCasado.ipynb`: Notebook con la evaluación del modelo entrenado para el parlamentario Casado.  
- `benchmarkSanchez.ipynb`: Notebook con la evaluación del modelo entrenado para el parlamentario Sánchez.  
- `dialogoCongreso.ipynb`: Notebook donde los modelos generados interactúan en un diálogo simulado entre los tres parlamentarios.  
- `Memoria_Proyecto.pdf`: Documentación completa del proyecto, incluyendo gráficos y análisis.  
- `models/`: Carpeta que contiene los modelos entrenados guardados en formato `.h5` o `.keras`.


## Cómo usar este repositorio

1. **Clona este repositorio:**  
   ```bash
   git clone https://github.com/ch0rtas/IS-Inteligencia_Artificial.git
   cd Generacion_Texto_Dialogo_Redes_Neuronales_Transformers
   ```

2. **Ejecuta los notebooks:**  
   - Abre `Generacion_Texto.ipynb` para entrenar y evaluar los modelos de generación de texto.  
   - Abre `benchmarkAbascal.ipynb`, `benchmarkCasado.ipynb` o `benchmarkSanchez.ipynb` para evaluar el desempeño de cada modelo.  
   - Abre `dialogoCongreso.ipynb` para ver el diálogo simulado entre los parlamentarios.

3. **Carga los modelos entrenados:**  
   - Los modelos entrenados se encuentran en la carpeta `models/`. Carga el modelo correspondiente en cada notebook para realizar las evaluaciones o el diálogo.

4. **Analiza y modifica:**  
   - Experimenta con las configuraciones para mejorar la calidad del texto generado o personalizar el diálogo.

## Resultados principales

### Modelos Generados
- **LSTM-Abascal:** Mejor modelo para generar texto coherente con un accuracy aceptable.  
- **LSTM-Casado:** Modelo con texto generado ligeramente menos coherente, pero con tiempos de entrenamiento más rápidos.  
- **LSTM-Sanchez:** Modelo más eficiente en términos de generación, pero con menor creatividad en el texto generado.

### Métricas de Evaluación
- **Perplejidad:** Los modelos LSTM mostraron la perplejidad más baja, indicando textos más coherentes.
- **BLEU y ROUGE:** Los modelos generados por LSTM fueron los más cercanos a las referencias en términos de precisión de n-gramas.

## Documentación adicional

Para un análisis detallado de los resultados, las configuraciones de los modelos y las conclusiones, consulta el archivo **Memoria_Proyecto.pdf** incluido en este repositorio.  

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE). Puedes usar, modificar y distribuir el código siempre que incluyas atribución al autor original.  

---

¡Espero que este proyecto sea útil para tus investigaciones y aprendizaje en el campo de la Inteligencia Artificial!
