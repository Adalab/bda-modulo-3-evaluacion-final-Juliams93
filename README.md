# Análisis de Datos de Vuelos

Este proyecto tiene como objetivo analizar un conjunto de datos de vuelos para obtener información valiosa sobre las reservas de vuelos, la distribución de clientes y otros aspectos relevantes. A continuación, se describen los pasos realizados y los resultados obtenidos.

## Fase 1: Exploración y Limpieza de Datos

### Lectura y Exploración General de los Datasets

1. **Carga de Datos**: Se cargaron dos datasets principales: `Customer Flight Activity` y `Customer Loyalty History`.
2. **Visualización Inicial**: Se visualizaron las primeras y últimas filas de los datasets para entender su estructura.
3. **Exploración de Datos**: Se revisaron los nombres de las columnas, el número de registros y columnas, y los tipos de datos.

### Estandarización de Nombres de Variables y Transformación de Tipos de Datos

1. **Estandarización**: Se estandarizaron los nombres de las columnas para facilitar el análisis.
2. **Transformación**: Se cambiaron los tipos de datos de ciertas columnas para asegurar la consistencia.
3. **Unión de Datasets**: Se unieron los dos datasets principales en uno solo basado en la columna `customer_id`.

### Limpieza de Datos

1. **Valores Nulos**: Se rellenaron los valores nulos en las columnas `salary`, `cancellation_year` y `cancellation_month`.
2. **Valores Duplicados**: Se eliminaron los valores duplicados.
3. **Valores Negativos**: Se revisaron y eliminaron los valores negativos.

## Fase 2: Visualización

### Análisis de la Cantidad de Vuelos Reservados

1. **Por Mes**: Se visualizó la cantidad de vuelos reservados por mes utilizando un gráfico de barras.
2. **Por Año**: Se visualizó la cantidad de vuelos reservados por año utilizando un gráfico de barras.

### Relación entre la Distancia de los Vuelos y los Puntos Acumulados

1. **Gráfico de Dispersión**: Se utilizó un gráfico de dispersión para visualizar la relación entre la distancia de los vuelos y los puntos acumulados por los clientes.

### Distribución de Clientes por Provincia o Estado

1. **Gráfico de Barras**: Se utilizó un gráfico de barras para visualizar la distribución de los clientes por provincia o estado.

### Comparación del Salario Promedio por Nivel Educativo

1. **Gráfico de Barras**: Se utilizó un gráfico de barras para comparar el salario promedio entre los diferentes niveles educativos de los clientes.

### Proporción de Clientes con Diferentes Tipos de Tarjetas de Fidelidad

1. **Gráfico de Pastel**: Se utilizó un gráfico de pastel para visualizar la proporción de clientes con diferentes tipos de tarjetas de fidelidad.

### Distribución de Clientes según su Estado Civil y Género

1. **Gráfico de Barras Agrupadas**: Se utilizó un gráfico de barras agrupadas para visualizar la distribución de los clientes según su estado civil y género.

## Fase 3: Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo

### Preparación de los Datos

1. **Filtrado de Datos**: Se filtraron las columnas relevantes para el análisis.
2. **Agrupación de Datos**: Se agruparon los datos por nivel educativo y se calcularon el promedio y la desviación estándar de vuelos reservados para cada grupo.

### Prueba Estadística

1. **Prueba de Normalidad**: Se realizó la prueba de Shapiro-Wilk para comprobar la normalidad de las muestras.
2. **Prueba de Kruskal-Wallis**: Se utilizó la prueba de Kruskal-Wallis para comparar los grupos debido a la falta de normalidad en los datos.

### Resultados

1. **Intervalo de Confianza**: Se calcularon los intervalos de confianza al 95% para el número promedio de vuelos reservados por nivel educativo.
2. **Conclusión**: Se encontró una diferencia significativa en el número promedio de vuelos reservados entre los diferentes niveles educativos.

## Conclusión

El análisis realizado proporciona información valiosa sobre las reservas de vuelos, la distribución de clientes y otros aspectos relevantes. Los resultados obtenidos pueden ser utilizados para mejorar las estrategias de marketing y fidelización de clientes.
