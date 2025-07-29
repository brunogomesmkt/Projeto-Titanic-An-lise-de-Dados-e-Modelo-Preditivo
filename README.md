# 🚢 Projeto Titanic - Análise de Dados e Modelo Preditivo

> Uma análise completa do clássico dataset do Titanic, combinando estatísticas, visualizações e machine learning para prever quem sobreviveu ao naufrágio mais famoso da história.

## 🎯 Objetivo

O projeto tem como foco responder à pergunta: **quais fatores influenciaram a sobrevivência dos passageiros do Titanic?** A análise combina exploração visual com modelagem preditiva para obter respostas e prever novos casos.

## 📦 Sobre o Dataset

* Fonte: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)
* Dados incluem informações como: nome, sexo, idade, classe (1ª, 2ª, 3ª), tarifa paga, número de irmãos/cônjuges e pais/filhos a bordo, entre outros.

## 🔍 Etapas da Análise

1. **Importação e limpeza dos dados**

   * Tratamento de valores ausentes (especialmente em `Age` e `Embarked`)
   * Conversão de variáveis categóricas para numéricas

2. **Análise exploratória (EDA)**

   * Distribuição de sobreviventes por sexo, classe e idade
   * Visualizações com Seaborn (barplots, countplots, heatmaps)
   * Cálculo de correlações

3. **Modelagem preditiva**

   * Criação de variáveis dummy
   * Divisão em treino e teste
   * Treinamento com `RandomForestClassifier`
   * Avaliação da acurácia do modelo

## 📊 Principais insights

* Passageiros da **1ª classe** e **do sexo feminino** tiveram maior chance de sobreviver.
* Crianças também apresentaram taxas maiores de sobrevivência.
* O modelo Random Forest alcançou boa performance na previsão da variável `Survived`.

## 🧠 Tecnologias utilizadas

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

## 🚀 Como executar

1. Clone o repositório
2. Instale os pacotes necessários (`pip install -r requirements.txt`)
3. Execute o notebook `Projeto_Titanic_Análise_de_Dados_e_Modelo_Preditivo.ipynb`

## 📌 Possíveis melhorias

* Testar modelos como XGBoost ou SVM
* Otimização de hiperparâmetros com GridSearchCV
* Adicionar validação cruzada para robustez do modelo

