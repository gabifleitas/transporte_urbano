# Urban Transport Optimisation – Power BI

This project, developed as part of the **Unicorn Academy** bootcamp, presents a detailed analysis of travel data from the fictional company **Transporte Urbano S.A.**. The aim is to explore demand patterns, operational performance and opportunities for optimisation, using a data model designed for intraday analysis.

### Description
The analysis was performed in **Power BI**, implementing a **star schema** data model that integrates:
- **Fact table [Trips]** with transport records.
- **Dimension tables [Dates] and [Times]** generated with DAX for accurate time breakdown.

This allows information to be filtered and explored at the hour, day, and month level, providing flexibility for strategic decision-making.

### Key findings
- **Weekly analysis**: 824,000 trips with slight growth in volume, higher demand on Fridays and Saturdays, and longer average duration on Sundays.
- **Monthly analysis**: peaks in demand between 7-9 a.m. and 5-7 p.m., notable drop in the early morning and on the last day of the month.
- Identification of hourly and weekly patterns that can optimise resource allocation.

### Methodology
1. **Preparation of the environment** in Power BI: deactivation of automatic date/time and relationship options.
2. **Data modelling**: creation of tables with DAX and star schema design.
3. **Visualisation**: use of segmenters, matrices and cards to display key indicators.

### Tools used
- **Power BI Desktop**
- **DAX** for measures and calculated tables


----------------------------------------------------------


Este proyecto, desarrollado como parte del bootcamp de **Unicorn Academy**, presenta un análisis detallado de los datos de viaje de la empresa ficticia **Transporte Urbano S.A.**. El objetivo es explorar patrones de demanda, desempeño operativo y oportunidades de optimización, utilizando un modelo de datos diseñado para análisis intradía.

### Descripción
El análisis se realizó en **Power BI**, implementando un modelo de datos en **esquema estrella** que integra:
- **Tabla de hechos [Viajes]** con los registros de transporte.
- **Tablas de dimensiones [Fechas] y [Horas]** generadas con DAX para un desglose temporal preciso.

Esto permite filtrar y explorar información a nivel de hora, día y mes, brindando flexibilidad para la toma de decisiones estratégicas.

### Principales hallazgos
- **Análisis semanal**: 824 mil viajes con un leve crecimiento en volumen, mayor demanda los viernes y sábados, y mayor duración promedio los domingos.
- **Análisis mensual**: picos de demanda entre las 7-9 AM y 17-19 PM, caída notable en la madrugada y el último día del mes.
- Identificación de patrones horarios y semanales que pueden optimizar la asignación de recursos.

### Metodología
1. **Preparación del entorno** en Power BI: desactivación de opciones automáticas de fecha/hora y relaciones.
2. **Modelado de datos**: creación de tablas con DAX y diseño en esquema estrella.
3. **Visualización**: uso de segmentadores, matrices y tarjetas para mostrar indicadores clave.

### Herramientas utilizadas
- **Power BI Desktop**
- **DAX** para medidas y tablas calculadas
