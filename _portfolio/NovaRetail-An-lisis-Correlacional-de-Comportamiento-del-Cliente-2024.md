---
layout: post
title: "NovaRetail+: Comportamiento del Consumidor e Ingresos"
excerpt: "Estudio correlacional en Python para identificar los drivers críticos de gasto anual y lealtad en e-commerce latinoamericano."
category: portfolio
---

# NovaRetail-An-lisis-Correlacional-de-Comportamiento-del-Cliente-2024
Proyecto SP8 del BootCamp Analista de Datos
# 🛒 NovaRetail+: Factores de Comportamiento e Ingreso Anual (2024)

## 📝 Descripción del Proyecto
Este proyecto analiza el comportamiento de los usuarios de **NovaRetail+**, una plataforma líder de e-commerce en Latinoamérica. El objetivo es identificar qué factores (frecuencia de compra, edad, dispositivo, región) impactan significativamente en el **ingreso anual** generado por los clientes al cierre de 2024.

---

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python 3.10+
* **Librerías principales:** * `Pandas` y `NumPy`: Procesamiento y limpieza de datos.
    * `Seaborn` y `Matplotlib`: Visualización estadística.
    * `SciPy`: Pruebas de correlación y análisis de varianza.

---

## ⚙️ Pipeline de Análisis
1. **Data Wrangling:** Identificación de nulos, corrección de tipos de datos y manejo de registros duplicados.
2. **EDA (Análisis Exploratorio):** Estudio de distribuciones del ingreso mediante histogramas y boxplots para detectar valores atípicos.
3. **Análisis Estadístico:** Cálculo de matrices de correlación (Pearson) para validar hipótesis sobre el comportamiento del consumidor.

---

## 📈 Resultados y Análisis Estadístico
Tras el análisis de correlación, se obtuvieron los siguientes hallazgos:

| Variable | Correlación con Ingreso | Impacto en Negocio |
| :--- | :---: | :--- |
| **Frecuencia de Compra** | Alta (+) | Principal motor de ingresos; clave para programas de lealtad. |
| **Edad del Usuario** | Moderada | Segmento de 35-50 años muestra mayor estabilidad de gasto. |
| **Tipo de Dispositivo** | Casi nula | El cliente gasta igual en móvil que en escritorio (omnicanalidad). |

### 💡 Insight Principal
> "La frecuencia de compra tiene una asociación mucho más fuerte con el ingreso anual que la ubicación geográfica. Para escalar NovaRetail+, es más rentable aumentar la recurrencia de los clientes actuales que invertir en expansión territorial masiva."

---

## 🎯 Conclusiones y Recomendaciones
1. **Fidelización:** Dado que la frecuencia es el driver principal, se recomienda implementar sistemas de suscripción o beneficios por compras recurrentes.
2. **Diseño UX:** Al no existir diferencias de ingreso por dispositivo, la experiencia de usuario debe mantenerse idéntica y fluida en todas las plataformas (Mobile First).
3. **Estabilidad Regional:** El negocio es sólido en toda LATAM; la uniformidad de los ingresos permite aplicar estrategias de marketing globales con pocos ajustes locales.

---
**Analista:** Reinier Vargas Jardines  
**Bootcamp:** Data Analysis Sprint 8 - Proyecto Final  
**Contacto:** rvargas86@gmail.com
