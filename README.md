# Análisis de la Evolución de COVID-19 en la Ciudad de México

Este proyecto analiza la evolución de los casos de COVID-19 en la Ciudad de México. Utiliza datos oficiales para explorar la dinámica de la pandemia mediante gráficos de casos diarios y acumulados, aplica suavizado de datos para mejor visualización y ajusta un modelo logístico para predecir la progresión de la pandemia.

## Requisitos

Para ejecutar este notebook, necesitas:

- Python 3.x
- Pandas
- Matplotlib
- NumPy
- SciPy

Puedes instalar todas las dependencias necesarias ejecutando:

```bash
pip install pandas matplotlib numpy scipy
```
## Datos

Los datos utilizados en este análisis provienen del CONACYT y pueden ser descargados directamente desde su página oficial. Este proyecto asume que se ha descargado un archivo llamado 'Casos_Diarios_Estado_Nacional_Confirmados_20230625.csv', el cual contiene los casos diarios y defunciones por COVID-19 en la Ciudad de México.

## Ejecución

El proyecto está estructurado como un Jupyter Notebook y puede ser ejecutado en entornos como Jupyter Lab, Jupyter Notebook o Google Colab. Para comenzar la ejecución, simplemente abre el archivo proyecto3.ipynb en tu entorno de Jupyter y ejecuta las celdas secuencialmente.

## Contenido
El notebook incluye las siguientes secciones:

- **Carga de Datos**: Carga los datos de casos diarios y defunciones de COVID-19 en la Ciudad de México.

- **Preparación de Datos**: Filtra los datos para la Ciudad de México, calcula los casos diarios y acumulados, y aplica suavizado de datos para una mejor visualización.

- **Visualización de Datos**: Genera gráficos de barras para casos diarios y gráficos de líneas para casos acumulados y suavizados.

- **Análisis de Tendencias**: Define y aplica el modelo logístico de Verhulst para ajustar los datos acumulados y evaluar la dinámica de la pandemia.

- **Optimización de Parámetros**: Utiliza el método de Nelder-Mead para encontrar los parámetros óptimos del modelo logístico y predecir la progresión de la pandemia.

## Resultados
Los resultados incluyen gráficos interactivos que muestran la evolución de los casos de COVID-19 en la Ciudad de México, junto con un ajuste del modelo logístico que permite evaluar la efectividad de las medidas sanitarias implementadas y predecir la futura progresión de la pandemia.

## Contacto
Para cualquier pregunta o comentario sobre este proyecto, por favor, no dudes en contactar al autor.

