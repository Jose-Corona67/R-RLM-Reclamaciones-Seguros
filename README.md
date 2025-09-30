# R-RLM-Reclamaciones-Seguros

## Resumen

Proyecto final de Econometría I que desarrolla y valida múltiples modelos econométricos para predecir reclamaciones de seguros. Incluye análisis exhaustivo de especificación, diagnóstico de residuos y comparación de modelos.

## Obetivos

- Modelizar reclamaciones de seguros usando variables actuariales
- Validar supuestos econométricos en cada modelo
- Identificar el modelo óptimo mediante criterios de información
- Diagnosticar problemas de especificación y multicolinealidad

## Modelos Desarrollados

### Modelo 1: Lineal Completo
- 18 variables predictoras
- Problemas de sobreajuste (R² = 1)
- Autocorrelación y no normalidad

### Modelo 2: Con Transformaciones
- Variables: X7, X15, sqrt(X16), sqrt(X17), I(X11²), X10
- Sin autocorrelación
- VIF dentro de rangos aceptables

### Modelo 3: Formas No Lineales
- Interacciones y transformaciones
- Problemas de heterocedasticidad
- Especificación incorrecta

### Modelo 4: Log-Lineal Optimizado
- log(Y) ~ X3 + X4 + X6 + X15 + X16 - 1
- Mejor desempeño en AIC/BIC
- Especificación más robusta

## Requisitos

- R
- RStudio
- Librerías mencionadas en el archivo

## Autores

Chantres Arrieta Nikole
Corona López José Luis

