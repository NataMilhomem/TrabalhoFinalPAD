# Trabalho Final da Disciplina de Pensamento Analítico de Dados

Grupo: Geovana Teixeira, Jair Neto, Lídia do Vale (Líder), Mirmila Sócrates, Natã Milhomem.

## Tema: Recomendação

---
---

### Projeto FMF:
Getting Started with a Movie Recommendation System:
https://www.kaggle.com/ibtesama/getting-started-with-a-movie-recommendation-system

Colab: 
https://colab.research.google.com/drive/1KjXbZAFiajppb9PKzw4wXt8aEgz2Wyp-?usp=sharing

Pasta Google Drive:
https://drive.google.com/drive/folders/15Dilh-XrBQ-GykSqaA_xcgkgPLTRTwsw?usp=sharing

---

#### Ask - Semana 1
> Definir a pergunta

**ASK**:
"Quais são os melhores filmes para recomendar a um usuário baseado em suas preferências anteriores?"


### Get e Explore - Semana 2
> Quais são os dados? Como vamos acessá-los?
> Como os dados se comportam? Existem padrões?

**GET:** 
Base do TMDB (disponível no drive)

**EXPLORE**:
- Visualização das primeiras linhas
- Inspeção das colunas e os tipos de dados
- Junção de dataframes
- Criação de novas variáveis/colunas
- Tratamento de valores ausentes
- Transformação de strings para minúsculas e sem espaços
- Conversão de strings para estruturas utilizáveis
- Criação de sopa de palavras de várias colunas
- Vectorização de texto
- Média ponderada das avaliações de filmes
- Filtragem de filmes por critérios
- Criação de histogramas da popularidade de filmes


### Model and Communicate - Semana 3
> Construção, adequação e validação de um modelo
> Comunicação e divulgação dos resultados

**MODEL**:
- Matriz TF-IDF (TfIdfVectorizer class pelo SKlearn) do resumo dos filmes
- Cálculo do núcleo linear (kernel) da Matriz TF-IDF (linear_kernel() pelo SKLearn)
- Construção de um mapa reverso que associa índices a títulos de filme  (usando o Pandas)
- Criação de uma "sopa de metadados" contendo diretor, 3 principais atores e palavras-chave
- Vetorização dos metadados e Cálculo da Matriz de Similaridade Cosseno entre os vetores
- Cálculo do Root Mean Square Error (RMSE) de avaliação de filmes pelos usuários (funções reader, dataset, SVD e evaluate da biblioteca Surprise)

**COMMUNICATE**:
Construção da função 'get_recommendations', em que o título de um filme é informado por um usuário e uma lista dos 10 filmes mais similares é apresentada

---
---

### Projeto Original:
https://drive.google.com/file/d/1ZVt5CXAp39oDm5vEEMfoCt19C7mLqXTp/view?usp=sharing


---

#### Ask - Semana 1
> Definir a pergunta

**ASK**:
"Quais são as melhores **séries** para recomendar a um usuário baseado em suas preferências anteriores?"

### Get e Explore - Semana 2
> Quais são os dados? Como vamos acessá-los?
> Como os dados se comportam? Existem padrões?

**GET**: 
Dados do TV Maze API (https://www.tvmaze.com/api)

**EXPLORE**:
- Visualização das primeiras linhas
- Inspeção das colunas e os tipos de dados
- Junção de dataframes
- Criação de novas variáveis/colunas
- Tratamento de valores ausentes
- Transformação de strings para minúsculas e sem espaços
- Conversão de strings para estruturas utilizáveis
- Criação de sopa de palavras de várias colunas
- Vectorização de texto
- Média ponderada das avaliações de séries
- Filtragem de séries por critérios
- Criação de histogramas da popularidade de séries


### Model and Communicate - Semana 3
> Construção, adequação e validação de um modelo
> Comunicação e divulgação dos resultados

**MODEL**:
- ...

**COMMUNICATE**:
...
