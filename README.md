# Inteligencia Operativa: Anticipando el futuro de la infraestructura a través de los datos

## Perfil Profesional
Ingeniero Informático especializado en Data Analytics, con más de 12 años de experiencia en la gestión de infraestructuras críticas. Experto en transformar grandes volúmenes de datos operativos en indicadores de Alta Disponibilidad.

## Mis Proyectos
Estructura de Proyecto: Análisis de Disponibilidad y Rendimiento de Red
1. Descripción del Proyecto
Este proyecto analiza el rendimiento de una infraestructura crítica mediante el procesamiento de logs de servidores y dispositivos de red. El objetivo es identificar patrones de fallos, picos de tráfico y optimizar el cumplimiento de los SLA.

2. El Problema (Contexto)
En entornos de NOC, la detección reactiva de fallos genera tiempos de inactividad que afectan la continuidad del negocio. Se requiere un análisis histórico que permita pasar de un soporte reactivo a un mantenimiento preventivo.

3. Herramientas y Habilidades Técnicas

Lenguaje: Python (Pandas, NumPy) para la limpieza de datos.

Bases de Datos: SQL para la extracción de registros de logs.

Visualización: Tableau o Power BI para el monitoreo de métricas.

Infraestructura: Análisis de datos provenientes de herramientas como Nagios o check_mk.

4. Proceso (Metodología)

Extracción (ETL): Obtención de datos de disponibilidad y latencia de los servidores de Teknovud y Zentius.

Limpieza de Datos: Tratamiento de valores nulos y normalización de formatos de fecha y hora.

Análisis Exploratorio (EDA): Identificación de horas pico de carga y correlación entre alertas de seguridad y caídas de servicio.

5. Resultados e Impacto 

Reducción del 15% en tiempos de inactividad mediante la identificación de causas raíz recurrentes.

Creación de un dashboard interactivo que permite visualizar el estado de salud de la red en tiempo real.

Optimización del uso de recursos en servidores virtuales, maximizando la eficiencia energética.

Proyecto 2: Análisis de Correlación de Fallas y Optimización de Disponibilidad en Redes MPLS
1. Descripción del Proyecto
Este proyecto presenta un análisis detallado sobre la recurrencia de interrupciones en servicios de conectividad crítica. A través del cruce de datos de monitoreo (Zabbix/Meraki) y tickets de incidentes, se identificó la causa raíz de la degradación del servicio, permitiendo transitar de un soporte reactivo a una estrategia de mitigación de riesgos.

2. El Problema (Contexto de Negocio)
Una estación de red presentaba una disponibilidad del 96.1%, quedando por debajo de los estándares óptimos de operación. El servicio MPLS sufría desconexiones sistemáticas que no se recuperaban automáticamente, exigiendo intervenciones manuales recurrentes que ponían en riesgo la continuidad del negocio.

3. Herramientas y Habilidades Técnicas

Análisis de Datos: Correlación de eventos temporales y análisis de causa raíz (Root Cause Analysis).

Monitoreo Técnico: Interpretación de métricas ICMP, picos de pérdida de paquetes y registros de reinicio de hardware.

Plataformas: Zabbix (Monitoreo de red) y Meraki (Gestión de equipos de nube).

Reporting: Elaboración de informes de impacto y recomendaciones estratégicas para stakeholders.

4. Hallazgos Clave mediante el Análisis

Identificación de Patrones: Se detectó un patrón de recurrencia anual donde los picos de desconexión coincidían sistemáticamente con fallas en el suministro eléctrico del sitio.

Correlación de Incidentes: Se analizaron múltiples tickets de soporte (ej. INC 2025-050022, INC 2025-136850) confirmando que la pérdida de energía en el equipo MX impedía la recuperación automática del enlace.

Visualización de Evidencia: El análisis de gráficos de monitoreo permitió registrar "reboots" por pérdida de energía, validando la hipótesis de que el fallo no era del equipo de red, sino de la infraestructura de respaldo.

5. Recomendaciones Basadas en Datos
Como resultado del análisis, se propuso un plan de acción priorizado para elevar la disponibilidad al 99.9%:

Prioridad Alta: Instalación de sistemas de alimentación ininterrumpida (UPS) con autonomía de 30 a 60 minutos para mitigar fallas transitorias.

Prioridad Media: Implementación de monitoreo proactivo sobre la salud de las baterías y la fuente de alimentación del UPS.

Prioridad Baja: Optimización de los parámetros de recuperación del protocolo MPLS para acelerar el restablecimiento tras un reinicio forzado.
