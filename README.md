# Ciência de Dados — Trabalhos Acadêmicos

Repositório com os trabalhos e exercícios que desenvolvi ao longo da disciplina de Ciência de Dados. Cada pasta contém um tema diferente, com notebooks comentados, dados utilizados e um README explicando o contexto de cada atividade.

A ideia aqui é documentar minha evolução — desde a primeira vez mexendo com Pandas até análises mais complexas com texto e múltiplas variáveis.

---

## Estrutura do Repositório

| Pasta | Tema | Resumo |
|:------|:-----|:-------|
| [`01-analise-dados-pandas/`](./01-analise-dados-pandas/) | Análise de Dados com Pandas | Primeiros passos com Pandas: leitura de dados, filtros, agrupamentos, tabelas pivô e visualizações simples usando um dataset de vendas de videogames. |
| [`02-web-scraping/`](./02-web-scraping/) | Web Scraping | Material teórico e prático sobre extração de dados da web, cobrindo desde `requests` + `BeautifulSoup` até automação com Playwright, Scrapy e consumo de APIs (Spotify, YouTube). |
| [`03-limpeza-de-dados/`](./03-limpeza-de-dados/) | Limpeza e Preparação de Dados | Aula sobre técnicas de limpeza (dados faltantes, outliers, transformações) e trabalho prático com o dataset Ames Housing, incluindo minha resolução completa. |
| [`04-visualizacao-de-dados/`](./04-visualizacao-de-dados/) | Visualização de Dados | Estudo de caso com o dataset Olist (e-commerce brasileiro): construção de gráficos com Matplotlib, Seaborn e análise visual de tendências de vendas. |
| [`05-eda-texto/`](./05-eda-texto/) | Análise Exploratória de Texto | Exploração de avaliações textuais de clientes usando técnicas de PLN: tokenização, nuvens de palavras, análise de sentimento e frequência de termos. |
| [`06-analise-multivariada/`](./06-analise-multivariada/) | Análise Bivariada e Multivariada | Estudo das relações entre variáveis: correlações, testes estatísticos, PCA e técnicas de redução de dimensionalidade. |

---

## Sobre os Datasets

Os datasets usados nos notebooks **não estão incluídos no repositório** por serem arquivos grandes. Cada README individual traz instruções de onde baixá-los. Os principais são:

- **Video Games Sales** — dataset de vendas de videogames até 2016
- **Ames Housing** — dados de imóveis residenciais para regressão de preços
- **Olist E-Commerce** — dados reais de 100 mil pedidos de um marketplace brasileiro

---

## Tecnologias Utilizadas

- Python 3
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- BeautifulSoup, Requests, Playwright
- Spotipy, Google API Client
- NLTK, WordCloud

---

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/cd.git
   cd cd
   ```

2. Crie um ambiente virtual e instale as dependências:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install pandas numpy matplotlib seaborn jupyter beautifulsoup4 requests
   ```

3. Baixe os datasets necessários (veja o README de cada pasta).

4. Inicie o Jupyter:
   ```bash
   jupyter notebook
   ```

---

## Autora

**Mikaelle Costa de Santana**

Trabalhos desenvolvidos durante a disciplina de Ciência de Dados.
