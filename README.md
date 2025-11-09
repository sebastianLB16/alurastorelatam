Propósito del Análisis
El objetivo principal de este proyecto es realizar un análisis exploratorio y estratégico de los datos de ventas y rendimiento de cuatro tiendas virtuales (Tienda 1 a Tienda 4) que operan en la plataforma Alura Store
Ingresos Totales: Determinar la tienda con mayor impacto económico.
Rendimiento de Productos y Categorías: Identificar las categorías (e.g., Electrónicos, Alimentos y bebidas) y productos específicos (e.g., Computador portátil, Mesa de comedor) más y menos vendidos.
Experiencia del Cliente: Evaluar la satisfacción a través de las calificaciones promedio.
Eficiencia Logística: Analizar el costo de envío promedio para cada tienda.
El resultado final es una recomendación justificada sobre a qué tienda debe el Sr. Juan vender sus productos, basándose en la maximización del potencial de ventas y la eficiencia operativa
Estructura del Proyecto y Organización de Archivos
AluraStore/
├── alurastorelatam (2).ipynb
└── README.md
Ejemplos de Gráficos e Insights Obtenidos
El análisis se respalda en diversas visualizaciones, principalmente gráficos de barras, pie charts y gráficos de dispersión, para comparar el rendimiento de las cuatro tiendas.
Ejemplo de Gráfico: Comparación de Ingresos Totales
Gráfico Sugerido: Gráfico de barras que muestre el ingreso total (en miles de millones) por cada una de las cuatro tiendas.
Insight Clave: La Tienda 1 fue identificada como la líder en facturación, generando el mayor ingreso total ($1,150,880,400.0), lo que la posiciona como la opción más rentable.
Ejemplo de Gráfico: Distribución de Categorías de Productos (por Ingreso)
Gráfico Sugerido: Cuatro gráficos circulares (pie charts), uno por tienda, o un gráfico de barras apiladas, mostrando la proporción de ingresos generados por cada categoría de producto.
Insight Clave: Se observó una homogeneidad en la demanda en las cuatro tiendas. La categoría Electrónicos domina consistentemente los ingresos (aprox. 29%), mientras que Alimentos y bebidas es la categoría con menor contribución (aprox. 3.4%).
Ejemplo de Gráfico: Calificación Promedio por Tienda
Gráfico Sugerido: Gráfico de barras simple que muestre la calificación promedio de clientes (escala 1 a 5) para cada tienda.
Insight Clave: Todas las tiendas muestran una satisfacción del cliente casi idéntica, con una calificación promedio muy cercana a 3.01, lo que no sirve como factor de diferenciación para la recomendación final.
Instrucciones para Ejecutar el Noteboo
Para replicar el análisis y las visualizaciones generadas en el proyecto, siga los siguientes pasos:
Acceso a Google Colab: El archivo principal, alurastorelatam (2).ipynb, está diseñado para ejecutarse en Google Colab.
Carga del Notebook:
Abra Google Colab.
Haga clic en Archivo > Subir notebook.
Seleccione y cargue el archivo alurastorelatam (2).ipynb.
Ejecución de Celdas:
Asegúrese de que el entorno de ejecución esté en Python 3.
Ejecute cada celda del notebook en orden, desde la importación de librerías hasta la generación de gráficos y conclusiones.
Puede usar la opción Entorno de ejecución > Ejecutar todas para correr el análisis completo automáticamente.
Requisito: Se asume que el archivo de datos (.csv o similar) se carga o se accede a través de una URL/Google Drive configurada dentro de las primeras celdas del notebook.
