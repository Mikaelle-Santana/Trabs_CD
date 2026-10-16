# Análise Exploratória de Dados Textuais

Esse notebook explora um lado diferente dos dados: o texto livre. Em vez de trabalhar com números e categorias, aqui o desafio é entender o que os clientes estão dizendo nas suas avaliações e transformar isso em insights úteis.

## O que tem aqui

- **`notebook.ipynb`** — Notebook completo de análise de texto com o dataset Olist

## O que eu trabalhei

O problema central que guia toda a análise é: *"O que as avaliações textuais dos clientes da Olist nos dizem sobre os principais motivos de satisfação e insatisfação?"*

Para responder, o notebook passa por várias etapas:

- **Preparação de texto** — limpeza, remoção de stopwords, tokenização
- **Análise de frequência** — quais palavras e termos mais aparecem nas avaliações positivas vs. negativas
- **Nuvens de palavras** — visualização intuitiva dos termos mais comuns
- **N-gramas** — bigramas e trigramas para captar expressões completas ("entrega rápida", "produto não chegou")
- **Análise de sentimento** — classificação automática do tom das avaliações
- **Cruzamento com dados estruturados** — relacionar o texto com notas, atrasos de entrega e categorias de produto

## Dataset

Usa o mesmo **Dataset Olist** do módulo de visualização.

📥 [Baixar no Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Os arquivos devem estar acessíveis em `data/olist/` (neste diretório há um link simbólico apontando para `../04-visualizacao-de-dados/data/olist/`).

## Dependências extras

```bash
pip install nltk wordcloud
```
