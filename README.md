# Español
# Predicción de Precios de Autos usando Regresión Lineal

## Descripción del Proyecto

Este proyecto desarrolla un modelo simple de **Regresión Lineal** para estimar el precio de venta de vehículos usados a partir de algunas características del automóvil:

- Antigüedad del vehículo
- Kilometraje
- Número de puertas

El objetivo es evaluar el desempeño del modelo utilizando métricas estándar de regresión y visualizar la relación entre los precios reales y los precios predichos.

Este proyecto fue desarrollado como parte del curso **Fundamentos de Ciencia de Datos**.

---

## Conjunto de Datos

El conjunto de datos contiene información básica de vehículos usados:

| Variable | Descripción |
|------|-------------|
| Antiguedad | Edad del vehículo en años |
| Kilometraje | Distancia recorrida en kilómetros |
| Puertas | Número de puertas del vehículo |
| Precio | Precio de venta del vehículo en USD |

Debido al tamaño reducido del dataset (4 observaciones), el análisis tiene principalmente un propósito **educativo y demostrativo**.

---

## Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Metodología

El flujo de trabajo seguido en el proyecto fue el siguiente:

1. Creación y preparación del conjunto de datos
2. Definición de variables independientes (features) y variable objetivo
3. División de datos en entrenamiento y prueba (80% / 20%)
4. Entrenamiento de un modelo de regresión lineal
5. Generación de predicciones
6. Evaluación del modelo mediante métricas de regresión
7. Comparación visual entre precios reales y predichos

---

## Métricas de Evaluación del Modelo

El modelo fue evaluado utilizando las siguientes métricas:

- **MAE (Error Absoluto Medio)**
- **MSE (Error Cuadrático Medio)**
- **RMSE (Raíz del Error Cuadrático Medio)**
- **R² (Coeficiente de determinación)**

Debido al tamaño extremadamente pequeño del conjunto de datos, la métrica **R² no pudo calcularse para el conjunto de prueba**.

---

## Visualización

El proyecto incluye un gráfico de dispersión que compara **precios reales vs precios predichos**, permitiendo observar visualmente el error de predicción del modelo.

---

## Estructura del Proyecto


# English

# Car Price Prediction using Linear Regression

## Project Overview

This project develops a simple **Linear Regression model** to estimate the selling price of used cars based on key vehicle characteristics:

- Vehicle age
- Mileage
- Number of doors

The objective is to evaluate the model's performance using standard regression metrics and visualize the relationship between real and predicted prices.

This project was developed as part of the **Fundamentals of Data Science** course.

---

## Dataset

The dataset contains information about used vehicles including:

| Feature | Description |
|------|-------------|
| Antiguedad | Age of the vehicle (years) |
| Kilometraje | Total distance traveled (km) |
| Puertas | Number of doors |
| Precio | Vehicle selling price (USD) |

Due to the small dataset size (4 observations), the model evaluation serves primarily as an educational exercise.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Methodology

The workflow followed these steps:

1. Data preparation and creation of the dataset
2. Definition of independent variables (features) and target variable
3. Train-test split (80% training / 20% testing)
4. Training a Linear Regression model
5. Generating predictions
6. Evaluating model performance using regression metrics
7. Visual comparison of real vs predicted prices

---

## Model Evaluation Metrics

The model was evaluated using the following metrics:

- **MAE (Mean Absolute Error)**
- **MSE (Mean Squared Error)**
- **RMSE (Root Mean Squared Error)**
- **R² (Coefficient of Determination)**

Due to the extremely small dataset, the R² metric could not be calculated for the test set.

---

## Visualization

The project includes a scatter plot comparing **real prices vs predicted prices**, allowing a visual evaluation of the prediction error.

---

## Project Structure
