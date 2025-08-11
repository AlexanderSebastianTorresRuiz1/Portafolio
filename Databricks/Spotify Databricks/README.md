# 🎶 Análisis y Visualización de Datos de Spotify (2018 - 2023)

## 📌 Descripción

Este proyecto lo desarrollé en **Azure Databricks**, donde creé un cluster para el procesamiento de datos utilizando **PySpark**. Usé **Azure Portal** para configurar un **Storage Account** con el servicio **Data Lake Storage Gen2**, donde almacené el dataset en formato CSV.

El objetivo principal fue analizar y visualizar el comportamiento de los usuarios en Spotify entre los años **2018 y 2023**, respondiendo preguntas clave del negocio y encontrando insights relevantes.

---

## 🚀 Tecnologías Utilizadas

- ☁️ **Azure Storage Account** (Data Lake Storage Gen2)
- 👥 **Microsoft Entra ID** (Azure Active Directory)
- 🔒 **Azure Key Vault & Scope Secrets** (para seguridad)
- 🐍 **PySpark & Python**
- 📊 **Matplotlib & Seaborn** (visualización de datos)
- 🎛️ **Widgets en Databricks** (para filtros dinámicos)

---

## ❓ Preguntas Clave del Negocio

- 🎧 ¿Cuántas horas se escucharon en Spotify entre los años 2018 - 2023?
- 🎶 ¿Cuántas transmisiones hubo entre los años 2020 - 2023?
- 💿 ¿Cuáles fueron los álbumes más escuchados?
- 🎵 ¿Qué géneros fueron los más escuchados?
- 💳 ¿Qué tipos de cuentas fueron más utilizadas? (Free vs Premium)
- 🎙️ ¿Qué artista fue el más escuchado por horas?
- 🌎 ¿Cuáles fueron los 10 países con más transmisiones?
- 📈 ¿Cuál es el promedio de Tasa de Salto (%) por artistas?

---

## 🧮 Filtros Dinámicos

Implementé **widgets en Databricks** para permitir un análisis interactivo, brindando al usuario la opción de ingresar el año deseado y visualizar los datos correspondientes sin modificar el código.

### 🎛️ Widget: Ingreso de Año
Este widget permite filtrar los datos por un año específico para facilitar la exploración personalizada del dataset.

---

## 🔍 Insights Encontrados

✅ En **2018** se registró el menor consumo de música, con **673,150.07 millones de horas** escuchadas.  
✅ En **2022**, se alcanzó el nivel más alto, con **823,165.02 millones de horas**.  
✅ El mayor número de transmisiones fue también en **2022**, con **245,756 millones** de reproducciones.  
✅ El álbum más escuchado en **2020** fue *Proof*, con **68,901.21 millones de horas**.  
✅ En **2019**, los géneros más populares fueron:
- *Classical*: **168,340 millones** de horas.
- *K-pop*: **129,008 millones** de horas.

✅ En 2019, el **52.5%** del consumo provino de cuentas *Premium* (**407,527 millones**), y el **47.5%** de cuentas *Free* (**368,216 millones**).  
✅ El artista más escuchado en **2021** fue **BLACKPINK**, con **129,878 millones de horas**.  
✅ En **2023**, los países con más transmisiones fueron:
- 🇸🇪 Suecia: **18,856 millones**
- 🇯🇵 Japón: **18,556 millones**

---

## 🔐 Justificación

Utilicé **Azure Data Lake Gen2 Storage** para practicar el almacenamiento seguro en la nube.  
También configuré **Scope Secrets y Azure Key Vault** para proteger credenciales y acceso al archivo CSV.  
El uso de **widgets** permitió crear una interfaz dinámica, facilitando el análisis interactivo sin necesidad de editar el código.

---

## 📈 Visualizaciones

Utilicé **Matplotlib** y **Seaborn** para generar gráficos claros y visuales que acompañaran cada uno de los insights.

---

## 📝 Conclusión

Este proyecto me permitió reforzar conocimientos en:

- Ingesta y procesamiento de datos con PySpark
- Uso de servicios en Azure (Storage, Key Vault)
- Seguridad en la nube
- Análisis de datos y visualización avanzada
- Desarrollo interactivo en Databricks

---

## 👋 Despedida

Espero que este proyecto haya sido útil e inspirador.  
Pronto estaré publicando más análisis y experimentos con otros datasets.  
¡Los animo a seguir creando proyectos, aprendiendo y compartiendo! 🚀
