# 🌊 Titanic - Predição com Árvore de Decisão 🌳

Este repositório apresenta um modelo de **Machine Learning** baseado em **Árvores de Decisão** para prever a sobrevivência dos passageiros do Titanic.

---

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Lu96iCZDE_aRB3Kx5hwLdoHyPShYnueq#scrollTo=cfe51bca)


## 📌 Visão Geral
Este projeto realiza:

### 📊 **Preparação dos Dados**
✔ Carregamento do conjunto de dados do Titanic 📂  
✔ Tratamento de valores ausentes  
✔ Conversão de variáveis categóricas para formato numérico 🔄  
✔ Seleção das features mais relevantes para a previsão 🎯  
✔ Divisão dos dados em conjunto de treino (80%) e teste (20%) 📚  

### 🏋️ **Treinamento do Modelo**
✔ Construção de uma árvore de decisão com `max_depth=20` 🌳  
✔ Ajuste do modelo com os dados de treino 📉  
✔ Cálculo da acurácia nos dados de treino 🎯  

### 📈 **Validação e Teste**
✔ Avaliação do modelo com dados de teste 📊  
✔ Previsão da sobrevivência dos passageiros de teste 🚢  
✔ Medida de desempenho usando `accuracy_score` 📏  

### 🌲 **Visualização da Árvore de Decisão**
✔ Gera e exibe um gráfico representando a estrutura da árvore 🌿  

---

## 🛠 Tecnologias Utilizadas
- **Python** 🐍
- **Pandas** 📊
- **Scikit-Learn** 🤖
- **Matplotlib** 📉
- **Seaborn** 🎨

---

## 🚀 Como Executar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/adairjuniordata/titanic-decision-tree.git
   ```

2. **Instale as dependências**:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
   ```

3. **Execute o script**:
   ```bash
   python titanic_decision.py
   ```

---

## 📌 Resumo do Modelo  
📌 Acurácia no teste: **82.02%**  
 

## 🔍 Melhorias Futuras
🔹 Ajustar hiperparâmetros (`min_samples_split`, `min_samples_leaf`) para reduzir overfitting.  
🔹 Explorar outros algoritmos, como **Random Forest** ou **XGBoost**, para possível ganho de desempenho.  

---

