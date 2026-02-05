---
title: "Movilidad urbana y productividad económica en ciudades de LATAM"
excerpt: "Análisis de la relación entre congestión urbana, tiempos de viaje y productividad económica para apoyar decisiones de inversión en infraestructura. Proyecto desarrollado como parte del Bootcamp de Data Analytics en TripleTen."
---

Este proyecto fue desarrollado como parte del Bootcamp de Data Analytics en **TripleTen**.  
El análisis se realizó desde la perspectiva de un analista del **Latin American Development Bank**, con el objetivo de evaluar cómo la movilidad urbana influye en la productividad económica de las principales ciudades de América Latina.

---

## Objetivo del análisis

Responder a las siguientes preguntas de negocio:

- ¿Qué ciudades presentan alta congestión y baja productividad económica?
- ¿Cuáles combinan movilidad eficiente y economía fuerte?
- ¿Qué variables de movilidad parecen tener mayor relación con el desarrollo urbano?

---

## Fuentes de datos

Se trabajó con dos datasets reales:

- **TomTom Traffic Index**  
  Indicadores de congestión, tiempos de viaje y retrasos urbanos.
- **OECD Cities**  
  PIB per cápita, desempleo, contaminación (PM2.5) y población.

Ambas fuentes fueron limpiadas, estandarizadas y combinadas en un único dataset por ciudad y año [1](https://zentius-my.sharepoint.com/personal/rvargas_zentius_com/_layouts/15/Doc.aspx?sourcedoc=%7B15B7CC12-4F0A-42CA-A2AB-488B1FC70AF4%7D&file=Proyecto%205%20Movilidad%20Urbana.docx&action=default&mobileredirect=true).

---

## Metodología

1. Carga y exploración inicial de datos
2. Limpieza y validación de tipos de datos
3. Filtrado por ciudades de América Latina
4. Agregación de métricas de tráfico por ciudad (promedios)
5. Unión de datasets de movilidad y economía
6. Visualización de relaciones entre variables
7. Elaboración de conclusiones e implicaciones de negocio

---

## Hallazgos clave

- Las ciudades con mayor congestión tienden a presentar **menor productividad económica**
- El tiempo de viaje adicional por congestión muestra una relación negativa con el PIB per cápita
- Ciudades con tráfico más eficiente presentan mejores indicadores laborales
- La congestión urbana aparece como un factor limitante para el desarrollo económico sostenible

---

## Implicaciones para inversión en infraestructura

- Invertir en transporte urbano puede generar retornos económicos indirectos
- La reducción de tiempos de traslado impacta productividad y calidad de vida
- Las ciudades con alta congestión y bajo PIB per cápita deben ser prioritarias para inversión
- Los datos apoyan estrategias de planificación urbana basadas en evidencia

---

## Herramientas utilizadas

- Python
- Pandas y NumPy
- Seaborn y Matplotlib
- Jupyter Notebook
