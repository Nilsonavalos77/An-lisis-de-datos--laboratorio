# LABORATORIO DE ANÁLISIS DE VENTAS
#  Proyecto – Especialización en Análisis de Datos  
## **ETL + EDA + Preguntas de Negocio sobre Dataset de Ventas**

###  Autor: *Nilson Avalos*  
###  Tecnologías: Python – Pandas – Matplotlib – Google Colab

---

##  Abrir el Notebook en Google Colab

Hacé clic aquí para abrir y ejecutar el proyecto directamente en Colab:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TU_USUARIO/TU_REPO/blob/main/NOMBRE_DEL_NOTEBOOK.ipynb)

>  **IMPORTANTE:** reemplazar en el link:
> - `TU_USUARIO` → Nilsonavalos77  
> - `TU_REPO` → LABORATORIO-DE-AN-LISIS-DE-VENTAS  

---

#  Descripción del Proyecto
 
El objetivo fue implementar un flujo completo de análisis utilizando un dataset de **150.000 transacciones reales de ventas minoristas**, aplicando:

 ETL (Extracción, Transformación y Carga)  
 EDA (Exploración y visualización)  
 Análisis descriptivo para responder preguntas de negocio  
 Documentación del proceso  
 Publicación en GitHub + ejecución desde Colab  

---

#  Estructura del Notebook

El notebook está organizado en secciones claras para facilitar su lectura:

---

##  1. **ETL – Extracción, Transformación y Carga**

Incluye:

- Importación del dataset (CSV desde Google Colab)
- Inspección de estructura
- Limpieza de datos:
  - Eliminación de duplicados
  - Manejo de valores nulos
  - Corrección de tipos ("datetime", "categorías", numéricos)
- Creación de nuevas variables:
  - `precio_unit_final`
  - `porc_impuesto`
  - `mes`, `año`
  - `ticket_promedio`

---

##  2. **EDA – Análisis Exploratorio**

Exploración con:

- `info()`, `describe()`, `value_counts()`
- Gráficos:
  - Ventas por ciudad
  - Ventas por categoría
  - Medios de pago
  - Evolución mensual de ventas
- Análisis textuales interpretando cada gráfico

---

##  3. **Preguntas de Negocio**

Se incluyen tres preguntas analíticas, con:

 Tabla resumen  
 Gráfico explicativo  
 Interpretación final  

Ejemplos:

1. **¿Qué categoría genera mayor monto total de ventas?**  
2. **¿Qué ciudad tiene el ticket promedio más alto?**  
3. **¿Qué forma de pago predomina según el tipo de producto?**  

---

#  4. Requisitos Técnicos del Proyecto

- Python 3  
- Pandas  
- Matplotlib / Seaborn  
- Google Colab  
- GitHub  

El notebook está preparado para ejecutarse sin configuración adicional.

---

# 📥 Cómo ejecutar este proyecto

1. Abrí el notebook entrando a:
