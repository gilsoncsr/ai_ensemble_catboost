# 📊 Company Risk Analysis and Classification

This project aims to perform exploratory data analysis (EDA), predictive modeling, and model interpretation to predict credit, compliance, and market risks of companies based on a dataset.

## 📁 Project Structure

- **`datasets/companies_profile.csv`**: File containing company profiles.
- **Python Notebook**: Contains all steps of the process, from exploratory analysis to model interpretability.

## ⚙️ Technologies Used

- **Language**: Python
- **Main Libraries**:
  - Data analysis: `pandas`, `numpy`, `scipy`
  - Visualization: `plotly`, `matplotlib`
  - Machine Learning: `scikit-learn`, `catboost`
  - Interpretability: `shap`
  - Interactive widgets: `ipywidgets`
  - Runtime environment: `ipykernel`, `nbformat`

## 🔍 Project Steps

### 1. Exploratory Data Analysis (EDA)

- Descriptive statistics and distribution analysis of numerical and categorical variables.
- Visualization with histograms, boxplots, correlation heatmaps, and interactive charts.
- Statistical tests (ANOVA, t-test) to investigate significant relationships between variables and targets.

### 2. Data Preparation

- Separation of independent variables (features) and targets.
- Splitting the dataset into training and testing sets.

### 3. Model Training

- Use of **CatBoostClassifier** with the **OneVsRest** strategy to independently predict multiple types of risk.
- Hyperparameter tuning and direct handling of categorical variables by CatBoost.

### 4. Model Evaluation

- Metrics used:
  - **Classification Report**
  - **Confusion Matrix**
  - **Log Loss**
- Analysis of results by type of risk.

### 5. Interpretability

- Visualization of feature importance for each risk model.
- Decision tree plots to understand the model.
- Use of SHAP to explain model decisions with both global and individual plots.

## 📈 Results

The model provides relevant insights into the main factors associated with company risks and delivers solid predictive performance across multiple evaluation metrics.

## 🛠️ How to Run

1. Clone the repository:

2. Install dependencies using `pipenv`:

   ```bash
   pipenv install
   ```

3. Start the environment:

   ```bash
   pipenv shell
   ```

4. Run the notebook in Jupyter:
   ```bash
   jupyter notebook
   ```

## 📌 Requirements

- Python 3.8+
- Pipenv (or use `pip install` directly)
- Jupyter Notebook or VS Code with Jupyter extension

---

# 📊 Análisis y Clasificación de Riesgos Empresariales

Este proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA), modelado predictivo e interpretación de modelos para predecir los riesgos crediticios, de cumplimiento y de mercado de las empresas a partir de un conjunto de datos.

## 📁 Estructura del Proyecto

- **`datasets/companies_profile.csv`**: Archivo que contiene los perfiles de las empresas.
- **Notebook en Python**: Contiene todas las etapas del proceso, desde el análisis exploratorio hasta la interpretabilidad de los modelos.

## ⚙️ Tecnologías Utilizadas

- **Lenguaje**: Python
- **Bibliotecas Principales**:
  - Análisis de datos: `pandas`, `numpy`, `scipy`
  - Visualización: `plotly`, `matplotlib`
  - Aprendizaje automático: `scikit-learn`, `catboost`
  - Interpretabilidad: `shap`
  - Widgets interactivos: `ipywidgets`
  - Entorno de ejecución: `ipykernel`, `nbformat`

## 🔍 Etapas del Proyecto

### 1. Análisis Exploratorio de Datos (EDA)

- Estadísticas descriptivas y análisis de distribución de variables numéricas y categóricas.
- Visualización con histogramas, diagramas de caja, mapas de calor de correlación y gráficos interactivos.
- Pruebas estadísticas (ANOVA, t-test) para investigar relaciones significativas entre variables y objetivos.

### 2. Preparación de los Datos

- Separación de las variables independientes (features) y los objetivos (targets).
- División del conjunto de datos en conjuntos de entrenamiento y prueba.

### 3. Entrenamiento de Modelos

- Uso del **CatBoostClassifier** con la estrategia **OneVsRest** para predecir múltiples tipos de riesgo de forma independiente.
- Ajuste de hiperparámetros y manejo directo de variables categóricas por parte de CatBoost.

### 4. Evaluación de Modelos

- Métricas utilizadas:
  - **Informe de Clasificación**
  - **Matriz de Confusión**
  - **Log Loss**
- Análisis de resultados por tipo de riesgo.

### 5. Interpretabilidad

- Visualización de la importancia de las características para cada modelo de riesgo.
- Gráficos de árboles de decisión para entender el modelo.
- Uso de SHAP para explicar las decisiones de los modelos con gráficos globales e individuales.

## 📈 Resultados

El modelo proporciona información relevante sobre los principales factores asociados a los riesgos empresariales y ofrece un buen rendimiento predictivo en múltiples métricas de evaluación.

## 🛠️ Cómo Ejecutar

1. Clona el repositorio:

2. Instala las dependencias con `pipenv`:

   ```bash
   pipenv install
   ```

3. Inicia el entorno:

   ```bash
   pipenv shell
   ```

4. Ejecuta el notebook en Jupyter:
   ```bash
   jupyter notebook
   ```

## 📌 Requisitos

- Python 3.8+
- Pipenv (o usar `pip install` directamente)
- Jupyter Notebook o VS Code con la extensión de Jupyter

---

# 📊 Análise e Classificação de Risco de Empresas

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA), modelagem preditiva e interpretação de modelos para prever os riscos de crédito, compliance e mercado de empresas a partir de um conjunto de dados.

## 📁 Estrutura do Projeto

- **`datasets/companies_profile.csv`**: Arquivo contendo o perfil das empresas.
- **Notebook Python**: Contém todas as etapas do processo, desde a análise exploratória até a interpretabilidade dos modelos.

## ⚙️ Tecnologias Utilizadas

- **Linguagem**: Python
- **Bibliotecas Principais**:
  - Análise de dados: `pandas`, `numpy`, `scipy`
  - Visualização: `plotly`, `matplotlib`
  - Machine Learning: `scikit-learn`, `catboost`
  - Interpretabilidade: `shap`
  - Widgets interativos: `ipywidgets`
  - Ambiente de execução: `ipykernel`, `nbformat`

## 🔍 Etapas do Projeto

### 1. Análise Exploratória dos Dados (EDA)

- Estatísticas descritivas e análise de distribuição das variáveis numéricas e categóricas.
- Visualização com histogramas, boxplots, heatmaps de correlação e gráficos interativos.
- Testes estatísticos (ANOVA, t-test) para investigar relações significativas entre variáveis e os alvos.

### 2. Preparação dos Dados

- Separação das variáveis independentes (features) e dos alvos (targets).
- Divisão dos dados em conjuntos de treino e teste.

### 3. Treinamento dos Modelos

- Utilização do modelo **CatBoostClassifier** com a estratégia **OneVsRest** para prever múltiplos riscos de forma independente.
- Ajuste dos hiperparâmetros e tratamento de variáveis categóricas diretamente pelo CatBoost.

### 4. Avaliação dos Modelos

- Métricas utilizadas:
  - **Classification Report**
  - **Confusion Matrix**
  - **Log Loss**
- Análise dos resultados por tipo de risco.

### 5. Interpretabilidade

- Visualização da importância das features para cada modelo de risco.
- Gráficos de árvore de decisão para entendimento do modelo.
- Utilização do SHAP para explicar as decisões dos modelos com gráficos globais e individuais.

## 📈 Resultados

O modelo apresenta insights relevantes sobre os principais fatores associados aos riscos das empresas, além de entregar uma boa performance de predição com múltiplas métricas de avaliação.

## 🛠️ Como Executar

1. Clone o repositório:

2. Instale as dependências com `pipenv`:

   ```bash
   pipenv install
   ```

3. Inicie o ambiente:

   ```bash
   pipenv shell
   ```

4. Execute o notebook no Jupyter:
   ```bash
   jupyter notebook
   ```

## 📌 Requisitos

- Python 3.8+
- Pipenv (ou use `pip install` diretamente)
- Jupyter Notebook ou VS Code com extensão Jupyter
