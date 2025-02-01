# Clasificación de Imágenes: Perros y Gatos  

Este repositorio contiene el proyecto **Clasificación de Imágenes: Perros y Gatos**, desarrollado como parte del curso _"Inteligencia Artificial"_ en el grado de Ingeniería de Software. El objetivo principal fue entrenar y evaluar modelos de redes neuronales convolucionales (CNN) y Transfer Learning para la clasificación de imágenes de perros y gatos.

[Ir al proyecto en GitHub](https://github.com/ch0rtas/IS-Inteligencia_Artificial/tree/main/Clasificación_Imagenes_Perros_y_Gatos)  

## Descripción del proyecto  

Este proyecto implementa y compara varios modelos de clasificación de imágenes, utilizando tanto redes neuronales convolucionales (CNN) personalizadas como arquitecturas avanzadas de Transfer Learning. Todo el desarrollo se llevó a cabo en Google Colab con soporte de GPU para acelerar los tiempos de entrenamiento.  

### Características principales  
- **CNNs Personalizadas:** Experimentación con configuraciones de capas, tamaños de batch y épocas.  
- **Transfer Learning:** Adaptación de modelos preentrenados como ResNet50 y EfficientNet.  
- **Optimización y análisis:** Evaluación de la eficiencia y precisión de diferentes configuraciones.  
- **Gestión de recursos:** Ajustes para trabajar con las GPUs L4 y A100 en Google Colab.  

## Estructura del proyecto  

Este repositorio contiene los siguientes archivos clave:  
- `cnn_models.ipynb`: Notebook con la implementación de las CNN personalizadas.  
- `transfer_learning.ipynb`: Notebook con la implementación de Transfer Learning.  
- `Memoria_Proyecto.pdf`: Documentación completa del proyecto, incluyendo gráficos y análisis.  
- `kaggle.json`: Credenciales necesarias para acceder a datasets desde Kaggle.  

## Cómo usar este repositorio  

1. **Clona este repositorio:**  
   ```bash
   git clone https://github.com/ch0rtas/IS-Inteligencia_Artificial.git
   cd Clasificación_Imagenes_Perros_y_Gatos
Configura Kaggle API:

Descarga tu archivo kaggle.json desde Kaggle.
Sube el archivo a tu entorno de Google Colab.
Ejecuta los notebooks:

Abre cnn_models.ipynb o transfer_learning.ipynb en Google Colab.
Asegúrate de tener una GPU habilitada en el entorno de Colab para ejecutar el código eficientemente.
Analiza y modifica:

Experimenta con las configuraciones para observar el impacto en los resultados.
Resultados principales
Modelos CNN
cnn03: Mejor modelo CNN con un accuracy de 0.7678, entrenado con batch size reducido, kernel más grande y 100 épocas.
cnn02: Modelo menos eficiente con tiempo de entrenamiento excesivo y accuracy de 0.7154.
Transfer Learning
transferlearning03: Mejor modelo basado en EfficientNetB5, con un accuracy significativamente mejor que otros modelos preentrenados.
transferlearning02: Intento fallido con EfficientNetB7 debido a limitaciones de memoria, incluso con GPU A100.
Documentación adicional
Para un análisis detallado de los resultados, las configuraciones de los modelos y las conclusiones, consulta el archivo Memoria_Proyecto.pdf incluido en este repositorio.

Licencia
Este proyecto está licenciado bajo la MIT License. Puedes usar, modificar y distribuir el código siempre que incluyas atribución al autor original.

¡Espero que este proyecto sea útil para tus investigaciones y aprendizaje en el campo de la Inteligencia Artificial!
