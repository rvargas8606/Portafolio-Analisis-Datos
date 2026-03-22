---
title: "A/B Testing: Optimización de Tasa de Conversión"
excerpt: "Evaluación estadística de variantes de interfaz para maximizar el ARPU y reducir la fricción en el funnel de ventas."
---

# A/B Testing: Optimización de Landing Page mediante Análisis Estadístico

##  Descripción del Proyecto
Este proyecto evalúa los resultados de un experimento A/B aplicado a una Landing Page comercial. El objetivo principal es determinar si la **Versión B** (nueva variante) genera una mejora significativa en la **Tasa de Conversión (CR)** y el **Gasto Promedio por Usuario (Spent)** en comparación con la **Versión A** (control).

A través de este análisis, se busca proporcionar una recomendación basada en datos para el despliegue definitivo de la nueva interfaz.

---

##  Stack Tecnológico
* **Python 3.x**
* **Pandas & NumPy:** Manipulación de datos y limpieza.
* **Seaborn & Matplotlib:** Visualización de distribuciones y comparativas.
* **Scipy.stats:** Pruebas de hipótesis y cálculo de p-values.

---

##  Metodología del Experimento
El análisis sigue un flujo de trabajo estructurado para garantizar la validez de los resultados:
1. **Validación de Datos:** Limpieza de nulos y verificación de que no existan usuarios duplicados en ambos grupos (fuga de datos).
2. **Análisis de Conversión:** Comparativa de proporciones de éxito entre el Grupo A y el Grupo B.
3. **Análisis de Gasto:** Evaluación del ticket promedio para usuarios que convirtieron.
4. **Segmentación:** Desglose de resultados por Fuente de Tráfico (Social, Search, Direct) y Tipo de Usuario (New vs. Returning).

---

##  Resultados Principales

### 1. Gasto Promedio (ARPU)
* **Hallazgo:** El Grupo B registró un gasto promedio de transacción superior al Grupo A.
* **Impacto:** La nueva landing no solo convierte, sino que atrae a un perfil de cliente con mayor disposición al gasto.

### 2. Tasa de Conversión (CR)
* **Hallazgo:** La Versión B superó la tasa de conversión base. 
* **Significancia:** El análisis sugiere que los cambios visuales o de copy redujeron efectivamente la fricción en el funnel de ventas.

### 3. Insights por Segmento
* **Tráfico:** Los usuarios de **Búsqueda (Search)** muestran la mayor afinidad con la Versión B.
* **Lealtad:** Los **Usuarios Nuevos** presentan la mayor tasa de adopción de la nueva interfaz.

---

##  Conclusiones y Recomendaciones
1. **Implementar Versión B:** Dado el incremento en ambas métricas (CR y Spent), se recomienda el despliegue total de la variante B.
2. **Optimización de Canales:** Incrementar el presupuesto de marketing en canales de **Social y Search**, ya que son los que mejor "aterrizan" en esta nueva landing.
3. **Iteración Continua:** Monitorear el comportamiento de los usuarios recurrentes a largo plazo para asegurar que la mejora en el gasto se mantenga constante.

---

##  Cómo ejecutar el proyecto
1. Clonar el repositorio.
2. Asegurarse de tener instalado `pandas`, `seaborn` y `scipy`.
3. Ejecutar el archivo `S9 Version_Student_Proyecto_Landing_Experiment.ipynb` en Jupyter Notebook o VS Code.

---
**Desarrollado por:** Reinier Vargas Jardines  
**Especialidad:** Análisis de Datos / Experimentación A/B  
**Bootcamp:** Data Analyst Proyecto Final Sprint 9 
