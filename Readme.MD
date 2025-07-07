# Análisis de Datos Públicos de Colombia 🇨🇴

Este proyecto tiene como objetivo la exploración, procesamiento y análisis de dos conjuntos de datos públicos de Colombia, con el fin de generar visualizaciones, estadísticas descriptivas y modelos que aporten a la comprensión de la contratación pública y la calidad educativa. El procesamiento se realizará en *Databricks* para aprovechar su potencia de análisis distribuido.

## 📦 Conjuntos de Datos Utilizados

1. *SECOP (Sistema Electrónico para la Contratación Pública)*  
   - 📄 [rpmr-utcd.csv](https://www.datos.gov.co/resource/rpmr-utcd.csv)  
   - Contiene información relacionada con procesos de contratación pública en Colombia.

2. *Resultados Saber 11 - Ministerio de Educación Nacional (MEN)*  
   - 📄 [nudc-7mev.csv](https://www.datos.gov.co/resource/nudc-7mev.csv)  
   - Incluye datos sobre los resultados de las pruebas de Estado Saber 11.

## ⚙ Procesamiento y Análisis

Los principales pasos incluyen:
- Descarga de los datasets directamente desde los portales de datos abiertos.
- Limpieza de datos: manejo de valores nulos, formatos de fecha, y normalización de nombres.
- Enriquecimiento y cruce de datos donde sea posible.
- Análisis exploratorio con herramientas como Pandas y Spark.
- Carga y almacenamiento en un entorno *Databricks* para visualización avanzada y procesamiento a gran escala.

## 🧰 Herramientas Utilizadas

- 🐍 Python 3.11+
- 📊 Pandas y PySpark
- 🔥 Databricks Community Edition
- 📈 Visualización con matplotlib y seaborn

## 🚀 Cómo Empezar

1. Clona este repositorio.
2. Crea un cluster en Databricks o usa uno existente.
3. Sube el script de procesamiento y asegúrate de tener acceso a los datos en la nube.
4. Ejecuta los notebooks y explora los resultados.

## 📌 Notas

- Este proyecto tiene fines educativos y de análisis.  
- Los datasets son públicos y provienen de [datos.gov.co](https://www.datos.gov.co/).

---

🎯 Conectar los puntos entre educación y contratación pública puede revelar datos fascinantes sobre el desarrollo regional. Vamos a explorarlos.