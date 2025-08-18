# 📊 Predicción de Churn en Telecom X

## 📌 Descripción
Este repositorio contiene un proyecto de **Machine Learning** aplicado a datos de clientes de **Telecom X**, cuyo objetivo principal es **predecir la cancelación de clientes (Churn)**.  

El proyecto aborda todo el flujo de un modelo predictivo: desde la extracción y preparación de datos, hasta el entrenamiento de diferentes algoritmos y la interpretación de resultados.

---

## 📂 Contenido del Notebook
El notebook [`Telecom_X2.ipynb`](Telecom_X2.ipynb) está estructurado en las siguientes secciones:

1. **📌 Extracción**  
   - Carga del dataset inicial.

2. **🔧 Preparación de los datos**  
   - Codificación de variables categóricas (Encoding).  
   - Cálculo de la proporción de clientes que cancelaron.  
   - Análisis de correlación y multicolinealidad.  
   - Balanceo de clases.  
   - Estandarización de características numéricas.  
   - Análisis de la relación entre variables y `Churn`.

3. **🤖 Modelado Predictivo**  
   - **Regresión Logística**.  
   - **Random Forest**.  
   - **XGBoost**.

4. **🔍 Evaluación de los Modelos**  
   - Evaluación en el conjunto de entrenamiento.  
   - Validación cruzada.

5. **📋 Interpretación y Conclusiones**  
   - Importancia de las variables en Regresión Logística.  
   - Importancia de las variables en Random Forest.  
   - Importancia de las variables en XGBoost.  

---

## 📊 Dataset
- Fuente: Dataset ficticio de clientes de **Telecom X**.  
- Observaciones: ~7.000 clientes.  
- Variable objetivo:  
  - `Churn` (1 = Cliente canceló, 0 = Cliente activo).  
- Variables predictoras:  
  - Datos demográficos (género, edad, etc.).  
  - Tiempo como cliente (`tenure`).  
  - Tipo de contrato (`Contract`).  
  - Servicios contratados (`InternetService`, `PhoneService`, etc.).  
  - Cargos (`Charges.Monthly`, `Charges.Total`).  

---

## ⚙️ Requisitos
Para ejecutar este proyecto necesitas tener instalado:

- Python 3.x  
- Librerías:  
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn xgboost

 ## 🚀 Cómo ejecutar el proyecto

1. Clona este repositorio:

```bash
git clone https://github.com/JonathanPuertaG/challenge-telecom-x-parte-2.git
cd challenge-telecom-x-parte-2

2. Abre el notebook en Jupyter o Google Colab:

`jupyter notebook Telecom_X2.ipynb`

3. Ejecuta las celdas paso a paso siguiendo la estructura.

## 📈 Resultados esperados

- Comparación de desempeño entre distintos modelos de clasificación.

- Identificación de las variables más importantes para explicar el Churn.

- Conclusiones que orientan la retención de clientes en la empresa.

# Autor
Jonathan Puerta
