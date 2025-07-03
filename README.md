# PUCRJ-AD-MVP
Projeto MVP para compor nota da Pós Graduação de Ciência de Dados e Analytics, Sprint de Análise de Dados e Boas Práticas, na PUC-RJ


# 📊 Datasets - 🏎️ Análise Histórica da Fórmula 1 (1950–2024)

Este branch contém os arquivos de dados utilizados no projeto **🏎️ Análise Histórica da Fórmula 1 (1950–2024)**.

## 📁 Estrutura dos Dados

\
### Datasets principais

| Dataset                     | Uso principal                                  |
| --------------------------- | ---------------------------------------------- |
| `drivers.csv`               | Informações dos pilotos                        |
| `constructors.csv`          | Informações das equipes                        |
| `races.csv`                 | Datas e locais das corridas                    |
| `results.csv`               | Resultados das corridas (posição, pontos etc.) |
| `driver_standings.csv`      | Pontuação acumulada dos pilotos                |
| `constructor_standings.csv` | Pontuação acumulada dos construtores           |
| `qualifying.csv`            | Tempo das voltas na qualificação               |
| `lap_times.csv`             | Duração das voltas nas corridas                |

\\
### Principais atributos

| Dataset                     | Atributos principais utilizados                                                            |
| --------------------------- | ------------------------------------------------------------------------------------------ |
| `drivers.csv`               | `driverId`, `dob`, `surname`, `nationality`                                                |
| `constructors.csv`          | `constructorId`, `name`                                                                    |
| `races.csv`                 | `raceId`, `year`, `circuitId`, `name`, `date`                                              |
| `results.csv`               | `raceId`, `driverId`, `constructorId`, `positionOrder`, `fastestLap`                       |
| `driver_standings.csv`      | `raceId`, `driverId`, `points`, `position`                                                 |
| `constructor_standings.csv` | `raceId`, `constructorId`, `points`, `position`                                            |
| `qualifying.csv`            | `raceId`, `driverId`, `q1`, `q2`, `q3` (convertidos em segundos com `convert_time_to_sec`) |
| `lap_times.csv`             | `raceId`, `driverId`, `lap`, `milliseconds` (convertidos em `lap_sec`)                     |
| `circuits.csv`              | `circuitId`, `name`, `location`, `country`                                                 |


## 🧾 Fonte dos Dados

Os dados foram obtidos de:

Fonte de dados: **Formula 1 World Championship (1950 - 2024)** \
Acesso em <https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020/data>

## 📌 Observações

- Este branch é utilizado **apenas para armazenar os datasets**, facilitando a manutenção e separação dos dados do código principal.

## 🔗 Branch Principal

O código principal que utiliza esses dados está no branch: [`main`](https://github.com/MarinaCRezende/PUCRJ-AD-MVP/tree/main)

## 📜 Licença

Verifique a licença da fonte dos dados originais antes de redistribuir. Este repositório é apenas para fins educacionais e analíticos.


