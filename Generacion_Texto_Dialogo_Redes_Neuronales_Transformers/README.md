# Generación de Texto y Diálogo con Modelos de Redes Neuronales y Transformers

Este repositorio contiene el proyecto **Generación de Texto y Diálogo con Modelos de Redes Neuronales y Transformers**, desarrollado como parte del curso _"Inteligencia Artificial"_ en el grado de Ingeniería de Software. El objetivo principal fue entrenar y evaluar diferentes modelos de redes neuronales (RNN, LSTM, GRU y Transformers) para la generación de texto y simulación de diálogos entre parlamentarios.

[Ir al proyecto en GitHub](https://github.com/ch0rtas/IS-Inteligencia_Artificial/tree/main/Generacion_Texto_Dialogo_Redes_Neuronales_Transformers)

## Estructura del proyecto

Este repositorio se organiza en las siguientes carpetas y archivos:

### **benchmark/**
Contiene los archivos de evaluación de los modelos entrenados para cada parlamentario.

- `benchmarkAbascal/`: Evaluación del modelo entrenado para el parlamentario Abascal.
- `benchmarkCasado/`: Evaluación del modelo entrenado para el parlamentario Casado.
- `benchmarkSanchez/`: Evaluación del modelo entrenado para el parlamentario Sánchez.

### **parlamentarios/**
Contiene los archivos de datos correspondientes a los discursos de cada parlamentario.

- `abascal/`: Carpeta con los archivos de discursos de Abascal (abascal01 hasta abascal10).
- `casado/`: Carpeta con los archivos de discursos de Casado (casado01 hasta casado12).
- `sanchez/`: Carpeta con los archivos de discursos de Sánchez (sanchez01 hasta sanchez10).

### **Archivos principales**

- **INAR #02 - Manuel Martínez.pdf**: Documento con el análisis completo del proyecto, incluyendo los resultados y conclusiones.
- **LICENSE**: Archivo con la licencia del proyecto (MIT License).
- **README.md**: Este archivo con la descripción y detalles del proyecto.
- **dialogoCongreso.ipynb**: Notebook donde los modelos generados interactúan en un diálogo simulado entre los tres parlamentarios.

## Descripción del proyecto

El proyecto tiene como objetivo entrenar y evaluar diferentes modelos de redes neuronales (RNN, LSTM, GRU y Transformers) para la **generación de texto coherente** basado en discursos parlamentarios. Además, se implementa un sistema para **simular un diálogo** entre tres parlamentarios: Abascal, Casado y Sánchez.

### Características principales

- **Modelos RNN, LSTM, y GRU:** Comparación de rendimiento entre diferentes arquitecturas de redes neuronales.
- **Transformers:** Exploración de la aplicación de Transformers para la generación de texto, aunque con limitaciones.
- **Evaluación de calidad:** Uso de métricas como perplejidad, BLEU y ROUGE para evaluar la calidad del texto generado.
- **Generación de Diálogo:** Simulación de un diálogo entre los tres parlamentarios en base a los modelos entrenados.
- **Optimización de modelos:** Ajustes en la arquitectura y parámetros de los modelos para mejorar la coherencia y relevancia del texto generado.

## Cómo usar este repositorio

1. **Clona este repositorio:**  
   ```bash
   git clone https://github.com/ch0rtas/IS-Inteligencia_Artificial.git
   cd Generacion_Texto_Dialogo_Redes_Neuronales_Transformers
   ```

2. **Ejecuta los notebooks:**  
   - Abre `*NAME+VERSION*.ipynb` para entrenar y evaluar los modelos de generación de texto.  
   - Abre `benchmarkAbascal.ipynb`, `benchmarkCasado.ipynb` o `benchmarkSanchez.ipynb` para evaluar el desempeño de cada modelo.  
   - Abre `dialogoCongreso.ipynb` para ver el diálogo simulado entre los parlamentarios.

3. **Carga los modelos entrenados:**  
   - Los modelos entrenados se encuentran en la carpeta `parlamentarios/`. Carga el modelo correspondiente en cada notebook para realizar las evaluaciones o el diálogo.

4. **Analiza y modifica:**  
   - Experimenta con las configuraciones para mejorar la calidad del texto generado o personalizar el diálogo.

## Resultados principales

### Modelos Generados
- **Abascal10:** Mejor modelo para generar texto coherente con un accuracy aceptable.  
- **Casado12:** Modelo con texto generado ligeramente menos coherente, pero con tiempos de entrenamiento más rápidos.  
- **Sanchez09:** Modelo más eficiente en términos de generación, pero con menor creatividad en el texto generado.

### Métricas de Evaluación
- **Perplejidad:** Los modelos LSTM mostraron la perplejidad más baja, indicando textos más coherentes.
- **BLEU y ROUGE:** Los modelos generados por LSTM fueron los más cercanos a las referencias en términos de precisión de n-gramas.

## Documentación adicional

Para un análisis detallado de los resultados, las configuraciones de los modelos y las conclusiones, consulta el archivo **INAR #02 - Manuel Martínez.pdf** incluido en este repositorio.  

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE). Puedes usar, modificar y distribuir el código siempre que incluyas atribución al autor original.  

---

¡Espero que este proyecto sea útil para tus investigaciones y aprendizaje en el campo de la Inteligencia Artificial!
