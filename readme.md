# Hector Sosa / 23-1243

# Ciencia de Datos

**Dataset de películas:** [Netflix Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## Informe de Proyecto

### 1. Metodología

**Herramientas y Técnicas Utilizadas:**

- **Herramientas:**

  - Python
  - Bibliotecas: pandas, numpy, matplotlib

- **Técnicas:**
  - **Carga de Datos:** Utilización de `pd.read_csv` para importar el conjunto de datos de películas.
  - **Limpieza de Datos:**
    - Identificación y eliminación de valores nulos.
    - Relleno de valores nulos con 'Unknown' en columnas específicas.
    - Eliminación de duplicados y valores 'Unknown'.
  - **Filtrado de Datos:**
    - Selección de registros basados en el tipo de contenido (solo películas).
    - Filtrado de registros por calificación (TV-MA y R) y por año de lanzamiento (2002-2017).
  - **Análisis Estadístico:** Descripción estadística y distribución de registros.
  - **Visualización:** Creación de un gráfico de barras para mostrar la distribución de películas por año de lanzamiento.

**Abordaje de Preguntas de Investigación:**

- **Pregunta Principal:** ¿Cómo se distribuyen las películas por año de lanzamiento en los primeros 100 registros de películas con calificación TV-MA y R?
- **Decisiones Tomadas:**
  - Exclusión de datos irrelevantes y valores desconocidos.
  - Enfoque en películas con calificación específica y en un rango de años determinado.
  - Limitación a las primeras 100 entradas para un análisis detallado.

### 2. Resultados

**Estadísticas Generales:**

- **Descripción Estadística:** Se proporcionaron estadísticas descriptivas de las películas, incluyendo medidas de tendencia central y dispersión.

**Distribución de Calificaciones:**

- **Conteo de Calificaciones:** Se identificó la cantidad de películas para cada calificación específica.

**Distribución por Año de Lanzamiento:**

- **Gráfico de Barras:** Se presenta un gráfico de barras que ilustra la distribución de películas por año de lanzamiento entre 2002 y 2017, limitando el análisis a las primeras 100 películas con calificaciones TV-MA y R.

- **Gráfico:**
  ![image.png](attachment:image.png)

### 3. Conclusiones

**Resumen de Hallazgos:**

- La mayoría de las películas con calificaciones TV-MA y R analizadas se concentran en ciertos años específicos, lo cual puede indicar tendencias en la producción de contenido para adultos.
- La distribución de películas varía significativamente entre los años, con ciertos años mostrando una mayor concentración de películas en estas categorías.

**Respuestas a Preguntas de Investigación:**

- **Distribución por Año:** El gráfico muestra claramente los años con más películas clasificadas como TV-MA y R entre 2002 y 2017.

### 4. Recomendaciones

**Acciones Propuestas:**

- **Para Productores de Contenido:** Considerar la tendencia en años específicos para planificar lanzamientos futuros o analizar la demanda en diferentes periodos.
- **Para Plataforma de Streaming:** Ajustar las recomendaciones y promociones basadas en la popularidad de ciertos años y calificaciones.

**Siguientes Pasos:**

- Realizar un análisis más detallado considerando otros aspectos como la duración de las películas y el país de origen para obtener una visión más completa.
