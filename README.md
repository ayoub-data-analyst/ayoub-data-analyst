<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:1e293b&height=180&section=header&text=Ayoub%20El%20Ouichouany&fontSize=38&fontColor=ffffff&fontAlignY=42&desc=Analytics%20Engineer%20%C2%B7%20Building%20Data%20Pipelines%20People%20Trust&descAlignY=62&descSize=15&animation=fadeIn" width="100%"/>

<a href="https://linkedin.com/in/ayoub-el-ouichouany"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:ayoubelouichouany0@gmail.com"><img src="https://img.shields.io/badge/Email-1e293b?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/ayoub-data-analyst?tab=repositories"><img src="https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

<br/>

## Who I Am

Data Analyst Trainee at **Simplon Maghreb** (Béni Mellal, Morocco), building end-to-end data pipelines — ingestion → warehouse → dashboard — using the modern data stack: **Airflow**, **dbt**, **Snowflake**, **PostgreSQL**, **Power BI**.

Looking for a **Junior Data Engineer / Analytics Engineer / Data Analyst** role where I can keep shipping pipelines that hold up in production, not just in a notebook.

<br/>

## Proof, Not Claims

| | |
|---|---|
| **-80%** | reporting time cut through automated Power BI pipelines |
| **10M+** | rows/day processed in a production pipeline |
| **1,508** | property listings modeled across 10 Moroccan cities |
| **4** | data engineering / BI certifications (Snowflake, LinkedIn Learning) |

<br/>

## How I Build

- **Model before I move data** — dimensional design (star/snowflake schema) comes before a single pipeline is written.
- **Medallion architecture by default** — Bronze/Silver/Gold layering so raw, cleaned, and analytics-ready data never get mixed.
- **Data quality is a step, not an afterthought** — outlier detection (IQR + business rules), missing-value imputation, validated before anything reaches a dashboard.
- **Orchestrate, don't babysit** — Airflow DAGs trigger dbt models; pipelines run without me watching them.

<br/>

## Projects

<table>
<tr>
<td width="50%" valign="top">

### Real Estate Data Warehouse
**Problem** — Raw, multi-country property listings with no structure for analysis.
**Solution** — Medallion (Bronze/Silver/Gold) warehouse in Snowflake; Airflow-orchestrated dbt models feeding a star schema (`fact_listings` + 3 dimensions) straight into Power BI.
**Built with a 4-person team.**

`Snowflake` `dbt` `Airflow` `Power BI` `Docker`

[→ View repository](https://github.com/ayoub-data-analyst?tab=repositories)

</td>
<td width="50%" valign="top">

### Crypto Market Data Platform
**Problem** — No structured, scalable way to track live crypto market data.
**Solution** — Pipeline pulling from the CoinGecko API in real time, staged through Bronze/Silver/Gold layers in MinIO/Snowflake, orchestrated end-to-end with Airflow.

`Python` `Airflow` `Snowflake` `MinIO` `Power BI`

[→ View repository](https://github.com/ayoub-data-analyst?tab=repositories)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Darkom Real Estate Analytics
**Problem** — 1,508 raw property listings across 10 Moroccan cities, unusable for analysis.
**Solution** — Cleaned and validated dataset (city-level mode + grouped-median imputation, IQR outlier detection), modeled into a PostgreSQL star schema, reported through a 4-page interactive Power BI report.

`Python` `PostgreSQL` `SQLAlchemy` `Power BI`

[→ View repository](https://github.com/ayoub-data-analyst?tab=repositories)

</td>
<td width="50%" valign="top">

### Lending Club Data Warehouse
**Problem** — Millions of raw loan records with no dimensional structure for reporting.
**Solution** — End-to-end warehouse transforming raw loan data into dimensional models in Snowflake via dbt, surfaced through interactive Power BI dashboards.

`Python` `SQL` `dbt` `Snowflake` `Power BI`

[→ View repository](https://github.com/ayoub-data-analyst?tab=repositories)

</td>
</tr>
</table>

<br/>

## Tech Stack

<table>
<tr><td><b>Programming</b></td><td>Python · SQL</td></tr>
<tr><td><b>Data Engineering</b></td><td>Apache Airflow · dbt · Docker · ETL/ELT · SQLAlchemy</td></tr>
<tr><td><b>Warehousing & Modeling</b></td><td>Snowflake · PostgreSQL · Dimensional Modeling (Star/Snowflake) · Medallion Architecture</td></tr>
<tr><td><b>Analytics & BI</b></td><td>Power BI · DAX · Power Query · Pandas · NumPy</td></tr>
<tr><td><b>Cloud</b></td><td>Azure Data Factory</td></tr>
<tr><td><b>Tools</b></td><td>Git · GitHub · CI/CD · Jupyter · VS Code · MinIO</td></tr>
</table>

<br/>

## GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=ayoub-data-analyst&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&icon_color=38BDF8&text_color=C9D1D9"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ayoub-data-analyst&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9"/>

</div>

<br/>

## Background

```
2026 – Present   Data Analyst Training · CCFBS, Simplon Maghreb
2025             Baccalauréat, Économie · Lycée Technique El Khawarezmi
```

**Certifications:** Data Engineering Professional Certificate (Snowflake) · Power BI Essential Training · SQL Essential Training · Learning Docker — LinkedIn Learning

<br/>

## Contact

<div align="center">

<a href="https://linkedin.com/in/ayoub-el-ouichouany"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:ayoubelouichouany0@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e293b,100:0f172a&height=90&section=footer"/>

</div>
