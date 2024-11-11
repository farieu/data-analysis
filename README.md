# Repositório - Tratamento Dataset

Esta branch documenta o processo de carregamento e limpeza do dataset **Goodreads Books 100k**.

## Artefatos 📄

- **Dataset Original**: O dataset bruto está disponível para download neste [link do Kaggle](https://www.kaggle.com/datasets/mdhamani/goodreads-books-100k), pois o tamanho do arquivo excede o limite de 100 MB permitido pelo GitHub.
- **Descrição dos Dados**: Incluí um arquivo `.pdf` detalhando as colunas do dataset, com uma descrição e tipagem dos atributos. Este documento foi elaborado para orientar o processo de limpeza.
- **Dataset Processado**: A versão gerada a partir da limpeza no Google Colab, ajustada (porém, ainda não categorizada numericamente para modelos de classificação e recomendação) também está disponível nesta [link do Google Drive](https://drive.google.com/drive/folders/1Y-O7rOVUjeMTuE6RicUxA82CQJirilco?usp=sharing), pois excede também excede o limite permitido pelo GitHub.

### Atualização 09/11
O input de dados demonstrou certa dificuldade durante a análise exploratória. Para contornar a situação, foi feito um novo tratamento, gerando um dataset sem esses inputs.

1. O arquivo **tratamento_dataset.ipynb** gera o dataset com imputação de dados ausentes.

2. O arquivo **tratamento_dataset(sem_imputacao_de_dados).ipynb** gera o dataset, com as mesmas colunas do primeiro arquivo, porém com uma quantidade de linhas menor **vide remoção de linhas que possuíam dados ausentes**.
