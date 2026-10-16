# Limpeza e Preparação de Dados

Essa etapa da disciplina foi dedicada a um tema que parece simples mas é o que mais consome tempo em qualquer projeto de dados: limpar e preparar os dados antes de usar em modelos.

## O que tem aqui

- **`aula-limpeza.ipynb`** — Material teórico e exemplos práticos sobre limpeza de dados
- **`exercicio-limpeza.ipynb`** — Enunciado do trabalho prático (Ames Housing)
- **`resolucao-mikaelle.ipynb`** — Minha resolução completa do trabalho, com justificativas para cada decisão

## Conteúdo da aula

O notebook da aula começa explicando o conceito de GIGO ("Garbage In, Garbage Out") e apresenta uma taxonomia dos tipos de problemas que encontramos em dados reais:

- Dados faltantes (e as diferentes estratégias: remoção, imputação por média/mediana, forward fill)
- Dados duplicados
- Outliers e como identificá-los
- Inconsistências em variáveis categóricas
- Transformações de tipo (datas, numéricos formatados como texto)
- Normalização e padronização

## Sobre o trabalho prático

O desafio foi pegar o dataset Ames Housing — um conjunto de dados sobre casas residenciais com 82 colunas — e prepará-lo para ser usado em um modelo de machine learning que prevê preços. A ideia não era seguir um roteiro, mas tomar decisões próprias e justificar cada passo.

Na minha resolução, trabalhei questões como:
- Quais colunas com dados faltantes vale a pena manter?
- Quando faz sentido preencher vs. remover linhas/colunas?
- Como transformar variáveis categóricas ordinais em numéricas?

## Datasets

Os notebooks usam o **Ames Housing Dataset**:

- 📥 [Baixar no Kaggle](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)
- Coloque os arquivos `AmesHousing.csv`, `AmesHousing.xlsx` e `train.csv` na pasta `data/`
