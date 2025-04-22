# Alura Store - Análisis de Datos

## Propósito del Análisis
El análisis realizado en el notebook `AluraStoreLatam.ipynb` tiene como objetivo explorar y comprender los datos de ventas de la tienda Alura Store. A través de este análisis, se busca identificar patrones de comportamiento de los clientes, productos más vendidos, tendencias de ventas y otros insights clave que puedan ayudar a decidir cual tienda vender. 

## Estructura del Proyecto
El proyecto está organizado de la siguiente manera:
- Importación de bibliotecas y diferentes fuentes de datos.
- Limpieza y preprocesamiento de los datos.
- Análisis de facturación.
- Ventas por categoría de producto.
- Calificación promediode cada tienda.
- Análisis de productos más y menos vendidos.
- Envío promedio por tienda

Todos los archivos de datos están en la carpeta `data`, y los gráficos generados se guardan en la carpeta `imagenes`.

## Ejemplos de Gráficos e Insights Obtenidos
A continuación, se presentan algunos ejemplos de gráficos generados y los insights obtenidos que fueron relevantes para tomar una decisión sobre cuál tienda vender:

1. **Gráfico de barras de ingresos de cada tienda**:
![alt text](<imagenes/Ingresos por tienda.png>)
    - Insight: La tienda con menor cantidad de ingresos es la tienda 4.

2. **Gráfico de calificación de clientes**:
![alt text](<imagenes\Calificacionpromedio.png>)
    - Insight: Las calificaciones de clientes tienden a ser similares entre las diferentes tiendas.

3. **Gráfico de cuotas por cliente**:
![alt text](<imagenes\CantidadDeCuotas.png>)
![alt text](<imagenes\Costos de envios.png>)
    - Insight: La cantidad de cuotas parece estable entre las diferentes tiendas, sin embargo la tienda 4 tiene la menor cantidad de cuotas. De igual forma la tienda 4 tiene la menor cantidad de costos de envíos.

## Instrucciones para Ejecutar el Notebook
Para ejecutar el notebook `AluraStoreLatam.ipynb`, sigue los pasos a continuación:

1. Asegúrate de tener instalado Python 3.8 o superior y las siguientes bibliotecas:
    - pandas
    - matplotlib
    - jupyter
    - numpy

2. Clona el repositorio o descarga los archivos del proyecto.

3. Abre una terminal y navega hasta la carpeta del proyecto.

4. Ejecuta el siguiente comando para iniciar Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

5. En el navegador, abre el archivo `AluraStoreLatam.ipynb`.

6. Ejecuta las celdas del notebook en orden para reproducir el análisis y los gráficos.

! Difruta el análisis y los insights obtenidos. Si tienes alguna pregunta o sugerencia, no dudes en contactarme.