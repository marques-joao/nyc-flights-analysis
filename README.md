# ✈️ Análise de Atrasos em Voos de NYC (2013)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange)

## 📋 Sobre o Projeto

Este projeto consiste em uma análise exploratória de dados (EDA) utilizando o dataset `nycflights`. O objetivo principal é investigar os fatores que influenciam a pontualidade dos voos que partem de Nova York (JFK, LGA, EWR), com foco específico no impacto das **rotas**, **aeronaves** e **sazonalidade**.

A análise busca responder perguntas como:
* A distância do voo tem correlação com o atraso na chegada?
* Existem aeronaves (`tailnum`) ou rotas específicas que são sistemicamente problemáticas?
* Qual o comportamento dos atrasos ao longo dos meses do ano?

## 🗂️ Fonte de Dados

Os dados foram obtidos a partir do repositório público:
- **URL:** [nycflights.csv](https://raw.githubusercontent.com/JackyP/testing/master/datasets/nycflights.csv)
- **Conteúdo:** Dados de mais de 300.000 voos partindo de NYC em 2013.

## 🛠️ Tecnologias Utilizadas

*   **Python** (Linguagem Principal)
*   **Pandas** (Limpeza, manipulação e agregação de dados)
*   **Seaborn & Matplotlib** (Visualização de dados: Scatterplots, Heatmaps e Barplots)
*   **Jupyter Notebook** (Ambiente de desenvolvimento)

## 🚀 Como Executar

1.  Clone este repositório:
    ```
    git clone https://github.com/SEU_USUARIO/NOME_DO_REPO.git
    ```
2.  Instale as dependências necessárias:
    ```
    pip install pandas seaborn matplotlib
    ```
3.  Execute o notebook da análise:
    ```
    jupyter notebook analise_voos_nyc.ipynb
    ```

## 📈 Principais Insights

*   **Horário:** Os dados mostram uma progressão linear de atrasos ao longo do dia. A partir da manhã, a média de atraso sobe consistentemente a cada hora, atingindo seus picos à noite.
*   **Sazonalidade:** Observou-se que os meses de Junho, Julho e Dezembro apresentam as maiores médias de atraso na partida.
*   **Rotas:** Rotas não alteram significativamente a probabilidade de um pequeno atraso corriqueiro, mas certas rotas específicas aumentam drasticamente a volatilidade e o risco de atrasos severos.
*   **Infraestrutura:** Observou-se que uma aeronave específica não exerce influência significativa nos atrasos. Os grandes atrasos observados na média são eventos pontuais, não estruturais da aeronave.

## ✒️ Autores

**João Marques e [Caio Costa](https://github.com/caioreigot)**

*   Data Analyst
*   [LinkedIn](https://www.linkedin.com/in/joao-marq)
*   [GitHub](https://github.com/marques-joao)

---
