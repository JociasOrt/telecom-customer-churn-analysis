# Análisis de Evasión de Clientes (Churn) en Telecomunicaciones 📊

## 📌 Propósito del Proyecto
Este proyecto de Data Science tiene como objetivo analizar los datos de clientes de una empresa de telecomunicaciones para descubrir los motivos principales por los que cancelan su servicio (fenómeno conocido como "Churn" o evasión). A través de la limpieza de datos y el análisis visual, buscamos identificar patrones de comportamiento para ofrecer recomendaciones estratégicas que ayuden a retener a los usuarios.

## 🛠️ Estructura y Proceso
El notebook principal documenta el proceso completo de extremo a extremo:

1. **Extracción y Limpieza (ETL):**  Consumo de datos crudos en formato JSON.
   * Desempaquetado de columnas anidadas para estructurar la información.
   * Estandarización de datos categóricos (conversión de "Yes/No" a "1/0") y corrección de formatos numéricos para habilitar el análisis matemático.
2. **Creación de Métricas:**  Cálculo de la variable `Cuentas_Diarias` para analizar el impacto del costo diario en la retención.
3. **Análisis Exploratorio Visual (EDA):**  Uso de gráficos de barras, boxplots (diagramas de caja) y mapas de calor (heatmaps) para cruzar variables demográficas y financieras contra la tasa de abandono.

## 🚀 Principales Descubrimientos
* **El momento crítico:** La mayor cantidad de cancelaciones ocurre durante los primeros meses de contratación.
* **El riesgo del contrato mensual:** Los usuarios que pagan "mes a mes" sin un contrato a largo plazo son los más propensos a irse.
* **Sensibilidad al precio:** Sorprendentemente, los clientes que pagan mensualidades más altas son los que más cancelan el servicio.

## 💻 Tecnologías y Dependencias
Para ejecutar este proyecto, el entorno requiere las siguientes librerías de Python:
* `pandas` (Manipulación y limpieza de datos)
* `matplotlib` (Creación de gráficos base)
* `seaborn` (Visualización estadística avanzada)

## ⚙️ Instrucciones de Uso / Cómo ejecutar el proyecto

Si deseas clonar este repositorio y ejecutar el análisis localmente, sigue estos pasos:

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone [https://github.com/JociasOrt/telecom-customer-churn-analysis.git](https://github.com/JociasOrt/telecom-customer-churn-analysis.git)
2. Asegúrate de tener instalado Python 3.x y un entorno como Jupyter Notebook o Google Colab.
3. Instala las dependencias necesarias ejecutando:
`pip install pandas matplotlib seaborn`
4. Abre el archivo principal del notebook (`.ipynb`) y ejecuta las celdas en orden desde el principio. Los datos se cargarán y limpiarán automáticamente.
