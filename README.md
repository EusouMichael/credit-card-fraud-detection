# 💳 Credit Card Fraud Detection

> **Machine Learning | Classification | Explainable AI**

Projeto de Machine Learning desenvolvido para estudar a identificação de transações potencialmente fraudulentas em uma base altamente desbalanceada.

## 🎯 Objetivo

Construir e avaliar modelos de classificação capazes de distinguir transações legítimas de transações fraudulentas, considerando as particularidades de um problema de **class imbalance**.

## 🔬 Abordagem

### 1. Exploração dos dados

- Inspeção da estrutura da base
- Verificação de valores ausentes
- Análise da distribuição das classes
- Exploração das variáveis

### 2. Preparação

- Separação entre treino e teste
- Seleção de características
- Tratamento do desbalanceamento das classes

### 3. Modelos

Foram explorados:

- Random Forest Classifier
- XGBoost Classifier

### 4. Avaliação

As métricas consideradas incluem:

- Precision
- Recall
- F1 Score
- Classification Report

Para detecção de fraude, a análise de **Recall e Precision** é especialmente relevante, pois falsos negativos e falsos positivos possuem impactos diferentes no negócio.

### 5. Explainable AI

Foi utilizado **SHAP (SHapley Additive exPlanations)** para interpretar as previsões e investigar a importância das características utilizadas pelos modelos.

## 🛠️ Tecnologias

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- SHAP
- Google Colab

## 📊 Resultado

Os modelos foram avaliados em um cenário de classes altamente desbalanceadas, com foco em identificar transações fraudulentas e compreender os fatores utilizados nas previsões.

> 📌 Este README evita apresentar métricas numéricas que não estão documentadas no repositório. Os resultados quantitativos devem ser adicionados após a consolidação da avaliação final dos modelos.

## 💼 Competências demonstradas

**Machine Learning** · **Classification** · **Imbalanced Data** · **Model Evaluation** · **XGBoost** · **Random Forest** · **Explainable AI** · **SHAP**

## 📌 Sobre

Projeto educacional desenvolvido como parte da evolução prática em **Python, Machine Learning e análise de dados**.
