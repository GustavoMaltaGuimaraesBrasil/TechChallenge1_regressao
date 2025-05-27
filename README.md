# 🏥 Previsão de Despesas Médicas com IA — Tech Challenge 1 (FIAP)

## 📚 Pós-graduação em Inteligência Artificial para Devs — FIAP

---

## 🔍 Descrição do Projeto

Este projeto foi desenvolvido como parte do **Tech Challenge 1** da pós-graduação em **Inteligência Artificial para Desenvolvedores** na **FIAP**.

O objetivo é construir um modelo de **regressão supervisionada** capaz de prever os custos médicos anuais de indivíduos, utilizando informações demográficas e comportamentais.

---

## 📊 Dataset

- **Nome:** [Medical Cost Personal Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **Fonte:** Kaggle
- **Descrição:** O conjunto de dados contém informações sobre:
  - Idade (`age`)
  - Sexo (`sex`)
  - Índice de Massa Corporal (`bmi`)
  - Número de filhos (`children`)
  - Fumante (`smoker`)
  - Região (`region`)
  - Despesas médicas anuais (`charges`) — **variável alvo**

---

## 🚀 Resultados

Após análise exploratória, tratamento dos dados e experimentação de modelos, o algoritmo que apresentou melhor desempenho foi o **Gradient Boosting Regressor**, alcançando os seguintes resultados:

- 📈 **R² (Coeficiente de Determinação):** `0.8707`
- 🧮 **MSE (Mean Squared Error):** `18.956.450`

> 🎯 O modelo consegue explicar aproximadamente **87% da variabilidade** nos custos médicos, indicando uma boa capacidade preditiva.

---
