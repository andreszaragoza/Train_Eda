Autor: Andres Zaragoza

![](./image/dell-xps-14-vs-apple-macbook-pro-14-cnnu-cover.jpg)
# Análisis Exploratorio de Datos (EDA) - Laptops

- Este repositorio contiene un Análisis Exploratorio de Datos (EDA) sobre un dataset de laptops, con el objetivo de comprender mejor las características de los dispositivos y preparar los datos para un análisis posterior.

## 📌 **Contenido**

1. Exploración Inicial

2. Análisis Exploratorio

3. Transformaciones de Datos

4. Visualización de Datos

5. Imágenes Representativas

## 🔍 **Exploración Inicial**

- Se verifica que no hay valores nulos.

- Se confirma que no existen filas duplicadas.

## 📊 **Análisis Exploratorio**

### Variables categóricas

- Company (Marca del laptop)

- Product (Modelo del laptop)

- TypeName (Tipo de laptop)

- ScreenResolution (Resolución de pantalla)

- CPU_Company y CPU_Type (Marca y modelo del procesador)

- Memory (Tipo de almacenamiento)

- GPU_Company y GPU_Type (Marca y modelo de la tarjeta gráfica)

- OpSys (Sistema operativo)

### Variables numéricas

- Inches (Tamaño de la pantalla en pulgadas)

- CPU_Frequency (GHz) (Frecuencia del procesador en GHz)

- RAM (GB) (Cantidad de memoria RAM en GB)

- Weight (kg) (Peso del dispositivo en kg)

- Price (Euro) (Precio en euros)

## 🛠  **Transformaciones de Datos**

- Separación de la columna ScreenResolution para extraer información relevante.

- Extracción del fabricante y modelo de CPU y GPU.

- Conversión de unidades en variables como RAM y almacenamiento.

- Extracción de información de la columna OpSys para distinguir el sistema operativo principal y su versión.

- Cálculo de la media del precio para su posterior análisis.

## 📈 **Visualización de Datos**

- Se incluyen diversas gráficas para visualizar los patrones en los datos:

- Distribución de precios de los laptops

- Relación entre peso y precio

- Diferencia de precios por marca y modelo

- Distribución de tipos de almacenamiento

## 📂 Archivos en el repositorio

1. Analisis.ipynb: Notebook con el Análisis Exploratorio de Datos.

2. train_limpio.csv: Dataset limpio luego de las transformaciones.

3. README.md: Este archivo con la documentación del proyecto.

### 🚀 Uso

- Para ejecutar el análisis, abre el notebook en Jupyter y ejecuta las celdas.

- jupyter notebook Analisis.ipynb
## 📌 Notas

- Este análisis se centra en la exploración y limpieza de datos para un estudio más profundo en futuras fases.

- Las visualizaciones pueden variar dependiendo de los datos de entrada.