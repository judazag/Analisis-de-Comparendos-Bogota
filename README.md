# 🚦 Análisis de Movilidad y Big Data: Comparendos Bogotá 2019

Este repositorio contiene un análisis exhaustivo de más de **400,000 registros** de infracciones de tránsito en Bogotá D.C. utilizando **Apache Spark**. El proyecto abarca desde la definición de esquemas de datos masivos hasta la extracción de insights estratégicos sobre el comportamiento vial en la capital.

## 🎯 Objetivo
Transformar datos crudos de movilidad en información accionable, identificando patrones temporales y geográficos de las infracciones para entender mejor la dinámica del tráfico y la seguridad vial.

## 🛠️ Stack Tecnológico
- **Procesamiento:** Apache Spark (PySpark) ⚡
- **Análisis de Datos:** Pandas, NumPy
- **Visualización:** Matplotlib, Seaborn
- **Entorno:** Google Colab / Distributed Computing

## 📊 El Dataset
Se utilizó el conjunto de datos oficial de la **Secretaría Distrital de Movilidad**.
- **Registros:** 402,500 entradas.
- **Variables clave:** Ubicación (Localidad, Lat/Long), Temporalidad (Fecha, Hora), Detalles de Infracción (Código, Descripción) y Caracterización del vehículo (Clase, Servicio).

## 🚀 Pipeline del Proyecto
1. **Definición de Esquema:** Implementación de `StructType` para asegurar la integridad de los datos en Spark.
2. **Data Wrangling:** Limpieza de nulos, estandarización de categorías y normalización.
3. **Análisis Exploratorio (EDA):** Agregaciones masivas distribuidas por localidad y tipo de servicio.
4. **Insights:** Visualización de tendencias y puntos críticos de movilidad.

## 💡 Hallazgos Principales (Insights)
* **Perfil del Infractor:** La mayor proporción de infracciones proviene de **vehículos particulares**, destacando motocicletas y automóviles.
* **Comportamiento:** El **mal estacionamiento** es la problemática recurrente identificada mediante el análisis de descripciones de infracciones.
* **Geografía Crítica:** Se detectó una alta concentración de comparendos en las localidades de **Suba, Kennedy y Engativá**.
* **Patrón Temporal:** La incidencia máxima ocurre en **horarios diurnos**, coincidiendo con los picos de flujo laboral y educativo.

## 📂 Estructura del Repositorio
- `notebooks/`: Contiene el desarrollo completo en Python/Spark.
- `data/`: Guía para la descarga de los datos abiertos.
- `reports/visualizaciones/`: Gráficas clave generadas en el análisis.

---

