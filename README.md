# PUCRJ-AD-MVP
Projeto MVP para compor nota da Pós Graduação de Ciência de Dados e Analytics, Sprint de Análise de Dados e Boas Práticas, na PUC-RJ

# 🏎️ Análise Histórica da Fórmula 1 (1950–2024)

Este projeto explora os dados da Fórmula 1 com foco em pilotos, equipes e mudanças técnicas que moldaram o esporte ao longo das décadas.

## 🎯 Objetivo

Realizar uma análise exploratória dos dados da F1 entre 1950 e 2024, respondendo perguntas como:

- Quais pilotos dominaram cada década?
- Qual a evolução da participação das equipes e pilotos ao longo dos anos?
- Quais pilotos acumularam mais voltas mais rápidas?
- Há alguma relação visível entre eventos históricos (como mudanças de regulamento) e alterações nos padrões de performance?

## 📁 Fontes de Dados

Base utilizada: [Formula 1 World Championship (1950 - 2024)](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)

## 📊 Datasets principais

| Dataset                     | Uso principal                                  |
|----------------------------|-----------------------------------------------|
| `drivers.csv`              | Informações dos pilotos                        |
| `constructors.csv`         | Informações das equipes                        |
| `races.csv`                | Datas e locais das corridas                    |
| `results.csv`              | Resultados das corridas                        |
| `driver_standings.csv`     | Pontuação dos pilotos                          |
| `constructor_standings.csv`| Pontuação dos construtores                     |
| `qualifying.csv`           | Tempos na classificação                        |
| `lap_times.csv`            | Duração das voltas nas corridas                |

## 📌 Destaques da Análise

- Comparação entre pilotos e equipes por década.
- Visualizações das posições médias, voltas rápidas e pontos acumulados.
- Análise de impacto de eventos históricos (ex: proibição de reabastecimento, introdução do DRS, novos regulamentos aerodinâmicos).

## 📦 Requisitos

- Python 3.8+
- pandas, numpy, matplotlib, seaborn, plotly

## 🛠️ Como Executar

1. Clone o repositório
2. Instale os pacotes com `pip install -r requirements.txt`
3. Execute o notebook `MVP_MarinaRezende_AD.ipynb`

## 📌 Autora

**Marina Rezende**  
Sprint: Análise de Dados e Boas Práticas  
Curso: Ciência de Dados e Analytics
