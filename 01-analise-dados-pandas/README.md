# Análise de Dados com Pandas

Esse foi o meu primeiro contato prático com a biblioteca Pandas. O notebook acompanha uma aula sobre como explorar e entender um conjunto de dados do zero, usando um dataset de vendas de videogames.

## O que tem aqui

- **`notebook.ipynb`** — Notebook da aula com exemplos e exercícios

## O que eu aprendi

O foco foi aprender a "conversar" com os dados: carregar um CSV, olhar as primeiras linhas, entender os tipos de cada coluna e começar a fazer perguntas. Algumas coisas que pratiquei:

- **Leitura e inspeção** de dados com `read_csv`, `head()`, `info()`, `describe()`
- **Filtros e seleções** — por exemplo, encontrar jogos lançados depois de 2016 (que eram dados sujos na base)
- **Agrupamentos com `groupby`** — como total de vendas por plataforma
- **Tabelas cruzadas e pivô** — comparando gêneros de jogos entre consoles
- **Visualizações simples** com histogramas, scatter plots e gráficos de barras integrados ao Pandas

## Dataset

O notebook usa o arquivo `Video_Games.csv`, um dataset com informações de vendas, notas de críticos e usuários de jogos de videogame até 2016.

📥 O arquivo deve ser colocado na pasta `data/` deste diretório.
