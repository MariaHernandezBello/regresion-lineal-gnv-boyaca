# Regresión Lineal para el Análisis del Volumen de GNV en Boyacá

## Descripción

Este proyecto desarrolla un modelo de Regresión Lineal para analizar y estimar la cantidad de Gas Natural Vehicular (GNV) suministrado por las estaciones de servicio del departamento de Boyacá, Colombia.

## Fuente de datos

Los datos fueron obtenidos del portal de Datos Abiertos de Colombia.

Conjunto de datos:

Análisis de las ventas de gas natural comprimido vehicular - Departamento de Boyacá.

## Datos

El conjunto de datos contiene 5.316 registros y 15 variables correspondientes a información de ventas, vehículos atendidos, estaciones activas y volumen de GNV suministrado.

## Variable objetivo

- CANTIDAD VOLUMEN SUMINISTRADO

## Variables predictoras

- VEHICULOS ATENDIDOS
- EDS ACTIVAS
- MES VENTA

## Metodología

El proyecto incluye:

1. Recolección de datos.
2. Limpieza y preparación.
3. Análisis exploratorio de datos.
4. Análisis de correlaciones.
5. Identificación de valores potencialmente atípicos.
6. División de los datos en entrenamiento y prueba.
7. Construcción de modelos de Regresión Lineal.
8. Evaluación mediante MAE, MSE, RMSE y R².
9. Análisis de residuos y validación de supuestos.

## Resultados

El modelo final obtuvo:

- MAE: 694,86
- MSE: 1.343.747,98
- RMSE: 1.159,20
- R²: 0,5627

## Requisitos

- Python 3.10 o superior
- pandas
- numpy
- scikit-learn
- matplotlib
- statsmodels

## Ejecución

Instalar las dependencias:

```bash
pip install -r requirements.txt