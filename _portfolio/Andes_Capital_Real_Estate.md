# Andes_Capital_Real_Estate

##  Descripción del Proyecto
El sector inmobiliario necesita evaluar su desempeño comercial para comprender su crecimiento, rentabilidad y comportamiento de clientes. Se creo un un dashboard ejecutivo que permita analizar ventas, clientes y propiedades para apoyar decisiones estratégicas basadas en datos. Este proyecto presenta una solución de **Business Intelligence** diseñada para transformar datos transaccionales en una herramienta de toma de decisiones para el sector inmobiliario. A través de un modelo de datos robusto, el dashboard permite monitorear la salud financiera de la empresa, evaluar la efectividad de las estrategias de precios y comprender profundamente el comportamiento de retención de los clientes durante el periodo 2023-2024.

##  Stack Tecnológico
* **Power BI Desktop:** Plataforma principal para la ingesta, modelado y visualización.
* **DAX (Data Analysis Expressions):** Motor de cálculo para medidas de Inteligencia de Tiempo, Cohortes y Variaciones.
* **Power Query (M):** Utilizado para la limpieza de datos, normalización de tipos de datos y transformación de la estructura original.
* **Modelado de Datos:** Implementación de un **Esquema en Estrella (Star Schema)** para optimizar el rendimiento de las consultas y la escalabilidad.

---

##  Pipeline de Análisis
El flujo de trabajo se dividió en cinco etapas críticas para asegurar la integridad de los insights:

1.  **Extracción y Limpieza (ETL):** Normalización de tablas de clientes, fechas y hechos de ventas.
2.  **Modelado de Datos:** Establecimiento de relaciones (1:*) entre dimensiones (`dim_clientes`, `dim_fecha`) y la tabla de hechos (`hecho_ventas`).
3.  **Desarrollo de Medidas Core:** Creación de indicadores base como Ingreso Total, Cantidad de Ventas y Ticket Promedio.
4.  **Inteligencia Avanzada:** Implementación de análisis de cohortes para medir la retención y funciones de tiempo para comparativas YoY (Year over Year).
5.  **Diseño de UX/UI:** Configuración de navegación por páginas, segmentadores interactivos y formato condicional para alertas visuales.



---

##  Funcionalidades y Análisis Implementados

### 1. Inteligencia de Tiempo (Time Intelligence)
* **Análisis YoY:** Comparativa directa de rendimiento entre 2023 y 2024.
* **Desempeño Acumulado (YTD):** Seguimiento de ingresos acumulados para control de metas anuales.
* **Líneas de Control Estadístico:** Inclusión de líneas de Máximo, Mínimo y Promedio para detectar anomalías operativas.
* **Regresión de Tendencia:** Visualización analítica del crecimiento o contracción del negocio.

### 2. Análisis de Cohortes y Retención
* **Segmentación por "Mes de Nacimiento":** Clasificación de clientes según su primera compra.
* **Matriz de Retención:** Visualización en "escalera" para cuantificar la lealtad de los clientes mes a mes.
* **Cálculo de Meses de Vida:** Lógica DAX para determinar la recurrencia real de cada segmento.

### 3. Segmentación y Participación
* **Participación por Perfil:** Análisis del peso porcentual de Inversionistas vs. Compradores de Primera Vez.
* **Navegación Dinámica:** Botones de acceso rápido para separar el análisis general de las tendencias profundas.

---

## 📈 Hallazgos Clave Extraídos

1.  **Diagnóstico de Crecimiento:** Se identificó una contracción del **6.6%** en los ingresos totales al cierre de 2024.
2.  **Eficiencia Operativa:** El negocio opera con una **Media Mensual de entre $222K y $238K**. Cualquier mes por debajo de este umbral activa una revisión de precios.
3.  **Comportamiento del Cliente:** La matriz de cohortes revela que la recurrencia se concentra en los meses 3 y 6 para el sector de inversionistas.
4.  **Optimización de Segmentos:** Identificamos qué perfil genera el mayor volumen de ingresos, permitiendo reasignar el presupuesto de marketing de manera eficiente.

---
---
**Analista:** Reinier Vargas Jardines  
**Bootcamp:** Data Analysis Sprint 11 - Proyecto Final  
**Contacto:** rvargas86@gmail.com
---
**Desarrollado por:** Reinier Vargas Jardines  
*IT Infrastructure Specialist & Data Analyst*
