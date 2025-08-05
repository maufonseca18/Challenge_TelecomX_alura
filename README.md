# Proyecto: Análisis de Evasión de Clientes – Telecom X

Este repositorio contiene el análisis de datos realizado sobre el comportamiento de evasión (*churn*) de clientes de la empresa ficticia **Telecom X**.  
El objetivo principal es identificar los factores que más influyen en la cancelación del servicio y proponer estrategias para mejorar la retención de clientes.

---

## Contexto

La evasión de clientes es un problema recurrente en el sector de las telecomunicaciones. Comprender qué variables se asocian con la cancelación de servicios permite tomar decisiones estratégicas para disminuir la rotación y mejorar la satisfacción del usuario.

Este análisis se basa en un dataset de más de **7,200 clientes**, que incluye información demográfica, tipo de servicios contratados, detalles de cuenta y cargos asociados.

---

## Objetivos del proyecto

- Analizar el comportamiento de los clientes y su relación con la tasa de evasión.  
- Identificar las características que aumentan el riesgo de cancelación (contrato, tipo de internet, método de pago).  
- Explorar patrones en cargos mensuales, antigüedad del cliente y uso de servicios adicionales.  
- Ofrecer conclusiones y recomendaciones basadas en los hallazgos.

---

## Contenido del repositorio

- `TelecomX_Data.json`: Archivo base con los datos de clientes.  
- `Proyecto_TelecomX.ipynb`: Notebook con el análisis completo (limpieza, visualización y conclusiones).  
- `README.md`: Este archivo, con la descripción general del proyecto.

---

## Metodología

1. **Importación y normalización de datos**: Conversión de columnas anidadas en estructura tabular.  
2. **Limpieza y tratamiento**: Corrección de valores inconsistentes, mapeo de variables binarias y manejo de nulos.  
3. **Transformación**: Creación de métricas adicionales como gasto diario estimado.  
4. **Análisis exploratorio (EDA)**: Estadísticas descriptivas y visualizaciones interactivas.  
5. **Conclusiones**: Interpretación de hallazgos y propuestas para reducir la evasión.

---

## Resultados principales

- La tasa de evasión es mayor en clientes con **contratos mensuales** y menor en contratos a largo plazo.  
- Los usuarios de **fibra óptica** y servicios de **streaming** muestran mayor tendencia a cancelar.  
- La antigüedad del cliente es un factor clave: los primeros meses presentan mayor riesgo de evasión.  
- El género no presenta una diferencia significativa en el comportamiento de cancelación.

---

## Tecnologías utilizadas

- **Python 3**  
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`  

---

## Cómo usar este proyecto

1. Clona este repositorio:  
   ```bash
   git clone https://github.com/TU_USUARIO/telecomx-churn.git
