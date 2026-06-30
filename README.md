# 📊 Predicción del Riesgo Crediticio mediante Machine Learning

## 📌 Descripción del Proyecto

Este proyecto desarrolla una solución basada en Machine Learning para predecir el riesgo de incumplimiento de clientes que solicitan un préstamo.

Se utilizó el algoritmo *Random Forest* para clasificar a los clientes como *Cumplidores* o *Incumplidores*, permitiendo apoyar la toma de decisiones en entidades financieras.

Como complemento, se desarrolló un *Dashboard Interactivo en Looker Studio*, donde se visualizan los resultados del modelo mediante indicadores, gráficos y filtros dinámicos.

---

# 🎯 Objetivo

Desarrollar un modelo de Machine Learning capaz de predecir el riesgo crediticio de un cliente antes de aprobar un préstamo, con el fin de reducir el riesgo financiero y mejorar el proceso de evaluación crediticia.

---

# 📂 Dataset

*Fuente:*

Credit Risk Dataset (Kaggle)

El conjunto de datos contiene información de *32 581 clientes*, incluyendo variables financieras y crediticias como:

- Edad
- Ingreso anual
- Tipo de vivienda
- Años de experiencia laboral
- Monto del préstamo
- Tasa de interés
- Motivo del préstamo
- Calificación crediticia
- Historial de incumplimiento
- Antigüedad del historial crediticio

Variable objetivo:

*Loan Status*

- 0 → Cliente Cumplidor
- 1 → Cliente Incumplidor

---

# ⚙️ Tecnologías Utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-Learn
- Imbalanced-Learn (SMOTE)
- Random Forest
- Google Sheets
- Looker Studio

---

# 🔄 Metodología

El desarrollo del proyecto siguió las siguientes etapas:

1. Carga del dataset.
2. Limpieza y preprocesamiento de datos.
3. Codificación de variables categóricas.
4. Análisis de correlación y eliminación de variables redundantes.
5. División de datos en entrenamiento y prueba.
6. Balanceo de clases mediante SMOTE.
7. Entrenamiento del modelo Random Forest.
8. Evaluación mediante métricas de clasificación.
9. Generación del dataset final con las predicciones.
10. Construcción del Dashboard en Looker Studio.

---

# 🤖 Modelo de Machine Learning

Modelo seleccionado:

*Random Forest*

Se eligió este algoritmo por presentar el mejor rendimiento durante las pruebas realizadas.

---

# 📈 Resultados del Modelo

| Métrica | Resultado |
|----------|-----------|
| Accuracy | 92% |
| Precision | 94% |
| Recall | 70% |
| F1 Score | 80% |

Estos resultados demuestran un buen desempeño del modelo para clasificar clientes con riesgo de incumplimiento.

---

# 📊 Dashboard

El Dashboard desarrollado en Looker Studio permite visualizar de manera interactiva:

- Total de clientes evaluados.
- Clientes cumplidores.
- Clientes incumplidores.
- Tasa de incumplimiento.
- Riesgo por motivo del préstamo.
- Riesgo por calificación crediticia.
- Impacto del historial crediticio.
- Tabla detallada de clientes evaluados.

Además, cuenta con filtros dinámicos que permiten analizar la información en tiempo real.

---

# 💼 Valor para la Empresa

La solución permite:

- Reducir el riesgo de otorgar préstamos a clientes con alta probabilidad de incumplimiento.
- Agilizar el proceso de evaluación crediticia.
- Apoyar la toma de decisiones mediante análisis basado en datos.
- Visualizar indicadores clave mediante un Dashboard interactivo.
- Optimizar el proceso de evaluación de préstamos.

---

# 📁 Estructura del Proyecto


Proyecto-Prediccion-Riesgo-Crediticio
│
├── data/
│   ├── credit_risk_dataset.csv
│   └── dataset_final.csv
│
├── notebooks/
│   └── Proyecto_Credit_Risk.ipynb
│
├── dashboard/
│   └── dashboard.png
│
├── imagenes/
│   ├── matriz_confusion.png
│   ├── correlacion.png
│   └── random_forest.png
│
├── presentacion/
│   └── Proyecto_Integrador.pdf
│
├── README.md
└── requirements.txt

---

Proyecto Integrador — Machine Learning para Predicción del Riesgo Crediticio.
