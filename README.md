# 🌳 Projeto de Classificação com Árvore de Decisão

Este projeto tem como objetivo aplicar o algoritmo de *Árvore de Decisão* para prever a aprovação de crédito de clientes com base em características pré-definidas. A atividade foi realizada como parte do curso de Análise de Dados.

## 📌 Objetivo

Desenvolver um modelo de Machine Learning supervisionado usando o algoritmo de Árvore de Decisão, treinando e avaliando o desempenho da classificação entre clientes que terão ou não crédito aprovado.

## 🧠 Modelo Utilizado

- *Árvore de Decisão* (DecisionTreeClassifier) da biblioteca sklearn.

## 📊 Etapas do Projeto

1. *Importação e exploração dos dados*
   - Leitura da base de dados.
   - Verificação de valores ausentes.
   - Análise estatística e visual (gráficos, correlações, etc).

2. *Pré-processamento dos dados*
   - Codificação de variáveis categóricas.
   - Separação entre variáveis preditoras (X) e variável alvo (y).
   - Divisão entre dados de treino e teste.

3. *Treinamento do modelo*
   - Utilização de DecisionTreeClassifier.
   - Ajuste aos dados de treino (fit).

4. *Avaliação do modelo*
   - Acurácia e Recall nos dados de treino e teste.
   - Matriz de confusão.
   - Comparação entre desempenho nos conjuntos de treino e teste.

## 🧪 Métricas de Avaliação

- *Acurácia*
- *Recall (macro)*
- *Matriz de Confusão*

Essas métricas ajudaram a verificar o desempenho do modelo e identificar possíveis overfittings.

## 🔍 Principais Insights

- O modelo teve melhor desempenho nos dados de treino do que no teste, indicando um leve overfitting.
- A análise da matriz de confusão demonstrou que o modelo acerta mais as classes majoritárias.
- Ajustes nos hiperparâmetros podem melhorar a generalização.

## 🛠 Tecnologias Utilizadas

- Python
- Pandas
- Numpy
- Scikit-learn
- Matplotlib / Seaborn (para visualizações)

## 📁 Organização do Projeto

```bash
📂 projeto-arvore-decisao
│
├── 📄 README.md
├── 📊 dataset.csv
├── 📓 notebook_decision_tree.ipynb
