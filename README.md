# Southern Copper Corporation (SCCO): Equity Research & Financial Valuation

Este repositorio contiene la tesis de inversión integral y el modelo financiero avanzado de **Southern Copper Corporation (SCCO)**, desarrollado para el certamen **Valuation Trainee**. El proyecto destaca por una arquitectura de datos robusta, utilizando la terminal **Bloomberg** para la extracción de métricas históricas, análisis de comparables y proyecciones de mercado.

🎯 **Objetivo:** Determinar el valor intrínseco de SCCO mediante una metodología de valoración por Flujos de Caja Descontados (DCF) y Múltiplos de Mercado, integrando el ciclo de los commodities y el análisis de riesgos jurisdiccionales.

---

## 📖 Extended Overview
Este trabajo representa una evaluación exhaustiva de Southern Copper, uno de los productores de cobre con los costos más bajos a nivel mundial. Se aplicó un enfoque *Bottom-Up* para proyectar la capacidad operativa y financiera de la compañía, analizando la dinámica global de precios del metal rojo y la eficiencia de sus unidades mineras en Perú y México.



### 💎 Integración con Terminal Bloomberg & Data Engine
Un pilar fundamental de este proyecto fue el uso de la plataforma **Bloomberg** para garantizar la precisión y profesionalismo de la data analizada en los modelos de Excel:

* **Extracción de Data Histórica:** Obtención de estados financieros auditados (IS, BS, CF) de los últimos 10 años, métricas de producción y *Cash Costs* detallados.
* **Análisis de Comparables (Comps):** Identificación y normalización de múltiplos (*EV/EBITDA*, *P/E*, *P/S*) frente a pares globales como **Freeport-McMoRan**, **BHP**, **Rio Tinto** y **Antofagasta**.
* **Costo de Capital (WACC):** Extracción de Betas ajustadas, tasas libres de riesgo y diferenciales de crédito para construir una tasa de descuento robusta (Cálculo WACC 2024: ~16.46%).
* **Market Consensus:** Incorporación de estimaciones de analistas (*Ratings*) y precios objetivo para contrastar con la valoración propia.

---

## 📁 Estructura del Repositorio

### 1. Tesis de Inversión (`Tesis_de_Inversion_SCCO.pdf`)
Documento ejecutivo que detalla:
* **Macro Tesis:** Dinámica de oferta/demanda del cobre y transición energética.
* **Moat Económico:** Ventajas competitivas en costos de extracción.
* **Riesgos:** Análisis de riesgo político y social en Perú y México.

### 2. Modelo Financiero (`Valuation_B20_Modelo.xlsx`)
El motor cuantitativo del proyecto, estructurado en módulos interconectados:

* **Income & Segment Analysis:** Desglose de ingresos por geografía (México, Perú) y por metal (Cobre, Molibdeno, Zinc, Plata). Proyección de ventas basada en curvas de precios de commodities.
* **Financial Ratios:** Dashboard de rentabilidad (*ROE, ROA, ROIC*), liquidez y solvencia histórica y proyectada.
* **Capital Structure:** Cálculo dinámico del WACC, ponderando el costo del *Equity* y la Deuda, ajustado por riesgo país.
* **DCF Model:** Valoración por Flujos de Caja Libres para la Firma (*FCFF*) con análisis de valor terminal (Método de Perpetuidad vs. Salida por Múltiplos).
* **Relative Valuation:** Matriz de valoración relativa comparando múltiplos (*P/E*, *EV/EBITDA*) contra la media de la industria y pares directos.

---

## 📈 Resultados Clave de la Valoración
* **Resiliencia Operativa:** SCCO mantiene uno de los márgenes EBITDA más altos de la industria gracias a su bajo *Cash Cost*.
* **Sensibilidad:** El modelo incluye tablas de sensibilidad para evaluar el impacto de la volatilidad del precio del cobre (+/- 10%) en el Precio Objetivo.
* **Posicionamiento:** La valoración sugiere una prima justificada por la calidad de las reservas y la vida útil de las minas en comparación con sus pares.

---

## 🚀 Tecnologías y Herramientas Usadas
* **Data Sources:** Terminal Bloomberg (Series de tiempo, *Equity Screening*, *Analyst Recommendations*).
* **Financial Modeling:** Microsoft Excel (Modelado financiero dinámico, tablas de sensibilidad y análisis de escenarios).
* **Concepts:** Valoración por DCF, *Equity Research*, Análisis de Múltiplos, WACC y *Capital Budgeting*.

---
