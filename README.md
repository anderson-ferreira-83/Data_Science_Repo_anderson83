# Projeto de Análise de Dados do Censo

Este projeto utiliza dados do censo para explorar técnicas de análise de dados e modelos de aprendizado supervisionado. Ele aplica diferentes algoritmos de classificação para prever a classe de renda de indivíduos com base em suas características demográficas e socioeconômicas.

## Fonte dos Dados

O conjunto de dados foi obtido do [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Adult). Este dataset é amplamente utilizado para estudos de classificação binária, como prever se a renda de um indivíduo é superior a 50K por ano.

## Estrutura do Projeto

- **dados_do_censo_anderson83.py**: Script principal com a análise dos dados e aplicação de modelos de machine learning.
- **adult.data**: Arquivo de dados do censo usado para treinar e avaliar os modelos.

## Pré-requisitos

O projeto foi desenvolvido no Google Colab, mas pode ser executado em qualquer ambiente Python com as seguintes bibliotecas instaladas:

- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`

Para instalar as dependências, utilize:
```bash
pip install pandas seaborn matplotlib scikit-learn
```
## Execução

Para rodar o projeto, siga os passos:

1. Conecte-se ao Google Drive, caso use o Colab, para acessar o arquivo de dados (`adult.data`).
2. Defina o caminho para o diretório onde o arquivo de dados está salvo.
3. Execute cada célula para carregar, pré-processar, e visualizar os dados.
4. Teste os modelos de classificação disponíveis no script, como Regressão Logística, Árvore de Decisão, K-Nearest Neighbors, entre outros.

## Descrição do Conjunto de Dados

O conjunto de dados possui as seguintes colunas:

- **age**: Idade do indivíduo.
- **workclass**: Categoria de trabalho (ex.: servidor público, autônomo, etc).
- **education**: Nível de escolaridade.
- **education-num**: Código do nível de escolaridade.
- **marital-status**: Estado civil.
- **occupation**: Ocupação.
- **relationship**: Relação familiar (ex.: esposa, marido, etc).
- **race**: Raça.
- **sex**: Gênero.
- **capital-gain**: Ganho de capital.
- **capital-loss**: Perda de capital.
- **hours-per-week**: Horas trabalhadas por semana.
- **native-country**: País de origem.

O objetivo é prever a variável de **renda** (acima ou abaixo de 50K por ano) com base nessas características.

## Modelos de Machine Learning

O projeto inclui a aplicação de diversos algoritmos de classificação, incluindo:

- Regressão Logística
- Árvore de Decisão
- K-Nearest Neighbors
- Random Forest
- Naive Bayes

Esses modelos são treinados e avaliados para verificar qual oferece o melhor desempenho em termos de precisão e outras métricas de avaliação.

## Métricas de Avaliação

As principais métricas utilizadas para avaliação dos modelos são:

- **Acurácia**
- **Matriz de Confusão**
- **Relatório de Classificação** (contendo precisão, recall e f1-score)

