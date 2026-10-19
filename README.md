# Data Visualization

Coursework and final project for a Data Visualization class (DATA 3310), built with Python and [Altair](https://altair-viz.github.io/).

## Final project: AI and the CS job market

An interactive analysis of how AI adoption and automation risk may affect job prospects for computer science graduates. It covers AI adoption by industry, automation risk by occupation, wage and employment trends, and the geographic spread of tech jobs.

**Team:** Henry Lai, Isaac Van Horn, Victor Wong, Hyman Ho

- Notebook (exported HTML): [`notebooks/final-project-ai-cs-job-market.html`](notebooks/final-project-ai-cs-job-market.html)
- Written report: [`docs/final-report.pdf`](docs/final-report.pdf)
- Slides: [`docs/final-presentation.pdf`](docs/final-presentation.pdf)

### Data sources

- AndrewMVD, *Occupation, Salary, and Likelihood of Automation* (Kaggle)
- Biswas & Jahan (2026), *Global AI Adoption Trends by Industry Sector, Country, and Business Function (2017-2025)*, Mendeley Data, doi: 10.17632/dnm5jxgn2m.2
- U.S. Bureau of Labor Statistics: OEWS profile; CPS 2024 annual averages; CPS Table 25b (2025 unemployment by occupation)
- National Center for Science and Engineering Statistics, National Survey of College Graduates (2025)

The raw CSVs are not included in this repo. Download them from the sources above.

## Repo layout

```
notebooks/
  class-interactive-altair.html      In-class interactive chart exercise
  hw5-altair.html                    Homework 5
  final-project-ai-cs-job-market.html  Final project notebook
docs/
  final-report.pdf
  final-presentation.pdf
```

The notebooks are static HTML exports, so open them in a browser. The charts are interactive (they load Vega libraries from a CDN, so you need an internet connection).