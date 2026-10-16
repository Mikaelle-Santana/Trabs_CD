# Visualização de Dados

Aqui o foco foi aprender a contar histórias com gráficos. O notebook usa um cenário fictício (mas com dados reais) onde eu sou uma desenvolvedora na Olist e preciso ajudar a equipe de negócios a entender tendências de vendas e comportamento de clientes.

## O que tem aqui

- **`notebook.ipynb`** — Notebook completo com teoria e exercícios práticos de visualização

## O que eu trabalhei

O notebook segue um fluxo que começa com a preparação dos dados (unir várias tabelas do dataset Olist) e vai avançando nas visualizações:

- **Montagem do DataFrame** — juntar 6 tabelas CSV usando joins com Pandas
- **Gráficos de distribuição** — histogramas, boxplots
- **Séries temporais** — evolução de vendas ao longo dos meses
- **Comparações categóricas** — vendas por estado, por categoria de produto
- **Mapas de calor** — correlações entre variáveis numéricas
- Uso de **Matplotlib** e **Seaborn** para gráficos mais elaborados

## Dataset

O notebook utiliza o **Brazilian E-Commerce Public Dataset by Olist**, um conjunto de dados com ~100 mil pedidos de um marketplace brasileiro (2016–2018).

📥 [Baixar no Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Os arquivos CSV devem ser colocados na pasta `data/olist/`. São eles:
- `olist_customers_dataset.csv`
- `olist_orders_dataset.csv`
- `olist_order_items_dataset.csv`
- `olist_order_payments_dataset.csv`
- `olist_order_reviews_dataset.csv`
- `olist_products_dataset.csv`
- `olist_sellers_dataset.csv`
- `olist_geolocation_dataset.csv`
- `product_category_name_translation.csv`
