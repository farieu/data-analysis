# 📚 Projeto GoodReads - Aprendizado Supervisionado

Repositório do projeto de análise e modelagem de dados de um dataset do GoodReads, englobando aspectos desde a exploração até implementação de algoritmos de máquina supervisionados para prever se o livro terá uma boa ou má avaliação com base em suas características.

## 🎯 Objetivos do Projeto
- Utilizar bibliotecas de Data Science (`pandas, numpy, scikit-learn, matplotlib, seaborn`);
-  Implementação de algoritmos de Machine Learning (`Regressão, RandomForest, ADABoostingRegressor`);

## 🎲 Base GoodReads no Kaggle
A base de dados que foi utilizada neste projeto pode ser acessada através do [Kaggle](https://www.kaggle.com/datasets/mdhamani/goodreads-books-100k)


## 📂 Estrutura das Branches
A estruturação do projeto é feita através de branches exclusivas para cada feature, contendo um notebook linkado ao Google Collab, e após o Pull Request, são colocadas na main em pastas individuais para facilitar o entendimento.

1. **`LimpezaDataset:`** consiste no trabamento dos dados para garantir que esteja livre de dados ausentes e pronto para análise exploratória.

2. **`AnaliseExploratoria:`** análise inicial dos dados, gerando visualizações e insights preliminares.

3. **`SelecaoFeatures:`** plot da matriz de correlação, seleção das características mais relevantes e codificação de variáveis categóricas/númericas para treino de modelos.

4. **`TreinamentoModelo:`** aplicação do aprendizado supervisionado de Regressão Logística.

5. **`AvaliacaoModeloRL:`** avaliação do modelo treinado e análise descritiva de resultados.

6. **`Pipeline:`** construção de um pipeline para pré-processamento do dataset.

7. **`OutrosModelos:`** exploração de outras técnicas de aprendizado além da regressão.