---
title: "Análisis de eventos para reducir ruido operativo en monitoreo NOC"
excerpt: "Priorización basada en datos para mejorar la atención de incidentes críticos"
---

## 📌 Contexto del problema
En entornos de NOC, el alto volumen de alertas genera **fatiga operativa** y dificulta la
identificación oportuna de incidentes con impacto real en la continuidad del servicio.
Gran parte de las alertas no requieren acción inmediata, pero consumen tiempo y atención
del equipo.

## ❗ Problema
La falta de análisis histórico y de criterios claros de priorización provoca:
- Saturación del canal de monitoreo
- Respuesta tardía a incidentes críticos
- Uso ineficiente de los recursos del NOC

## 🎯 Objetivo del análisis
Identificar patrones de alertas repetitivas y no accionables para **reducir falsos positivos**
y mejorar la **priorización operativa** de eventos críticos.

## 🧪 Datos utilizados
- Logs históricos de eventos y alertas del NOC
- Campos clave: timestamp, tipo de evento, severidad, origen, componente afectado
- Datos **anonimizados** por confidencialidad

## 🔍 Enfoque analítico
1. **Análisis exploratorio (EDA)**
   - Distribución de alertas por severidad y horario
   - Identificación de picos operativos
2. **Detección de redundancias**
   - Eventos repetidos con mismo origen y firma
   - Alertas sin correlación con incidentes reales
3. **Agrupación de eventos**
   - Clasificación por tipo, componente y ventana temporal
4. **Validación operativa**
   - Contraste de hallazgos con criterios del equipo NOC

## 📈 Hallazgos clave
- Un conjunto reducido de tipos de alerta generaba un porcentaje desproporcionado del volumen total
- Se detectaron patrones horarios con alta recurrencia y bajo impacto
- Varias alertas no aportaban información adicional para la toma de decisiones

## 💡 Impacto del análisis
- Base analítica para **reducción de alertas no accionables**
- Mejora en la **priorización de incidentes críticos**
- Insumo para disminuir el tiempo medio de atención y resolución (MTTR)

## 🧠 Aprendizajes
La reducción de ruido operativo no depende de eliminar alertas,
sino de **entender su contexto y su valor real para la decisión operativa**.
``
## ✅ Decisiones habilitadas por el análisis
- Definir qué tipos de alertas requieren atención inmediata
- Priorizar eventos críticos sobre alertas repetitivas
- Justificar ajustes en reglas de monitoreo basados en evidencia
