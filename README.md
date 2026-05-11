# Predicao_ataques_redescorporativas

Este repositório contém o código-fonte e a metodologia utilizados no trabalho “Predição de Ataques em Redes Corporativas Utilizando Técnicas de Aprendizado de Máquina”.

O estudo realiza uma análise comparativa entre os algoritmos Regressão Logística, SVM, KNN, MLP e XGBoost aplicados à detecção de intrusões em redes corporativas, utilizando o conjunto de dados NSL-KDD.

Os modelos foram avaliados com base em métricas de desempenho como acurácia, precisão, recall, F1-score e AUC-ROC, além da utilização de validação cruzada estratificada do tipo 5-fold para análise da capacidade de generalização e estabilidade dos algoritmos.

O conjunto de dados utilizado foi o NSL-KDD, amplamente empregado em pesquisas relacionadas à segurança de redes e sistemas de detecção de intrusão.

Todo o pipeline foi desenvolvido em Python, utilizando bibliotecas como scikit-learn, xgboost, tensorflow, keras, pandas, numpy, matplotlib e seaborn.

## Algoritmos Avaliados

- Regressão Logística
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Multilayer Perceptron (MLP)
- XGBoost

## Métricas Utilizadas

- Acurácia
- Precisão
- Recall
- F1-Score
- AUC-ROC
- Validação Cruzada 5-Fold

## Bibliotecas Utilizadas

- Python
- Scikit-learn
- XGBoost
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Objetivo

Avaliar e comparar diferentes técnicas de Aprendizado de Máquina na identificação de tráfego malicioso em redes corporativas, analisando desempenho, capacidade de generalização e robustez dos modelos.

## Dataset

- NSL-KDD
- Fonte: https://www.kaggle.com/datasets/hassan06/nslkdd/data
