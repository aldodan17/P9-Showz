📊 P9 — Análisis de Marketing y Métricas de Producto para Showz

👤 Autor: Aldo Daniel Galván Rodríguez

🧠 Descripción general del proyecto

Este proyecto simula el trabajo de un analista de datos en Showz, una plataforma de venta de entradas. El objetivo principal fue evaluar el rendimiento de los canales de marketing, entender el comportamiento del usuario y determinar qué fuentes publicitarias aportan clientes rentables, utilizando datos reales de visitas, pedidos y gastos.

El análisis incluye:
✔ Limpieza y preparación de datos
✔ Métricas de comportamiento (sesiones, retornos, conversión)
✔ Análisis de cohortes
✔ Cálculo de LTV, CAC, ARPU, ARPPU y ROMI
✔ Visualizaciones avanzadas
✔ Conclusiones estratégicas para optimizar la inversión publicitaria

🛠️ Tecnologías utilizadas

Python
pandas
numpy
matplotlib
seaborn
datetime
Análisis de Cohortes
Métricas de Producto (LTV, CAC, ROMI)
EDA (Exploratory Data Analysis)

📌 Metodología del proyecto
1️⃣ Preparación y limpieza de datos
Conversión de fechas y tipos de datos.
Corrección de sesiones con valores erróneos.
Integración de datasets (visitas, pedidos, costos).
Cálculo de duración de sesiones y parámetros por usuario.

2️⃣ Análisis de comportamiento del usuario

Visitas diarias, semanales y mensuales.
Número de sesiones por usuario.
Frecuencia de retorno.
Tiempo desde el registro hasta la primera compra (Conversion 0d, 1d, etc.).
Distribuciones de compras por cohorte.

3️⃣ Análisis de ventas y valor del cliente

Tamaño promedio de pedido (AOV).
Número de pedidos por usuario y por cohorte.
LTV por cohortes y por fuente de adquisición.
Comparación del gasto vs ingresos obtenidos.

4️⃣ Análisis de marketing y rentabilidad

CAC por fuente.
Curvas de gasto acumulado.
Evaluación del retorno (ROMI) por cada plataforma.
Identificación de los canales más y menos rentables.
Visualizaciones para entender el rendimiento por dispositivo, fuente y periodo temporal.

📈 Resultados principales

Las cohortes con mayor LTV provenían de fuentes con mayor costo, pero también con mayor retención y número de pedidos.
Varias fuentes de adquisición tenían CAC por encima del LTV, lo que implica pérdidas.
Se identificaron canales que, con menor inversión, generan usuarios de alto valor.
El performance cambia significativamente por dispositivo y periodo del año.

🧪 Conclusiones y recomendaciones

Aumentar inversión en las fuentes con ROMI positivo y LTV superior al CAC.
Reducir presupuesto en canales con adquisición costosa y baja retención.
Segmentar campañas por dispositivo y temporada.
Analizar cohortes más recientes para monitorear cambios en el comportamiento.
