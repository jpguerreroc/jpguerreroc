## José Pablo Guerrero Chaves

**Economist · Data analysis and official statistics · Costa Rica**

*[Español abajo ↓](#-español)*

Bachelor's degree in Economics (Universidad Latina de Costa Rica) and a
Licentiate in progress. I am currently doing my professional internship at the
**Central Bank of Costa Rica**, in the Data Analysis and Statistics Division,
International Accounts Statistics area.

I work at the intersection of applied economics and data analysis: time series,
official statistics, and questions that end in a decision rather than a table.
Every figure I report can be traced back to its source, and gaps are declared as
gaps.

---

### Projects

**U.S. shocks and Costa Rica's external sector, 2015–2025** *(private — thesis in progress)*
Does Costa Rica feel the United States through trade or through the Fed's policy
rate? Three VAR/VECM blocks on public data from FRED and the Central Bank of
Costa Rica. **The financial channel dominates the real one in all 14**
variable-horizon combinations. At 24 months, the federal funds rate explains
**44.4 %** of the variance in international reserves and **43.2 %** of the real
effective exchange rate; the U.S. industrial cycle explains 3.3 % and 4.5 %.
Unit root tests flagging ambiguous cases, Engle-Granger and Johansen
cointegration, Granger causality, bootstrapped impulse responses and variance
decomposition. Reproducible end to end.

**[Data warehouse and quality engine for macro time series](https://github.com/jpguerreroc/warehouse-sector-externo)**
DuckDB star schema over a macroeconomic panel, with **proof that moving the data into
SQL did not alter a single number**: 18 series reconcile against the validated
Python pipeline. The Central Bank publishes trade figures accumulated within the
year; deaccumulation is done in SQL with a window partitioned by year and
reconciles to `5.7e-14`. Seven data-quality checks that return the failing rows,
not a boolean — 0 errors and 3 warnings on this data, all three genuine
macroeconomic shocks rather than capture errors.

**[Nowcasting Costa Rica's quarterly GDP](https://github.com/jpguerreroc/portfolio-data-analytics/tree/main/nowcasting-pib)**
Estimating GDP growth before the official figure is released, using OECD
short-term indicators. The nowcast cuts the error **30.6 %** against the naive
benchmark — but only **6.5 %** against the historical mean, which is the
demanding one. Both numbers are in the README, along with the R² of 0.154 and
the fact that the model did not anticipate the 2020 break.

**[Customer churn and lifetime value](https://github.com/jpguerreroc/portfolio-data-analytics/tree/main/churn-supervivencia)**
Survival analysis on 7,043 customers. Month-to-month contracts churn at
**42.7 %** against **2.8 %** for two-year contracts, at nearly identical monthly
fees. Kaplan-Meier estimator implemented from scratch and validated against
`lifelines` (max difference 4.33e-15).

**[Automated job-posting tracker](https://github.com/jpguerreroc/portfolio-data-analytics/tree/main/buscador-vacantes)**
Queries public job-board APIs and documents how each one actually behaves —
including the ones that fail silently.

---

### Tools

`Python` · `pandas` · `numpy` · `statsmodels` · `SQL` · `Power BI` ·
`Excel / Power Query` · `Git`

**Methods:** time series, VAR/VECM, cointegration tests (Engle-Granger,
Johansen), Granger causality, regression models, survival analysis.

**Official statistics:** balance of payments (BPM6), OECD Benchmark Definition
(BD4), foreign direct investment, international accounts.

---

### How I work

- The finding comes first, with a number.
- Limitations are declared. A result that does not survive scrutiny is a
  finding, not a failure to hide.
- Public data only, with reproducible downloads from the code itself.

📍 Costa Rica · Native Spanish, C1 English
[LinkedIn](https://linkedin.com/in/jpguerreroc) · guerrerochavesjosepablo@gmail.com

---
---

## 🇨🇷 Español

**Economista · Análisis de datos y estadísticas · Costa Rica**

Bachillerato Universitario en Economía (Universidad Latina de Costa Rica) y
Licenciatura en curso. Actualmente realizo mi práctica profesional en la División de
Análisis de Datos y Estadísticas del **Banco Central de Costa Rica**, en el área de
Estadísticas de Cuentas Internacionales.

Trabajo en la intersección entre economía aplicada y análisis de datos: series de
tiempo, estadística oficial y preguntas que terminan en una decisión, no en una tabla.

### Proyectos

**EE. UU. y el sector externo de Costa Rica, 2015–2025** *(privado — TFG en curso)*
¿Costa Rica siente a Estados Unidos por el comercio o por la tasa de la Fed? Tres
bloques VAR/VECM sobre datos de FRED y del portal público del BCCR. **El canal
financiero domina al real en las 14 combinaciones de variable y horizonte.** A 24
meses, la tasa de fondos federales explica el **44,4 %** de la varianza de las
reservas internacionales y el **43,2 %** del tipo de cambio efectivo real; el ciclo
industrial estadounidense, 3,3 % y 4,5 %. Pipeline completo: ADF y KPSS marcando
las filas ambiguas, Engle-Granger y Johansen, causalidad de Granger,
impulso-respuesta con banda bootstrap y descomposición de varianza.

**[Warehouse y motor de calidad para series macro](https://github.com/jpguerreroc/warehouse-sector-externo)**
Esquema estrella en DuckDB sobre un panel macroeconómico, con **la prueba de que pasar
los datos a SQL no alteró ni un número**: 18 series reconcilian contra el pipeline
validado en Python. El BCCR publica el comercio acumulado dentro del año; la
desacumulación se hace en SQL con una ventana particionada por año y reconcilia a
`5,7e-14`. Siete chequeos de calidad que devuelven las filas que fallan — 0 errores
y 3 avisos, y los tres avisos son choques macro reales, no errores de captura.

**[Nowcasting del PIB trimestral de Costa Rica](https://github.com/jpguerreroc/portfolio-data-analytics/tree/main/nowcasting-pib)**
Estimar el crecimiento del PIB antes de que se publique la cifra oficial, con
indicadores de coyuntura de la OCDE. El nowcast reduce el error **30,6 %** frente a
repetir el trimestre anterior — pero solo **6,5 %** frente al promedio histórico, que
es el referente exigente. Ambos números están en el README, junto con el R² de 0,154
y el hecho de que el modelo no anticipó la caída de 2020.

**[Churn y valor de vida del cliente](https://github.com/jpguerreroc/portfolio-data-analytics/tree/main/churn-supervivencia)**
Análisis de supervivencia sobre 7.043 clientes. El contrato mes a mes cancela al
**42,7 %** contra **2,8 %** del contrato a dos años, con cuota mensual casi idéntica.
Estimador de Kaplan-Meier implementado a mano y validado contra `lifelines`.

**[Buscador automático de vacantes](https://github.com/jpguerreroc/portfolio-data-analytics/tree/main/buscador-vacantes)**
Automatiza el descubrimiento de vacantes en varias APIs públicas y documenta el
comportamiento real de cada una, incluidas las que fallan en silencio.

### Herramientas

`Python` · `pandas` · `numpy` · `statsmodels` · `SQL` · `Power BI` ·
`Excel / Power Query` · `Git`

**Métodos:** series de tiempo, VAR/VECM, pruebas de cointegración (Engle-Granger,
Johansen), causalidad de Granger, modelos de regresión, análisis de supervivencia.

**Estadística oficial:** balanza de pagos (MBP6), OCDE Benchmark Definition (BD4),
inversión extranjera directa, cuentas internacionales.

### Cómo trabajo

- El hallazgo va primero, con número.
- Las limitaciones se declaran. Un resultado que no sobrevive al escrutinio es un
  hallazgo, no un fracaso que esconder.
- Datos públicos, con descarga reproducible desde el propio código.

📍 Costa Rica · Español nativo, inglés C1
[LinkedIn](https://linkedin.com/in/jpguerreroc) · guerrerochavesjosepablo@gmail.com
