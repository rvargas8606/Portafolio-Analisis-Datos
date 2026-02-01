---
title: "Análisis de incidentes para optimizar MTTR y disponibilidad de servicios"
excerpt: "Uso de datos históricos para mejorar SLAs y decisiones operativas"
---

## Contexto del problema
La infraestructura TI presenta incidentes recurrentes que afectan los indicadores de
**disponibilidad** y el cumplimiento de **acuerdos de nivel de servicio (SLA)**.
Sin un análisis histórico estructurado, la gestión tiende a ser reactiva.

##  Problema
La ausencia de visibilidad analítica sobre incidentes provoca:
- Dificultad para identificar servicios críticos
- Escasa priorización basada en impacto
- Limitada capacidad de prevención

## Objetivo del análisis
Analizar incidentes históricos para identificar patrones que permitan:
- Reducir el **tiempo medio de resolución (MTTR)**
- Mejorar la **disponibilidad de los servicios**
- Apoyar decisiones operativas y de mejora continua

## Datos utilizados
- Registros históricos de incidentes
- Variables: severidad, duración, servicio afectado, fecha y hora
- Datos **anonimizados** por confidencialidad

##  Enfoque analítico
1. **Cálculo de indicadores**
   - MTTR por severidad y por servicio
   - Frecuencia de incidentes
2. **Análisis temporal**
   - Identificación de ventanas horarias de mayor riesgo
   - Detección de recurrencia
3. **Priorización por impacto**
   - Servicios con mayor contribución al tiempo total de indisponibilidad

##  Hallazgos clave
- Un número reducido de servicios concentraba la mayor duración de incidentes
- Ciertas franjas horarias presentaban mayor recurrencia
- La severidad media tenía un impacto acumulado mayor que incidentes críticos aislados

##  Impacto del análisis
- Definición de focos prioritarios de mejora
- Insumos para optimizar planificación operativa
- Base para estrategias preventivas y mejora de SLAs

##  Aprendizajes
El análisis de incidentes históricos permite pasar de una
gestión reactiva a una **toma de decisiones basada en datos**.
##  Decisiones habilitadas por el análisis
- Identificar servicios prioritarios para planes de mejora
- Ajustar la planificación operativa según ventanas de mayor riesgo
- Enfocar esfuerzos de mejora donde el impacto en SLA es mayor
