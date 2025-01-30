# Anlisis de Emisiones de CO Tendencias y Comparaciones Globales
Este código analiza las emisiones de CO₂ per cápita en diferentes países a lo largo del tiempo, utilizando visualizaciones interactivas y cálculos estadísticos para identificar tendencias y correlaciones.
Este análisis permite:
✅ Visualizar tendencias en emisiones de CO₂ en distintos países.
✅ Comparar la evolución de las emisiones por décadas.
✅ Identificar correlaciones entre países con niveles de emisiones similares.
✅ Explorar dinámicamente la relación entre dos países con gráficos interactivos.

Es útil para estudios medioambientales, formulación de políticas climáticas y concientización sobre el impacto de las emisiones.

# Paso a Paso del Código
## Importación de librerías
Se importan pandas (manipulación de datos), matplotlib y seaborn (visualización), numpy (cálculos matemáticos) e ipywidgets (interactividad).

## Carga y exploración de datos

Se carga el archivo CSV co-emissions-per-capita.csv.
Se visualizan las primeras filas del dataset.
Se filtran datos de 7 países específicos: EE.UU., China, India, Reino Unido, México, Perú y Colombia.
Se revisan los años disponibles y se identifican valores nulos.
## Visualización de emisiones a lo largo del tiempo

Se genera un gráfico de líneas para comparar la evolución de las emisiones de CO₂ per cápita de cada país.
## Análisis por décadas

Se agrupan los datos por décadas (desde 1950 en adelante).
Se genera un gráfico de barras con el promedio de emisiones de CO₂ por década.
## Comparación de décadas clave (1950 vs. 2020)

Se genera un boxplot y un violinplot para visualizar la distribución de emisiones en estos dos periodos.
## Análisis de distribución en todas las décadas

Se genera otro boxplot con la distribución de emisiones de CO₂ desde 1950 hasta la actualidad.
## Matriz de correlación

Se transforma la tabla para analizar la correlación entre países en cuanto a sus emisiones.
Se genera un heatmap con la matriz de correlación.
## Comparación entre países mediante gráficos interactivos

Se define una función para generar gráficos de dispersión entre dos países seleccionados.
Se incluye la opción de agregar una línea de tendencia para ver relaciones entre los datos.
Se implementa un widget interactivo para elegir los países y la opción de tendencia.
