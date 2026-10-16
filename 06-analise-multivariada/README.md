# Análise Bivariada e Multivariada

Esse foi o módulo mais avançado em termos de estatística. Depois de aprender a analisar variáveis individualmente e fazer visualizações, aqui o foco foi entender como as variáveis se relacionam entre si — tanto em pares quanto em conjunto.

## O que tem aqui

- **`notebook.ipynb`** — Notebook completo com teoria e exercícios

## O que eu trabalhei

O notebook segue uma progressão natural de complexidade:

### Análise Bivariada
- **Numérico × Numérico** — scatter plots, correlação de Pearson e Spearman
- **Categórico × Categórico** — tabelas de contingência, teste qui-quadrado
- **Numérico × Categórico** — boxplots comparativos, testes t e ANOVA

### Análise Multivariada
- **Correlação entre múltiplas variáveis** — heatmaps de correlação
- **PCA (Análise de Componentes Principais)** — redução de dimensionalidade para simplificar datasets com muitas colunas
- **Visualizações multivariadas** — pair plots, gráficos com codificação por cor e tamanho

A ideia central é que no mundo real nenhuma variável existe isolada — o preço de uma casa depende da área, da localização, do número de quartos, tudo junto. Esse módulo ensina a captar essas relações.

## Dependências

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```
