# Copia-de-Entrega_Final.DataAnalytics_Alfonso.Ladoux.ipynb
"Transformación de datos crudos en insights de negocio: Limpieza de datasets reales, análisis de correlación y visualización de KPIs de ventas mediante Python."

# Proyecto de Análisis de Datos: Ventas y Marketing 📊
**Curso:** Data Analytics en Adult Tech
**Alumno:** Alfonso Ladoux (según el título del cuaderno)

## 📝 Descripción del Proyecto
Este proyecto consiste en un análisis exhaustivo de tres conjuntos de datos (Ventas, Clientes y Marketing) para identificar patrones de consumo y medir el impacto de las campañas publicitarias.

## 🛠️ Etapas del Análisis
1. **EDA (Análisis Exploratorio de Datos):** Identificación de nulos, duplicados y tipos de datos.
2. **Limpieza y Transformación:** - Normalización de precios (eliminación de caracteres especiales como `$`).
   - Conversión de tipos de datos (Strings a Datetime y Floats).
   - Tratamiento de valores faltantes y registros duplicados.
3. **Integración de Datos:** Cruce de tablas (*Merge*) para comparar ventas dentro y fuera de los períodos de campaña de marketing.
4. **Visualización:** Creación de histogramas, boxplots y gráficos de dispersión para entender la distribución de precios y la correlación entre variables.

## 💻 Tecnologías Utilizadas
* **Python**
* **Pandas:** Manipulación y limpieza de datos.
* **Seaborn & Matplotlib:** Visualización estadística de datos.
* **Google Colab:** Entorno de desarrollo.

## 📈 Conclusiones Clave
- Se detectó una correlación positiva de **0.77** entre la cantidad vendida y el valor total de la venta.
- Se segmentaron productos de alto rendimiento basados en el **percentil 75**.
- El análisis permitió diferenciar ingresos generados específicamente durante campañas de marketing por canal (TV, RRSS, Email).
