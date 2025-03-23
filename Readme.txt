Proyecto: Análisis de Ventas y Ratings de Juegos Android
Autores:

Daniel Felipe Duarte Quintero

Mónica Antolínez Becerra

Harvey Demian Bastidas Caicedo

Descripción
Este proyecto analiza datos de ventas y calificaciones de juegos de Android, generando visualizaciones interactivas con Google Charts. Se procesaron los datos con Python (Pandas y NumPy) y se convirtieron a formato JSON para ser utilizados en la visualización web.

Pasos realizados
1. Procesamiento de Datos con Python
Se cargó el archivo de datos en formato Excel (android_games_sales.xlsx).

Se eliminaron espacios en los nombres de las columnas para evitar errores.

Se convirtieron las columnas numéricas a tipo int64, manejando valores nulos (NaN) correctamente.

Se generaron valores aleatorios sin repetir para las columnas:

US_Sales, EU_Sales, Global_Sales, JP_Sales (ventas en diferentes regiones).

User_Rating y Critic_Rating (calificaciones de usuarios y críticos).

Se guardó el archivo modificado en formato JSON (android_games_sales.json).

2. Creación de la Visualización Web
Se desarrolló un archivo HTML (index.html) que utiliza Google Charts para mostrar gráficos interactivos.

Se incluyó un script en JavaScript que:

Carga el archivo JSON con fetch().

Procesa los datos y genera visualizaciones con gráficos de barras, dispersión y pastel.

Ordena y selecciona los 10 mejores juegos según diferentes métricas.

3. Subida del Proyecto a GitHub
Se creó un repositorio en GitHub.

Se subieron los archivos index.html y android_games_sales.json.

Se verificó que los archivos estén correctamente disponibles en el repositorio.

Archivos en el Proyecto
index.html → Página web con las visualizaciones de datos.

android_games_sales.json → Archivo de datos en formato JSON.

Readme.txt → Este archivo con la documentación del proyecto.

Instrucciones para Ejecutar
Clonar el repositorio o descargar los archivos.

Abrir index.html en un navegador web.

Asegurar que el archivo android_games_sales.json esté en la misma carpeta que index.html.

Tecnologías Utilizadas
Python (Pandas, NumPy) para procesamiento de datos.

Google Charts para visualizaciones.

HTML, CSS, JavaScript para la interfaz web.

GitHub para almacenamiento y control de versiones.