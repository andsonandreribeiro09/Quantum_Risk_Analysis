
# 🧠 Quantum Risk Analysis com Amplitude Estimation

Este projeto demonstra como algoritmos quânticos podem ser utilizados para **análise de risco financeiro**, com foco na estimativa das métricas **Value at Risk (VaR)** e **Conditional Value at Risk (CVaR)**.

## 🚀 Visão Geral

Através da simulação de **Quantum Amplitude Estimation (QAE)**, comparamos o desempenho da abordagem quântica em relação ao tradicional **Método de Monte Carlo**. 

## 🔍 Principais Resultados

- A **estimativa baseada em QAE** apresenta **convergência mais rápida** do que o método clássico de Monte Carlo, mesmo sob simulação.
- A abordagem quântica se mostra promissora para aplicação prática em **gestão de risco de carteiras financeiras**.

## 📊 Métricas Analisadas

- **Value at Risk (VaR)**: risco máximo esperado com determinado nível de confiança.
- **Conditional Value at Risk (CVaR)**: média das perdas que excedem o VaR, mais sensível a eventos extremos.

## ⚠️ Limitações

- O custo computacional das simulações ainda é alto.
- As limitações do **hardware quântico atual** impedem experimentos em larga escala com carteiras complexas.
- A preparação de estados e a construção dos circuitos exigem otimizações adicionais para maior escalabilidade.

## 🛠️ Tecnologias Utilizadas

- [Qiskit](https://qiskit.org/)
- Python 3.11+
- Simuladores quânticos: `Aer` ou `BasicAer`
- Bibliotecas auxiliares: `numpy`, `matplotlib`, `scipy`

## 📁 Estrutura

📦Quantum_Risk_Analysis
┣ 📜 Quantum_Risk_Analysis_Portfolio.ipynb
┣ 📜 README.md
┗ 📜 requirements.txt


Autor: Andson Andre Ribeiro
GitHub: andsonandreribeiro09/Quantum_Risk_Analysis
Licença: MIT
