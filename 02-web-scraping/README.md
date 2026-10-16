# Web Scraping com Python

Essa parte da disciplina foi sobre extração de dados da web — desde o básico com `requests` até automação de navegador e consumo de APIs reais.

## O que tem aqui

- **`aula-scraping.ipynb`** — Material teórico completo sobre web scraping, cobrindo todas as abordagens principais
- **`pratica-scraping.ipynb`** — Exercícios práticos com casos reais (Spotify, YouTube, sites de e-commerce)

## O que esses notebooks cobrem

### Parte teórica (`aula-scraping.ipynb`)
O notebook funciona como um guia progressivo, indo do mais simples ao mais avançado:

1. **Requests + BeautifulSoup** — a base para sites estáticos, incluindo seletores CSS vs XPath
2. **Selenium e Playwright** — automação de navegador para sites dinâmicos (SPAs com JavaScript)
3. **Scrapy** — framework para projetos de scraping em larga escala
4. **APIs oficiais** — por que usar uma API é quase sempre melhor que scraping, quando disponível
5. **Técnicas avançadas** — lidar com paginação, logins, rate limiting e evasão de bloqueios
6. **Ética e legalidade** — robots.txt, termos de serviço e boas práticas

### Parte prática (`pratica-scraping.ipynb`)
Quatro módulos com exercícios mão na massa:

- **Módulo 1** — Coleta de dados do Spotify via API (playlists, podcasts, discografias)
- **Módulo 2** — API do YouTube (estatísticas de vídeos, playlists)
- **Módulo 3** — Scraping estático de sites de e-commerce (Nuuvem)
- **Módulo 4** — Scraping dinâmico com Playwright (infinite scroll)

## Dependências extras

```bash
pip install beautifulsoup4 requests lxml spotipy google-api-python-client playwright scrapy
playwright install
```

> ⚠️ Os exercícios com Spotify e YouTube precisam de chaves de API próprias. Consulte os notebooks para instruções de como obtê-las.
