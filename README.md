# Projeto Marvel Data

Este projeto coleta, processa e analisa dados sobre os personagens do universo Marvel, utilizando a API pública da Marvel. O objetivo é realizar análises interessantes sobre os personagens, como o número de quadrinhos disponíveis, eventos em que participaram, e outros insights.

## Funcionalidades

- **Coleta de Dados**: O projeto utiliza a API da Marvel para coletar informações detalhadas sobre os personagens, como quadrinhos disponíveis, séries, histórias, e eventos.
- **Tratamento de Dados**: Os dados são tratados, removendo valores nulos e organizados em um formato que permite análise eficiente.
- **Análises**: O projeto gera gráficos e insights como:
  - Ranking dos 10 personagens com mais quadrinhos.
  - Quantidade de personagens com descrição e sem descrição.
  - Número de personagens modificados nos últimos 5 anos.

## Tecnologias Utilizadas

- **Python**: Linguagem principal utilizada para coleta, tratamento e análise de dados.
- **Pandas**: Para manipulação e análise de dados tabulares.
- **Matplotlib** e **Seaborn**: Para visualização de dados e geração de gráficos.
- **API Marvel**: Para coletar dados dos personagens.

## Como Executar

### Requisitos

- Python 3.x
- Bibliotecas:
  - requests
  - pandas
  - matplotlib
  - seaborn

### Passos para Execução

1. Clone o repositório:

   ```bash
   git clone https://github.com/kevintg99/marvel_data_project.git
