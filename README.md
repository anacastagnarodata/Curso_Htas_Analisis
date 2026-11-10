# Análisis exploratorio de datos de fermentación etanólica industrial

**Trabajo final – Curso Herramientas básicas para el análisis de datos | UTN BA**

## Descripción del proyecto

Este proyecto aborda el análisis exploratorio de datos de fermentación etanólica industrial a partir de un dataset sintético, diseñado para representar diferentes condiciones operativas y microbiológicas del proceso de producción de bioetanol a partir de caña de azúcar.

El trabajo comprende la preparación y limpieza de datos, el análisis estadístico y la elaboración de visualizaciones que permiten explorar relaciones entre variables como temperatura, concentración inicial de azúcares, contaminación bacteriana, viabilidad de levaduras y rendimiento fermentativo.

## Objetivo

Aplicar herramientas de análisis de datos para identificar patrones, distribuciones y asociaciones entre variables relevantes del proceso fermentativo, utilizando Python para la preparación y exploración de los datos y Power BI para su visualización interactiva.

## Dataset

Se utilizó un conjunto de datos sintético generado con asistencia de inteligencia artificial para fines didácticos.

El dataset original contenía 6.000 registros e incluía deliberadamente valores faltantes, duplicados e inconsistencias para ejercitar procedimientos de limpieza y transformación.

Luego del procesamiento, se obtuvo un conjunto de 5.792 registros para el análisis exploratorio.

## Herramientas utilizadas

- **Google Colab y Python:** preparación, limpieza y análisis exploratorio.
- **pandas y NumPy:** manipulación de datos y análisis estadístico.
- **Matplotlib, Seaborn y Plotly:** visualización de distribuciones, tendencias y correlaciones.
- **Power BI Desktop:** elaboración de dashboards interactivos.
- **ReportLab:** generación automatizada del reporte ejecutivo en PDF.
- **GitHub:** organización y documentación del proyecto.

## Organización del repositorio

| Carpeta | Contenido |
|---|---|
| `data/` | Datasets utilizados en el proyecto |
| `notebooks/` | Notebook de Google Colab con el procesamiento y análisis exploratorio |
| `dashboard/` | Tableros de análisis realizados en Power BI |
| `conclusiones/` | Conclusiones finales y reporte ejecutivo del análisis |

## Dashboards desarrollados

**1. Contaminación bacteriana y estado fisiológico de las levaduras**

Permite explorar la relación entre contaminación bacteriana y viabilidad celular, comparar tratamientos de control microbiológico y analizar diferencias entre destilerías y sustratos.

**2. Factores asociados al rendimiento fermentativo**

Permite analizar la relación entre temperatura y rendimiento, concentración inicial de azúcares y producción de etanol, así como la distribución y evolución temporal del rendimiento fermentativo.

## Resultados y conclusiones

El análisis permitió identificar asociaciones entre distintas variables del proceso, incluyendo correlaciones entre contaminación y viabilidad, °Brix inicial y etanol final, y viabilidad y rendimiento fermentativo.

Los resultados principales, sus interpretaciones y las limitaciones del estudio se desarrollan en los documentos incluidos en la carpeta `conclusiones/`.

## Alcance del trabajo

El proyecto se desarrolló utilizando datos sintéticos con fines exclusivamente didácticos. Por lo tanto, los resultados deben interpretarse como parte de un ejercicio de análisis exploratorio y no como evidencia experimental aplicable directamente a procesos industriales reales.
