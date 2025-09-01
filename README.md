# 🛠️ IT Support Ticket Desk Dashboard

Este proyecto de análisis y visualización simula la gestión de más de **1,000 tickets de soporte TI**, utilizando información similar a la de Jira Service Management. A través de dashboards interactivos, puedes explorar métricas clave sobre problemas, equipos, prioridades, tiempos de resolución y distribución geográfica.

![Vista General del Dashboard](dashboard_general.png)
![Tipos de Tickets](dashboard_tipos.png)
![Análisis de Prioridades y Resolución](dashboard_prioridades.png)
![Distribución Geográfica de Tickets](dashboard_geografico.png)

---

## 🎯 Objetivos del Proyecto

- Identificar los **tipos de problemas** más frecuentes.
- Evaluar el **flujo de trabajo** por equipos/colas.
- Analizar el **uso de etiquetas** (ej. Seguridad, Integración).
- Medir **tiempos promedio de resolución** por tipo.
- Relacionar la **prioridad con el tiempo de respuesta**.
- Visualizar la **distribución geográfica** de solicitudes y demoras.
- Detectar **oportunidades de mejora** y automatización.

---


## 🛠️ Herramientas Utilizadas

- **Power BI Desktop** (modelado y visualización)
- **Python (Pandas)** (limpieza y preparación de datos)
- **DAX** (medidas y cálculos para KPIs)
- **Power Query** (transformaciones)

---

## 📈 Principales Visualizaciones

- KPIs globales: tickets totales, resueltos, tiempos promedio.
- Gráficos de barras/donuts por tipo de ticket, flujo por equipo y etiquetas.
- Evolución temporal y backlog de incidencias.
- Análisis geográfico por país y región.
- Tablas dinámicas por prioridad, equipo y ubicación.

---

## 🔍 Hallazgos Clave

- **Errores e Incidencias** son el principal motivo de solicitud.
- Los equipos de **Soporte General** y **Infraestructura** gestionan la mayoría de tickets.
- **Etiquetas de Seguridad** e **Integración** aparecen en >30% de tickets críticos.
- Los **tickets de alta prioridad** se resuelven en promedio un 45% más rápido.
- Las regiones del **sur y centro** presentan mayores tiempos de respuesta.
- Se identificaron flujos de trabajo repetitivos, candidatos para automatización.

---

## 💡 Oportunidades de Mejora

- Establecer respuestas y flujos automáticos para incidencias comunes.
- Rediseñar los procesos en regiones con mayores tiempos de espera.
- Monitorear tickets etiquetados como **críticos** para priorización automática.
- Mejorar la calidad de datos en descripciones y categorización de solicitudes.

