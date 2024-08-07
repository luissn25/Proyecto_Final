# Proyecto Final

## Descripción del Proyecto
Este proyecto aborda la normalización de datasets y el uso de modelos de redes neuronales para evaluar y mejorar la calidad de los datos. Se revisan trabajos previos, se describen métodos aplicados, se presentan los resultados obtenidos y se discuten los conocimientos descubiertos. Los hallazgos subrayan la importancia de la normalización para el rendimiento de los modelos predictivos, ofreciendo una guía práctica y teórica sobre las mejores prácticas en este campo.

## Estructura del Proyecto
- `proyecto_primer_avance.ipynb`: Primer avance del proyecto, incluye los primeros análisis y resultados iniciales.
- `proyecto_segundo_avance.ipynb`: Segundo avance del proyecto, con análisis más detallados y resultados adicionales.
- `normalizar_datasets.ipynb`: Script para la normalización de datasets, asegurando la consistencia de los datos.
- `convertir_ris_csv.ipynb`: Script para convertir archivos en formato RIS a CSV, facilitando su análisis.
- `dataset_trabajado.csv`: Dataset trabajado, resultado de la normalización y unificación de datos.
- `dataset_unificado.csv`: Dataset unificado, que combina diferentes fuentes de datos en un único archivo.
- `sciencedirect_carbon_footprint.csv`: Dataset obtenido de ScienceDirect sobre la huella de carbono.
- `sciencedirect_carbon_footprint_01.csv`: Dataset adicional de ScienceDirect sobre la huella de carbono.
- `sciencedirect_carbon_footprint_02.csv`: Segundo dataset adicional de ScienceDirect sobre la huella de carbono.
- `sciencedirect_carbon_footprint_03.csv`: Tercer dataset adicional de ScienceDirect sobre la huella de carbono.
- `sciencedirect_carbon_footprint_03.ris`: Archivo RIS correspondiente al dataset sciencedirect_carbon_footprint_03.csv.
- `sciencedirect_carbon_footprint_02.ris`: Archivo RIS correspondiente al dataset sciencedirect_carbon_footprint_02.csv.
- `sciencedirect_carbon_footprint_01.ris`: Archivo RIS correspondiente al dataset sciencedirect_carbon_footprint_01.csv.
- `scopus_estimation_carbon_footprint.csv`: Dataset obtenido de Scopus sobre la estimación de la huella de carbono.
- `english.txt`: Archivo de texto con palabras en inglés posiblemente usado para preprocesamiento de texto o análisis de contenido.

## Descripción del Dataset
### sciencedirect_carbon_footprint.csv
- **Fuente**: ScienceDirect
- **Criterios de búsqueda**: Huella de carbono, impacto ambiental

### sciencedirect_carbon_footprint_01.csv, sciencedirect_carbon_footprint_02.csv, sciencedirect_carbon_footprint_03.csv
- **Fuente**: ScienceDirect
- **Número de artículos**: [Especificar el número de artículos para cada archivo]
- **Criterios de búsqueda**: Huella de carbono, impacto ambiental

### scopus_estimation_carbon_footprint.csv
- **Fuente**: Scopus
- **Criterios de búsqueda**: Estimación de huella de carbono

## Pre-procesamiento
- Limpieza de datos: Eliminación de duplicados, tratamiento de valores faltantes.
- Normalización: Estandarización de formatos y unidades.
- Conversión: Transformación de archivos RIS a CSV para facilitar el análisis.

  

## Visualizaciones (Análisis Exploratorio)
Descripción de las visualizaciones y análisis exploratorios realizados.

![Visualización 1] (https://github.com/user-attachments/assets/cb053804-56ed-4cf5-ad79-96b46797c82d)

![Visualización 2] (https://github.com/user-attachments/assets/24160f08-e034-4ee3-a9ca-45719790da98)


## Modelo No Supervisado
Clasificación de artículos relevantes a conceptos, palabras clave, aspectos importantes, métodos más usados, métricas, entidades, beneficios, etc.

## Evaluación
Descripción de la evaluación del modelo y los resultados obtenidos.

## Datos Relevantes al Proyecto
Palabras y tópicos importantes identificados en el proyecto.

## Información y Conocimiento Descubierto
Resumen de la información y conocimiento descubierto a partir del análisis.

## Instalación
Para configurar el entorno y ejecutar los scripts, sigue estos pasos:

1. Clona el repositorio:
   ```bash
   git clone [URL del repositorio]
2.  Navega al directorio del proyecto:
    ```bash
    cd [nombre del directorio]
    
3. Instala las dependencias necesarias:    
    ```bash
    pip install -r requirements.txt
