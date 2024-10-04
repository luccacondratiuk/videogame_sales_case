# Videogame Sales Case (EN) | Caso Vendas de Videogames (PT_BR)

## EN

## Table of Contents

1. [Project Briefing](#project-briefing)
2. [Project Overview](#project-overview)
   - [Step 1: Exploring the Data](#step-1-exploring)
   - [Step 2: Preparing the Data](#step-2-preparing)
   - [Step 3: Analyzing the Data](#step-3-analyzing)
   - [Step 4: Defining a User Profile for Each Region](#step-4-defining-a-user-profile-for-each-region)
   - [Step 5: Test Hypotheses](#step-5-test-hypotheses)
3. [Data Description](#data-description)

## Project Briefing

The provided data is from 2016. The case takes place in December 2016, and we are planning a campaign for 2017.

The dataset contains a "rating" column, which stores the ESRB rating for each game. The Entertainment Software Rating Board evaluates game content and assigns age ratings, such as Teen or Mature.

## Project Overview

### Step 1: Exploring

**File Path:**
```/datasets/games.csv```

- Open the data file and examine the general information.

### Step 2: Preparing

1. Rename columns
2. Convert data.
3. Handle missing values if necessary:
4. Calculate total sales (the sum of sales across all regions) for each game and store these values in a separate column.

### Step 3: Analyzing

1. How many games were released in different years.
2. Examining how sales varied by platform.
3. Determining which period’s data should be used for creating a 2017.
4. Which platforms lead in sales? Which are growing or declining?
5. Does user and critic ratings affect sales on a popular platform?
6. What are the most profitable genres?

### Step 4: Defining a User Profile for Each Region

1. The top five platforms. How their market shares differ from region to region.
2. The top five genres.
3. Does the ESRB rating affect sales in individual regions?

### Step 5: Test Hypotheses

- Hypothesis 1: The average user ratings for Xbox One and PC platforms are the same.
- Hypothesis 2: The average user ratings for Action and Sports genres are different.

## Data Description

- **Name**: The name of the video game.
- **Platform**: The platform the game was released on.
- **Year_of_Release**: The release year of the game.
- **Genre**: The genre of the game.
- **NA_sales**: North American sales in millions of USD.
- **EU_sales**: European sales in millions of USD.
- **JP_sales**: Japanese sales in millions of USD.
- **Other_sales**: Sales in other regions in millions of USD.
- **Critic_Score**: Critic's score (maximum of 100).
- **User_Score**: User's score (maximum of 10).
- **Rating**: ESRB rating (Entertainment Software Rating Board).

---
---

## PT_BR

## Índice

1. [Contexto do Projeto](#contexto-do-projeto)
2. [Visão Geral do Projeto](#visão-geral-do-projeto)
   - [Etapa 1: Estudando os Dados](#etapa-1-estudando-os-dados)
   - [Etapa 2: Preparando os Dados](#etapa-2-preparando-os-dados)
   - [Etapa 3: Analisando os Dados](#etapa-3-analisando-os-dados)
   - [Etapa 4: Definindo um Perfil de Usuário para Cada Região](#etapa-4-definindo-um-perfil-de-usuário-para-cada-região)
   - [Etapa 5: Teste Hipóteses](#etapa-5-teste-hipóteses)
3. [Descrição dos Dados](#descrição-dos-dados)

## Contexto do Projeto

Os dados disponibilizados são de 2016. Imagine que estamos em dezembro de 2016 e você está planejando uma campanha para 2017.

O principal objetivo é ganhar experiência no trabalho com dados. Não importa se você está prevendo as vendas de 2017 com base nos dados de 2016 ou de 2027 com base nos de 2026.

O conjunto de dados contém uma coluna de "rating", que armazena a classificação ESRB de cada jogo. O Entertainment Software Rating Board avalia o conteúdo de um jogo e atribui uma classificação etária, como Adolescente (Teen) ou Adulto (Mature).

## Visão Geral do Projeto

### Etapa 1: Estudando os Dados

**Caminho do Arquivo:**
```/datasets/games.csv```

### Etapa 2: Preparando os Dados

1. Normalizando nome das colunas.
2. Convertendo o tipo dos dados.
3. Lidando com os valores ausentes quando necessário.
4. Adicionando dados pertinentes à análise.

### Etapa 3: Analisando os Dados

1. Veja quantos jogos foram lançados em diferentes anos?
2. Analisando como as vendas variaram entre plataformas.
3. Determinando o período de dados a ser usado para criar um modelo para 2017.
4. Quais plataformas lideram em vendas? Quais estão crescendo ou diminuindo?
5. Como as avaliações de usuários e críticos afetam as vendas em uma plataforma popular?
6. Quais são os gêneros mais lucrativos?

### Etapa 4: Definindo um Perfil de Usuário para Cada Região

1. Determinando as cinco principais plataformas.
2. Determinando os cinco principais gêneros.
3. A classificação ESRB afeta as vendas em regiões individuais?

### Etapa 5: Teste Hipóteses

- Hipótese 1: As avaliações médias dos usuários para Xbox One e PC são as mesmas.
- Hipótese 2: As avaliações médias dos usuários para os gêneros Ação e Esportes são diferentes.

## Descrição dos Dados

- **Name**: Nome do jogo.
- **Platform**: Plataforma em que o jogo foi lançado.
- **Year_of_Release**: Ano de lançamento do jogo.
- **Genre**: Gênero do jogo.
- **NA_sales**: Vendas na América do Norte em milhões de USD.
- **EU_sales**: Vendas na Europa em milhões de USD.
- **JP_sales**: Vendas no Japão em milhões de USD.
- **Other_sales**: Vendas em outras regiões em milhões de USD.
- **Critic_Score**: Pontuação dos críticos (máximo de 100).
- **User_Score**: Pontuação dos usuários (máximo de 10).
- **Rating**: Classificação ESRB (Entertainment Software Rating Board).
