# Análisis de Evasión de Clientes (Churn)

## 1. Descripción

Este proyecto realiza un **análisis exploratorio de datos (EDA)** para estudiar la evasión de clientes (churn) en un conjunto de datos del sector telecomunicaciones.
El objetivo principal es **comprender el comportamiento de los clientes** y detectar patrones asociados a la cancelación del servicio.

El análisis se desarrolla en un **notebook de Python**, utilizando técnicas básicas de limpieza, transformación y visualización de datos.

---

## 2. Objetivo

* Analizar la distribución de la evasión de clientes.
* Explorar la relación entre churn y variables categóricas y numéricas.
* Obtener conclusiones iniciales que ayuden a entender qué factores influyen en la evasión.

---

## 3. Estructura del Proyecto

```
churn-project/
│
├── TelecomX.ipynb
├── README.md
```

---

## 4. Herramientas Utilizadas

* Python
* pandas
* numpy
* matplotlib

Instalación de dependencias:

```bash
pip install pandas numpy matplotlib
```

---

## 5. Ejecución

1. Abrir el archivo `churn_analysis.ipynb` en Google Colab o Jupyter Notebook.
2. Ejecutar las celdas en orden para reproducir el análisis.

---

## 6. Análisis Realizado

El notebook incluye:

* Limpieza y preparación de datos.
* Análisis descriptivo de variables numéricas.
* Visualización de la evasión de clientes.
* Análisis de churn por:

  * Género
  * Tipo de contrato
  * Servicio de internet
  * Método de pago
* Comparación de variables numéricas según estado de evasión.

---

## 7. Principales Resultados

* La evasión es mayor en clientes con contratos **mensuales**.
* Los clientes con **menor antigüedad** presentan mayor probabilidad de cancelar.
* Cargos mensuales más altos están asociados a mayores tasas de evasión.
* Algunos métodos de pago muestran una mayor proporción de clientes evadidos.

---

## 8. Conclusión

Este análisis permite obtener una **visión inicial del problema de churn**, identificando patrones relevantes que pueden servir como base para análisis más avanzados o modelos predictivos en etapas posteriores del aprendizaje.


