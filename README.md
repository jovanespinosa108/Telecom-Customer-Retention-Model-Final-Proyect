# Telecom-Customer-Retention-Model-Final-Proyect
Customer churn rate forecast for customer retention and promotions

# Customer Churn Prediction for Interconnect Telecom
*(Pronóstico de Cancelación de Clientes para Interconnect Telecomunicaciones)*

## 📋 Project Overview / Descripción del Proyecto
This project aims to **predict customer churn (cancellation)** for the telecom company **Interconnect**.  
By identifying customers at risk of leaving, the marketing team can offer promotions and special plans to improve retention.

Este proyecto busca **predecir la cancelación de clientes (churn)** para la empresa de telecomunicaciones **Interconnect**.  
El objetivo es detectar clientes propensos a cancelar su servicio para que el equipo de marketing pueda ofrecerles promociones y planes especiales.

---

## 📂 Dataset / Conjunto de Datos
The dataset consists of four CSV files provided by Interconnect:

- `contract.csv` – Contract details (type, start/end dates, payment method).  
- `personal.csv` – Customer personal information.  
- `internet.csv` – Internet service details.  
- `phone.csv` – Phone service details.  

El conjunto de datos incluye cuatro archivos CSV:

- `contract.csv` – Detalles del contrato (tipo, fechas, método de pago).  
- `personal.csv` – Datos personales del cliente.  
- `internet.csv` – Información sobre los servicios de Internet.  
- `phone.csv` – Información sobre los servicios telefónicos.

All files share a common key: **`customerID`**.  
Todos los archivos se vinculan mediante la columna **`customerID`**.

---

## 🛠️ Project Workflow / Flujo del Proyecto
1. **Data Preparation & Cleaning / Preparación y Limpieza de Datos**  
   - Merging datasets, handling missing values, feature engineering.

2. **Exploratory Data Analysis (EDA) / Análisis Exploratorio de Datos**  
   - Understanding churn patterns, class balance check, visualizations.

3. **Modeling / Modelado**  
   - Training baseline and ML models (Dummy, Logistic Regression, Random Forest, Gradient Boosting).

4. **Evaluation / Evaluación**  
   - Comparing models using **F1-score (≥0.75 target), ROC-AUC, accuracy, recall**.  
   - Monitoring overfitting (train vs. test performance).

5. **Insights & Recommendations / Conclusiones y Recomendaciones**  
   - Highlighting key churn drivers and next steps for retention strategy.

---

## 📈 Key Features / Características Clave
- Focused on **binary classification (Churn: Yes/No)**.  
- Handles **class imbalance** with resampling techniques.  
- Uses **baseline model (DummyClassifier)** for sanity check.  
- Provides **visualizations** and **insights** for business decisions.  

---

## 📊 Tools & Technologies / Herramientas y Tecnologías
- **Python 3.x**  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, `lightgbm`, `graphviz`  

---

## 🚀 Results / Resultados
- Baseline with DummyClassifier.  
- Best-performing model achieved **F1-score ≥ 0.75** on test set.  
- Insights on key churn factors (e.g., contract type, tenure, payment method).

---

## 📜 License / Licencia
This project is for educational purposes and does not include real customer data.  
Este proyecto es con fines educativos y no incluye datos reales de clientes.
