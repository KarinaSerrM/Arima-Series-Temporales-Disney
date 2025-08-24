# Análisis y modelado AR(p) de series de tiempo de Disney

Este proyecto presenta un análisis y modelado de series temporales para los precios de cierre de Walt Disney Company (DIS), aplicando técnicas estadísticas para seleccionar el mejor modelo AR(p) y evaluar su precisión.

## Objetivos

- Analizar la autocorrelación y autocorrelación parcial de la serie.
- Seleccionar el mejor modelo AR(p) usando criterios AIC y BIC.
- Ajustar el modelo ARIMA y generar predicciones con intervalos de confianza.
- Evaluar la precisión del modelo con RMSE y MAPE.
- Visualizar los resultados de forma clara y estratégica.

## Metodología

1. **Extracción de datos** desde Yahoo Finance (enero a marzo 2023).
2. **División de datos**: 70% entrenamiento, 30% prueba.
3. **Análisis de ACF y PACF** para entender la estructura temporal.
4. **Comparación de modelos AR(0) a AR(6)** con AIC y BIC.
5. **Selección de AR(1)** como modelo óptimo.
6. **Predicción para abril 2023** con intervalos de confianza del 90%.
7. **Evaluación de precisión** con RMSE = 5.26 y MAPE = 5.14%.
8. **Visualización diferenciada** por conjuntos y análisis de residuales.

## Resultados clave

| Métrica        | Valor     |
|----------------|-----------|
| Modelo elegido | AR(1)     |
| RMSE           | 5.26      |
| MAPE           | 5.14%     |
| Tendencia      | Bajista   |
| Precisión      | Alta      |

## Visualización

- Línea azul: conjunto de entrenamiento  
- Línea verde: conjunto de prueba  
- Línea roja: predicción del modelo  
- Zona rosa: intervalo de confianza del 90%

## Tecnologías utilizadas

- Python (Pandas, NumPy, Matplotlib)
- Statsmodels (ARIMA, ACF, PACF)
- Yahoo Finance API
- Warnings

## Conclusión

El modelo AR(1) demuestra una alta capacidad predictiva para los precios de Disney, con una precisión superior al 94%. La visualización clara y el análisis de residuales permiten validar la calidad del ajuste y detectar posibles mejoras futuras.

https://www.linkedin.com/in/karina-serrano-data-science/
