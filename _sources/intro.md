# Introducción a Predicción de Series de Tiempo

El presente informe detalla el análisis sobre la predicción de serie de tiempo de la criptomoneda Bitcoin utilizando técnicas de modelado ARIMA para predecir el precio de Bitcoin en horizontes de 7, 14, 21 y 28 días. Se empleará la API de `Yahoo Finance` para obtener la serie de tiempo. El análisis se dividirá en varias etapas:

* Obtención de Datos (Series de tiempo) y Visualización.

* Modelado ARIMA con Rolling Forecast.

* Modelado ARIMA sin Rolling Forecast.

* Evaluación del Rendimiento y Comparación de Modelos con base a las siguiente métricas: `MAPE`, `MAE`, `RMSE`, `MSE`, `R2`.

* Selección de Modelo Óptimo con Criterios: `el criterio de inferencia Bayesiana (BIC)` y `el criterio de información de Hannan–Quinn (HQIC)`.

```{tableofcontents}
```
