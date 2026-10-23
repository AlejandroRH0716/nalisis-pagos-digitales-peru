# Transición hacia el Dinero Digital en el Perú (2024–2026)

Análisis macrofinanciero interactivo sobre la adopción de billeteras móviles (Yape, Plin), cuota de mercado y desplazamiento del retiro de efectivo en cajeros automáticos del sistema financiero peruano.

![Vista General del Dashboard](img/dashboard_overview.png)

## 📌 Contexto & Hallazgos Clave
- **Cruce Histórico (Sep 2025):** El valor de las transferencias digitales interbancarias superó por primera vez al total de retiros de efectivo en cajeros automáticos (S/ 13,534 M vs. S/ 13,446 M).
- **Monto Promedio por Operación:** Marcada diferenciación de uso: Yape promedia ~S/ 40-45 (microtransacciones diarias), mientras que Plin promedia ~S/ 60-70 por operación.
- **Interoperabilidad:** Crecimiento sostenido del canal interbancario alcanzando más de 260 millones de transacciones mensuales.

## 🛠️ Herramientas y Técnicas
- **Power BI Desktop:** DAX avanzado (Time Intelligence, ratios, métricas dinámicas), diseño corporativo oscuro, modelado relacional y nuevos segmentadores de botones.
- **Power Query (M):** Limpieza, normalización y transformación de series temporales.
- **Fuente de Datos:** Banco Central de Reserva del Perú (BCRPData).

## 📂 Estructura del Repositorio
- `/data`: Series estadísticas descargadas del BCRP.
- `/img`: Capturas del reporte en alta resolución.
- `Peru_Digital_Payments.pbix`: Archivo fuente de Power BI.
