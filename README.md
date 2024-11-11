# 📚 Projeto GoodReads - Análise e Modelagem de Dados

Repositório do projeto de análise e modelagem de dados de uma base de dados do GoodReads! Este projeto visa a exploração, limpeza e modelagem de um dataset de livros do GoodReads para prever a avaliação dos livros com base em suas características.

## 📂 Estrutura das Branches

Este repositório está organizado em diversas branches, cada uma com seu objetivo específico para facilitar o desenvolvimento e a análise das diferentes etapas do projeto. Todas as branches convergem em pastas que estão estruturadas na main, com prefixo [PR].

### 1. `LimpezaDataset` 🧼
Contém os notebooks relacionados à limpeza dos dados. Nessa branch, foi feito o tratamento dos dados para garantir que o dataset estivesse pronto para análise e modelagem.

- **Artefatos**:
  - `tratamento_goodreads.ipynb`
  - `tratamento_goodreads_(sem_imputacao_de_dados).ipynb`

- **Dataset Original**: O dataset bruto está disponível para download neste [link do Kaggle](https://www.kaggle.com/datasets/mdhamani/goodreads-books-100k), pois o tamanho do arquivo excede o limite de 100 MB permitido pelo GitHub.
- **Descrição dos Dados**: Incluí um arquivo `.pdf` detalhando as colunas do dataset, com uma descrição e tipagem dos atributos. Este documento foi elaborado para orientar o processo de limpeza.
- **Dataset Processado**: A versão gerada a partir da limpeza no Google Colab, ajustada (porém, ainda não categorizada numericamente para modelos de classificação e recomendação) também está disponível nesta [link do Google Drive](https://drive.google.com/drive/folders/1Y-O7rOVUjeMTuE6RicUxA82CQJirilco?usp=sharing), pois excede também excede o limite permitido pelo GitHub.

### 2. `AnaliseExploratoria` 📊
Nesta branch, é realizada a etapa de análise exploratória dos dados, gerando visualizações e insights preliminares sobre o dataset.

- **Artefatos**:
  - `eda_goodreads.ipynb`
  - `eda_advanced.ipynb` (visualizações e análises extras)

### 3. `SelecaoFeatures` 🔍
Dedicada a seleção de características mais relevantes para melhorar o desempenho dos modelos de machine learning.

- **Arquivo Principal**:
  - `PreparacaoModelo.ipynb`

### 4. `TreinamentoModelo` 🤖
Branch contendo ao treinamento dos modelos preditivos para prever a avaliação dos livros com base nas features selecionadas.
Branch contendo o treinamento do modelo de Regressão Logística em quatro tipos de parâmetros. O treinamento é para prever a avaliação dos livros com base nas features selecionadas.

- **Arquivo Principal**:
  - `TreinamentoRegressao.ipynb`

### 5. `AvaliacaoModeloRL` 🧪
Contém a avaliação dos modelos treinados, incluindo métricas de desempenho e análise detalhada e discursiva de resultados.

- **Arquivo Principal**:
  - `AvaliacaoModeloRL.ipynb`

### 6. `Pipeline` 🚀
Nesta branch, tento construir o pipeline de execução para automatizar o fluxo de limpeza e codificação do dataset para outros modelos.

- **Arquivo Principal**:
  - `Pipeline.ipynb`

### 7. `AnaliseExploratoria2 ou AE Avançada` 🔎
Essa branch é dedicada a visualizações mais avançadas e plotagens adicionais, complementando as análises iniciais dos dados.

- **Arquivo Principal**:
  - `Pipeline.ipynb`

### 7. `OutrosModelos` 📈
Aqui exploramos outras técnicas de modelagem além da regressão, incluindo Random Forest e ADA Boost, e comparando-as com o modelo de RL.

- **Arquivos Principais**:
  - `ModelosAdicionais(RandomForest).ipynb`
  - `ModelosAdicionais(ADABoost).ipynb`