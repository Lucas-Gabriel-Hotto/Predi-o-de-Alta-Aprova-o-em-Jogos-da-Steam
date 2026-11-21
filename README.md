# Predição de Alta Aprovação em Jogos da Steam

Trabalho final da disciplina de **Programação para Ciência de Dados**, reunindo análise exploratória, preparação dos dados e modelagem preditiva aplicada ao catálogo de jogos da Steam.

## Integrantes

- Lucas Gabriel Hotto
- Marcelo Lutz Brum
- Vinícius Strzelecki

## Objetivo

Investigar se características cadastrais de um jogo permitem prever se ele terá alta aprovação entre os jogadores. O problema foi formulado como uma classificação binária, considerando como alta aprovação uma taxa igual ou superior à mediana da amostra analisada.

## Modelos comparados

- Regressão Logística
- Árvore de Decisão
- Random Forest

A Random Forest apresentou o melhor resultado, com **62,96% de acurácia no conjunto de teste**.

## Arquivos

- [`projeto.ipynb`](projeto.ipynb): notebook completo com carregamento, preparação, modelagem, avaliação e gráficos.
- [`relatorio_final_sbc.pdf`](relatorio_final_sbc.pdf): relatório final no formato de artigo SBC.
- [`requirements.txt`](requirements.txt): dependências necessárias para executar o notebook.

## Base de dados

Foi utilizado o [Steam Games Dataset, publicado no Kaggle](https://www.kaggle.com/datasets/fronkongames/steam-games-dataset).

O arquivo `games.csv` não está armazenado neste repositório devido ao seu tamanho. Depois de baixar a base, coloque o arquivo em `data/games.csv` ou na mesma pasta do notebook.

## Execução

Instale as dependências:

```bash
pip install -r requirements.txt
```

Abra `projeto.ipynb` no Jupyter Notebook ou no Google Colab e execute as células em ordem.
