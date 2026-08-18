# 5G-LTE-OPTIMIZATION-POWER-BI-DASHBOARD
# 5G & LTE RAN Performance and Geographical Optimization Dashboard

## 📊 Descripción del Proyecto
Este proyecto de analítica y optimización de redes móviles integra datos de rendimiento de radiofrecuencia (RF) con visualizaciones geoespaciales y temporales avanzadas en **Power BI**. El objetivo principal es identificar cuellos de botella en la experiencia del usuario final, correlacionando métricas clave de calidad de señal con el comportamiento de diferentes fabricantes y modelos de dispositivos (*Device Brand* y *Device Name*).

---

## 🚀 Características Principales y Arquitectura del Dashboard
* **Análisis Geoespacial de RF:** Mapeo de la señal de servicio NR (RSRP) superpuesta sobre coordenadas de latitud y longitud para identificar zonas de cobertura crítica y degradación de señal.
* **Monitoreo de Throughput y Latencia:** Seguimiento temporal del comportamiento de la velocidad de descarga (*DL Speed*) y latencia de red.
* **Segmentación por Fabricante y Dispositivo:** Evaluación comparativa del rendimiento de la red desglosada por marca y modelo de equipo terminal, permitiendo detectar anomalías específicas de compatibilidad o rendimiento de radio.

---

## 📈 Hallazgos Clave e Insights Técnicos
* **Correlación de Cobertura y Rendimiento:** Se identificaron caídas en el *DL Speed* asociadas a niveles críticos de RSRP en áreas urbanas específicas, lo que permite priorizar ajustes en los parámetros de *handover* y optimización de celdas.
* **Variabilidad por Terminal:** El análisis de marcas y modelos reveló diferencias en la estabilidad de la latencia bajo condiciones de señal marginal, datos cruciales para la planeación de capacidad en redes 5G.

---

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Power BI & DAX:** Creación de medidas personalizadas, segmentaciones dinámicas y diseño de la interfaz visual.
* **Python / SQL (Opcional):** Procesamiento, limpieza y estructuración de los registros de datos de campo antes de su importación al modelo analítico.
* **Ingeniería de Radiofrecuencia:** Análisis experto de KPIs de red (RSRP, RSRQ, Throughput, Latencia, CQI).

---

## 📂 Estructura del Repositorio
```text
├── Dashboard_Screenshots/    # Capturas de pantalla de alta resolución del reporte
├── Scripts/                  # Código y consultas utilizadas para la preparación de datos
├── Reporte_Final.pbix        # Archivo fuente de Power BI Desktop
└── README.md                 # Documentación técnica del proyecto
