# GitHub Repository Consolidation Plan

Goal: reduce the Foxfusion account from 45 active repositories to 18 active repositories.

## Active repositories to keep (18)

1. **Superman-React-Dev** — canonical Project Nuclear / Superman React application
2. **AI_Fox_Project** — AI agents, RAG, prompts, workflows, experiments
3. **Models** — reusable model training/evaluation/inference work
4. **Project-Nurv** — standalone local LLM/chat application
5. **project-archlight** — canonical scraping / web-intelligence platform
6. **Data_Engineering** — general data-engineering workspace
7. **FoxPySpark** — PySpark-specific work
8. **Spark** — Apache Spark-specific work
9. **Flink** — Apache Flink-specific work
10. **Terraform** — infrastructure-as-code work
11. **CDPSetup** — Cloudera/CDP setup assets
12. **CDE_Tour_ACE_HOL** — Cloudera Data Engineering hands-on lab
13. **FoxBase** — canonical legacy PHP/BigSky intranet
14. **DC_Characters** — graph/database project
15. **FoxFusion-Blizzard** — FoxFusion lab/site project
16. **Dev-Opshello-world** — DevOps/Kubernetes/Java demo
17. **MovieDux** — standalone React application
18. **Foxfusion** — GitHub profile / portfolio repository

## Repositories to archive (27)

### Nuclear / React duplicates
- proj_nuclear
- project-nuclear
- project-nuclear-react
- superman_react_nuclear
- superman_react_dev
- superman_react_dev_1
- react-app
- React
- react-one-fx
- reactfx4
- html-portfolio

Canonical destination: **Superman-React-Dev**

### BigSky duplicates
- BigSky
- BigSky_Dev
- BigSky_One
- Project_BigSky

Canonical destination: **FoxBase**

### Scraping experiments
- Price-Tracking-Web-Scraper
- Selenium
- BeautifulSoup
- WebScraping_Mariya
- Web-scraping-Yahoo-Finance-using-requests-and-Beautiful-Soup

Canonical destination: **project-archlight**

### Training / vendor / upstream copies
- grafana
- dagster
- mlflow
- pydata-book
- udemy-spark-streaming

Keep these archived for reference rather than treating them as active FoxFusion projects.

### Small / placeholder repositories
- Scala
- project-commons

Scala examples can move into **Data_Engineering** if needed. project-commons currently contains only a short project-list README.

## Consolidation principles

- Archive old repositories before considering deletion.
- Do not delete Git history during the first cleanup phase.
- Keep one canonical repository per application.
- Do not commit .env files, secrets, IDE metadata, node_modules, model artifacts, or generated build output.
- Use feature branches and pull requests for future changes.
- Keep large model artifacts and datasets in MLflow, Hugging Face, MinIO/S3, or other artifact/data storage rather than normal Git.

## Completed

- Project Nuclear / Superman code consolidated into **Superman-React-Dev**.
- Tracked .env, IntelliJ metadata, and node_modules removed from the canonical Nuclear repo.
- AI_Fox_Project reorganized into agents, models, RAG, prompts, tools, workflows, experiments, notebooks, config, tests, and docs.

## Next

1. Validate Superman-React-Dev locally.
2. Archive Nuclear/React duplicates.
3. Confirm FoxBase as canonical BigSky legacy source.
4. Archive BigSky duplicates.
5. Treat project-archlight as canonical scraping platform and archive older scraping experiments.
6. Archive vendor/training copies.
7. Review the final 18 repositories for README quality, .gitignore hygiene, secrets, and stale IDE/generated files.
