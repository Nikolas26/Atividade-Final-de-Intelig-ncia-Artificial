🧬 Atividade Final de Inteligência Artificial
Classificação Supervisionada – Titanic Dataset

Este repositório contém a atividade final da disciplina de Inteligência Artificial, cuja proposta é desenvolver, treinar e comparar três modelos de classificação supervisionada para prever a sobrevivência de passageiros do Titanic utilizando o dataset Titanic.

🎯 Objetivo

Aplicar três modelos de machine learning supervisionado:

XGBoost

SVM (Support Vector Machine)

Random Forest

O objetivo é comparar o desempenho, custo computacional e interpretabilidade de cada modelo.

🧩 Descrição da Tarefa
📌 Dataset

Utilizar o dataset Titanic, obtido via Kaggle ou pelo seaborn:
seaborn.load_dataset("titanic")

🎯 Variável-alvo

Survived

0 = não sobreviveu

1 = sobreviveu

🔧 Variáveis sugeridas

Pclass

Sex

Age

Fare

SibSp

Parch

Embarked

🔄 Pré-processamento dos Dados

As etapas de preparação no notebook incluem:

Tratamento de valores ausentes (Age, Embarked etc.)

Codificação de variáveis categóricas (One-Hot Encoding)

Padronização de variáveis numéricas (StandardScaler)

Construção de pipelines para processamento organizado

Divisão estratificada entre treino e teste

🤖 Modelos Treinados

Os seguintes algoritmos foram implementados e avaliados:

1. XGBoost Classifier

Modelo baseado em boosting

Alta performance e boa capacidade de generalização

2. Support Vector Machine (SVM)

Usado com kernel apropriado para dados tabulares

Requer normalização (incluída no pipeline)

3. Random Forest

Ensemble baseado em árvores de decisão

Robusto a valores faltantes e variáveis ruidosas

📊 Métricas Avaliadas

Os modelos foram comparados utilizando:

🔑 Métrica Principal

ROC-AUC

📈 Métricas Secundárias

Acurácia

F1-Score

Matriz de Confusão

Curvas ROC

Curvas Precision-Recall

Todas as curvas e métricas foram geradas no notebook.

📉 Resultados

O notebook apresenta:

Comparação tabular das métricas dos três modelos

Análise gráfica das curvas (ROC e PR)

Discussão sobre overfitting, sensibilidade e interpretabilidade

🗂 Estrutura do Notebook

O notebook segue esta organização:

Importação de bibliotecas

Carga e exploração do dataset

Pré-processamento com pipelines

Treinamento dos modelos

Avaliação e comparação

Visualização de métricas

Conclusões

📌 Conclusão

O projeto explora e compara três abordagens supervisionadas para classificação, destacando:

Diferenças de desempenho

Impacto do pré-processamento

Complexidade computacional

Capacidade de generalização
