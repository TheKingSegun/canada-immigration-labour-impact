# Canada Immigration & Labour Market Impact

> **Live App:** [canada-immigration-labour.streamlit.app](https://canada-immigration-labour.streamlit.app)

An interactive Streamlit dashboard analysing how immigration shapes Canada's labour market — provincial employment trends, sector-level vacancy fill rates, wage dynamics, and newcomer integration outcomes. Built using real **Statistics Canada** and **IRCC** data.

## Business Impact
> "Dashboard surfaces that newcomer workers fill **68% of net healthcare vacancies** in Ontario and BC — interactive app deployed publicly on Streamlit Cloud"

- Directly relevant to Canadian employers evaluating internationally-trained data professionals
- Demonstrates ability to work with government open data APIs at scale
- Actionable for HR, policy, and workforce planning contexts

## What the Dashboard Shows
1. **Provincial employment map** — unemployment rates by province, filterable by year
2. **Immigration vs. labour force growth** — how IRCC admissions correlate with employment gains
3. **Sector vacancy fill rates** — which industries newcomers enter vs. domestic hires
4. **Wage convergence analysis** — earnings gap between newcomers and Canadian-born workers over time
5. **Top source countries** — where skilled workers come from and which sectors they join
6. **NOC occupation demand** — highest-demand occupations by province

## Key Findings
- Newcomers account for 100%+ of net labour force growth in ON, BC since 2016
- Healthcare and professional services show fastest newcomer integration (wage parity within 5 years)
- Youth unemployment (15-24) remains 2.3x the overall rate despite immigration inflows
- Real wage growth turned negative in 2022-23 due to inflation, hitting newcomers hardest

## Data Sources
| Source | Dataset | Access |
|--------|---------|--------|
| Statistics Canada | Labour Force Survey (LFS) — Table 14-10-0287-03 | Public API |
| Statistics Canada | Job Vacancy & Wage Survey — Table 14-10-0325-01 | Public API |
| IRCC | Permanent residents by province and category | Open data portal |
| Bank of Canada | CPI and real wage deflators | Public API |

## Tech Stack
- **Streamlit** — interactive dashboard
- **pandas + numpy** — data processing
- **Plotly + Altair** — interactive charts
- **Statistics Canada WDS API** — live data ingestion
- **geopandas** — provincial choropleth maps

## Run Locally
```bash
git clone https://github.com/TheKingSegun/canada-immigration-labour-impact
cd canada-immigration-labour-impact
pip install -r requirements.txt
streamlit run app.py
```

## Why This Project
As a Lagos-based data professional targeting international opportunities, I built this to demonstrate that I already understand the Canadian labour market — its data infrastructure, sector dynamics, and policy context — before setting foot there.
