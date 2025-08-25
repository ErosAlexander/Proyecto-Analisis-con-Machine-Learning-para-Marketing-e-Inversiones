# 📊 Análisis con Machine Learning para Marketing e Inversiones  

## 📌 Descripción del Proyecto  
Este proyecto se centra en analizar datos de clientes y sus decisiones de inversión, con el fin de aplicar **técnicas de Machine Learning** que permitan identificar patrones de comportamiento y mejorar la estrategia de marketing de la empresa.  

Se trabajó con modelos de clasificación y árboles de decisión para predecir la **adherencia de los clientes a inversiones** en función de sus características financieras.  

## 🔍 Datos Analizados  
- **Fuente de datos:** archivo `marketing_inversiones.csv`.  
- **Tipo de datos incluidos:**  
  - Información de clientes (edad, ingresos, saldo en cuenta, historial financiero).  
  - Datos sobre inversiones y adherencia a productos financieros.  
  - Variable objetivo: nivel de adherencia a la inversión.  
- **A qué se refieren los datos:** a registros de clientes con relación a sus decisiones de inversión.  
- **Quiénes están representados:** clientes de la empresa que ofrece productos de inversión.  

## 🛠️ Tecnologías Utilizadas  
- **Entorno de desarrollo:** Google Colab.  
- **Lenguaje de programación:** Python 3.  
- **Formatos de datos:** CSV, notebooks Jupyter (`.ipynb`).  

## 📚 Librerías Usadas  
- **Pandas:** manipulación y limpieza de datos.  
- **NumPy:** operaciones numéricas y matriciales.  
- **Matplotlib:** visualización de gráficos.  
- **Seaborn:** visualización estadística con mejor diseño.  
- **Scikit-learn:** construcción y evaluación de modelos de Machine Learning.  
- **Plotly Express:** visualización interactiva de datos.  

## 📊 Visualizaciones Realizadas  

### 📌 Árbol de Decisión del Modelo  
- **Visualización del árbol de decisión** generado por el modelo entrenado.  

![Árbol de decisión del modelo](/img/plot_tree%20modelo_arbol.png)  

👉 Permite comprender cómo el modelo toma decisiones, qué variables son más importantes y cómo se definen los criterios de clasificación.  

---

### 📌 Distribución del saldo por adherencia a la inversión  
- **Boxplot interactivo con Plotly** mostrando la relación entre el saldo y la adherencia a la inversión.  

![Boxplot de saldo y adherencia a inversión](/img/px.box%20X%20saldo%20color%20adherencia_inversion.png)  

👉 Ayuda a visualizar la distribución del saldo entre los diferentes niveles de adherencia y detectar patrones financieros relevantes.  

---

## ⚠️ Problemas Encontrados y Soluciones  
- **Datos con valores extremos (outliers):** se visualizaron con boxplots y se analizó su impacto en el modelo.  
- **Sobreajuste en modelos iniciales:** se mitigó aplicando poda en árboles de decisión y ajustando hiperparámetros.  
- **Interpretación del modelo:** se complementó con visualizaciones del árbol y métricas de evaluación para una mejor explicación.  

## 📈 Resumen del Análisis  
- Se entrenó un modelo de árbol de decisión para predecir la adherencia a inversiones.  
- Se observaron relaciones claras entre el **saldo de clientes** y su probabilidad de invertir.  
- Las variables financieras tuvieron un mayor peso en la clasificación que las demográficas.  
- Las visualizaciones permitieron comprender mejor el comportamiento de los clientes y validar los resultados del modelo.  

## ✅ Conclusión  
El análisis mostró que existen **patrones financieros clave** que influyen en la decisión de inversión de los clientes.  
El árbol de decisión permitió identificar reglas claras de clasificación, mientras que los boxplots evidenciaron la relación entre **saldo y adherencia**.  

Estos resultados ofrecen un valor estratégico para el área de **marketing y gestión de inversiones**, ayudando a diseñar campañas más segmentadas y efectivas.  
