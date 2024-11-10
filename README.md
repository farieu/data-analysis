# Branch - Análise Exploratória

A análise exploratória inicial fornece uma visão sobre a estrutura e as tendências do dataset, o que ajudará na seleção de variáveis relevantes e na preparação para etapas futuras de modelagem.

Esta branch documenta o processo inicial de análise exploratória do dataset **Goodreads Books 100k**, fornecendo insights preliminares sobre a distribuição e características dos dados. 

## Artefatos 📄

- **Notebook de Análise Exploratória**: Dispõe de visualizações e estatísticas descritivas para compreender melhor as distribuições e relações entre as variáveis do dataset.

## Principais Descobertas 📊

1. **Visualizações Iniciais**: Inclui gráficos de barras, histogramas e gráficos de dispersão que revelam informações como:
   - Distribuição das avaliações (`rating`) entre os livros.
   - Contagem de livros por gênero, destacando os gêneros mais populares.
   - Distribuição dos formatos de livros.
   - Relação entre a quantidade de páginas e a média de avaliação dos livros.

   - Popularidade de autores, de livros melhores avaliados, piores notas de livros.
2. **Identificação de Ruídos**: Durante a análise, percebeu-se que a inserção de valores "Unknown" para preencher dados ausentes em certas colunas (como `genre` e `bookformat`) poderia introduzir ruídos e impactar a precisão dos modelos futuros. Para resolver isso, foi gerada uma nova versão do dataset sem esses valores preenchidos.

3. **Dataset Limpo e Documentação Complementar**: O processo de limpeza de dados está documentado na branch **LimpezaDataset**, onde foi commitado um notebook que não contém e não gera dataset imputado.
