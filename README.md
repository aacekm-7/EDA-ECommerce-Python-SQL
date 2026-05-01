# EDA-ECommerce-Python-SQL

## 📦 E-Commerce Sales Analysis

Análisis exploratorio de ventas de un e-commerce indio durante el período 2018–2019, enfocado en rentabilidad por producto, comportamiento de clientes y distribución geográfica de ventas.

#

## 🎯 Objetivo

Identificar oportunidades de negocio a través del análisis de ventas, productos, clientes y geografía, respondiendo preguntas clave como:

- ¿Qué categorías y sub-categorías son rentables y cuáles operan con pérdida?
- ¿Qué clientes generan más ingresos y cómo retenerlos?
- ¿Cómo evolucionaron las ventas mes a mes entre 2018 y 2019?
- ¿Qué estados y ciudades concentran más ventas y cuáles generan pérdidas?

## 🗂️ Estructura del proyecto

Archivo	Descripción
* `ecommerce_analysis.ipynb`	Notebook principal con el análisis completo
* `List of Orders.csv`	Dataset: órdenes de compra (clientes, fechas, ubicación)
* `Order Details.csv`	Dataset: detalle de productos por orden (ventas, profit, categorías)
* `README.md`	Documentación del proyecto
---
## 📊 Dataset
- Fuente: Kaggle 
- [Dataset](https://www.kaggle.com/datasets/benroshan/ecommerce-data)

## 🛠️ Herramientas

Herramienta	Uso
* `Python 3`	Lenguaje principal
* `Pandas`	Manipulación y limpieza de datos
* `DuckDB`	Consultas SQL sobre DataFrames
* `Seaborn / Matplotlib`	Visualizaciones
  
## 🔍 Contenido del análisis

- EDA — Validación de nulos, duplicados, tipos de datos y estadísticos descriptivos
- Limpieza — Estandarización de columnas, conversión de fechas, tratamiento de outliers con método IQR
- Análisis de Ventas — Correlaciones y tendencia mensual 2018 vs 2019
- Análisis de Productos — Ganancia por categoría, margen por sub-categoría, sub-categorías con pérdida
- Análisis de Clientes — Top 10 clientes por ingreso con recomendaciones de retención
- Análisis Geográfico — Ventas y profit por estado, estados críticos, ciudades con más órdenes

📈 Hallazgos principales

- 1	Clothing genera el 84% del profit total	Categoría clave — priorizar inventario y marketing
- 2	Saree: alto volumen con profit negativo (-$1,190)	Revisar estructura de costos o precio de venta
- 3	Electronics y Chairs en zona de pérdida media	Rediseño de estrategia comercial
- 4	T-Shirt tiene el mejor margen del portafolio	Potenciar ventas cruzadas
- 5	2019 supera a 2018 en pico de ventas (~44%)	Tendencia de crecimiento positiva
- 6	Correlación ventas-cantidad débil (0.18)	El precio unitario importa más que el volumen
- 7	Tamil Nadu: mayor pérdida geográfica	Auditar operaciones y precios en esa región
- 8	Madhya Pradesh lidera en ventas	Reforzar logística y disponibilidad

💡 Recomendaciones

- Aplicar descuentos estratégicos al Top 10 clientes en sub-categorías con margen negativo
- Auditar costos de Saree — alto volumen con pérdida sostenida
- Investigar causas de pérdida en Tamil Nadu — puede ser logística, descuentos excesivos o precios mal calibrados
- Reforzar operaciones en Madhya Pradesh — estado con mayor volumen de ventas
- Preparar inventario para los meses pico históricos: noviembre (2018) y marzo (2019)

