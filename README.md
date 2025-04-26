# Meu primeiro modelo de Scikit Learn

Este projeto realiza uma análise exploratória de dados (EDA) com base no dataset `netflix_daily_top_10.csv`, que contém informações sobre os filmes e séries mais populares na Netflix. O objetivo é identificar padrões, outliers e insights relevantes sobre o desempenho de títulos na plataforma.

## Intuito do Projeto

O projeto foi desenvolvido como parte do curso **Desenvolvimento de IA** da Rocketseat. Ele tem como objetivo aplicar técnicas de análise exploratória de dados para responder às seguintes perguntas:

- Quais são os tipos de dados disponíveis no dataset?
- Qual é o período de análise coberto pelos dados?
- Qual é o tamanho da base de dados?
- Existem dados nulos? Se sim, onde?
- Quais são os outliers presentes nos dados?

Além disso, o projeto utiliza visualizações para explorar os dados e gerar relatórios automatizados com a biblioteca `sweetviz`.

## Estrutura do Projeto

- **`eda-challenge-netflix.ipynb`**: Notebook principal contendo o código para análise exploratória.
- __`netflix_daily_top_10.csv`__: Dataset com os dados de popularidade de títulos na Netflix.
- **`Pipfile` e `Pipfile.lock`**: Arquivos de configuração do ambiente virtual gerenciado pelo `pipenv`.

## Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas:

- Python 3.9 ou superior
- `pipenv` para gerenciamento de dependências
- Jupyter Notebook

## Instalação

1. Clone este repositório:

```bash
git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_REPOSITORIO>

```

2. Instale as dependências utilizando o pipenv:

```bash
pipenv install

```

3. Ative o ambiente virtual:

```bash
pipenv shell

```

## Executando o Jupyter Notebook

1. Inicie o servidor Jupyter:

```bash
jupyter notebook

```

2. No navegador, abra o arquivo eda-challenge-netflix.ipynb.

## Funcionalidades do Notebook

O notebook realiza as seguintes análises:

1. *Importação de bibliotecas:* Carrega as bibliotecas necessárias, como pandas, numpy, matplotlib e sweetviz.
2. _Criação do DataFrame:_ Lê o dataset netflix_daily_top_10.csv e exibe as primeiras linhas.
3. *Tipos de dados disponíveis:* Mostra informações sobre as colunas e seus tipos de dados.
4. *Período de análise: Identifica* o intervalo de tempo coberto pelos dados.
5. *Tamanho da base de dados:* Exibe o número de linhas e colunas do dataset.
6. *Verificação de dados nulos:* Identifica colunas com valores ausentes.
7. *Outliers:* Analisa outliers em colunas como Days In Top 10 e Viewership Score.
8. *Visualizações:* Gera gráficos como box plots, histogramas e gráficos de barras horizontais.
9. *Relatório automatizado:* Cria um relatório detalhado com a biblioteca sweetviz.

## Conclusão

Este projeto é uma aplicação prática de técnicas de análise exploratória de dados, permitindo identificar padrões e insights em dados reais. Ele também demonstra o uso de ferramentas como pandas, matplotlib e sweetviz para análise e visualização de dados.