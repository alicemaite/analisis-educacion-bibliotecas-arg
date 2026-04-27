# Análisis de Distribución: Establecimientos Educativos y Bibliotecas Populares en Argentina

**Materia:** Laboratorio de Datos (FCEyN - Universidad de Buenos Aires)  
**Integrantes:** Maite Alice, Abril Echarri y Facundo Miguel.

## 📌 Descripción del Proyecto
Este repositorio presenta una solución técnica basada en datos públicos para investigar si existe algún patrón o relación entre la infraestructura educativa (EE) y cultural (BP) en las diferentes provincias y departamentos de Argentina. La propuesta abarca todo el flujo de trabajo: desde la recolección, revisión y modelado de datos, hasta el análisis visual y mediante consultas SQL.

## 🎯 Objetivos del Proyecto
* Integrar datos educativos, culturales y poblacionales desde fuentes públicas oficiales.
* Identificar y cuantificar problemas de calidad de datos mediante métricas **GQM (Goal-Question-Metric)**.
* Diseñar un modelo conceptual (DER) y normalizar las tablas generadas.
* Generar reportes estructurados con SQL y comunicar hallazgos mediante visualizaciones efectivas.

## 🗂️ Estructura del Repositorio
* `data/raw/`: Datasets originales en su formato de descarga.
* `data/processed/`: Tablas limpias y normalizadas tras la aplicación del modelo relacional.
* `notebooks/`: Código fuente en Jupyter Notebook interactivo (`analisis_tp.ipynb`) y script original (`archivo.py`).
* `docs/`: Informe técnico final del trabajo en formato PDF.

## 🛠️ Herramientas y Tecnologías
* **Python:** `pandas` para manipulación y limpieza de datos.
* **SQL:** Consultas embebidas con `duckdb` para análisis estructurado de las consignas.
* **Visualización:** `matplotlib` para la generación de gráficos.

## 📊 Visualizaciones Incluidas
1. Cantidad de Bibliotecas Populares por provincia (Gráfico de barras).
2. Relación entre Establecimientos Educativos y población segmentado por nivel (Gráfico de dispersión).
3. Distribución de EE por departamento agrupado por provincia (Boxplots).
4. Correlación entre la cantidad de BP y EE cada mil habitantes.

## 🔗 Fuentes de Datos Utilizadas
Todos los datasets originales se encuentran alojados en la carpeta `data/raw/`. Las fuentes oficiales son:
* **Establecimientos Educativos (2022):** [Padrón Oficial - Ministerio de Educación](https://www.argentina.gob.ar/educacion/evaluacion-e-informacion-educativa/padron-oficial-de-establecimientos-educativos)
* **Bibliotecas Populares:** [Mapa Cultural - Datos Argentina](https://datos.gob.ar/dataset/cultura-mapa-cultural-espacios-culturales/archivo/cultura_01c6c048-dbeb-44e0-8efa-6944f73715d7)
* **Población por Departamento (Censo 2022):** [Portal INDEC](https://www.indec.gob.ar/indec/web/Nivel4-Tema-2-41-165)