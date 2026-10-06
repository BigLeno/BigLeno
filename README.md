<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=header" width="100%" />
</p>

# Olá! Eu sou o [BigLeno](https://github.com/BigLeno) 👋

Sou **Python Developer / Data Engineer** na **[Confianca-FIDC](https://github.com/Confianca-FIDC)** — foco em pipelines de dados, ETL e integração de sistemas.

Tenho familiaridade com ambientes **Linux** para deploy, automação e administração de serviços em produção (Docker, bancos SQL, brokers de mensageria, web servers).

Antes disso, trabalhei com **hardware, IoT e prototipagem** na UFRN (URA, inPACTA, GPH), o que me deu uma visão completa do ciclo de desenvolvimento, do silício até o deploy em produção.

📍 Natal, RN — Brasil

---

## 🚀 O que eu faço agora

- **Data engineering** — pipelines ETL, CDC em tempo real, integração SQL Server ↔ PostgreSQL
- **Orquestração** — Apache Airflow + Docker para DAGs de produção
- **Automação** — Python para integração entre sistemas legados e modernos
- **Análise & visualização de dados** — SQL analítico, dashboards e modelos preditivos

---

## 🏷️ Featured Projects

### 🏦 Destaque — [bcb-indicadores-pipeline](https://github.com/BigLeno/bcb-indicadores-pipeline)

Pipeline de dados do **Banco Central (API SGS)** com Airflow 3, Postgres em camadas (raw → staging → marts) e **API REST em Django/DRF**. Foco no que torna um pipeline confiável em produção.

- Carga histórica de 26 anos (Selic, CDI, IPCA, dólar) em cerca de 1 minuto, com carga incremental e backfill
- Idempotência ponta a ponta: raw com sha256 e upsert que só reescreve revisões reais do BCB
- Checagens de qualidade que bloqueiam os marts; valores validados contra o IPCA oficial de 2024
- Dynamic task mapping: adicionar uma série é editar um YAML
- 118 testes (unitários e de integração em Postgres real) rodando no CI
- API somente leitura com OpenAPI/Swagger e decimais sem perda de precisão

### ⚡ Tempo real — [cdc-sqlserver-postgres-kafka](https://github.com/BigLeno/cdc-sqlserver-postgres-kafka)

Pipeline de **Change Data Capture (CDC)** em tempo real que replica alterações do SQL Server para PostgreSQL via Apache Kafka e Debezium.

- Captura de todas as alterações do banco de origem (INSERT, UPDATE, DELETE)
- Apache Kafka 4.3.0 em modo KRaft (sem Zookeeper)
- Debezium 3.5.2 com Source Connector e JDBC Sink Connector
- Replicação com upsert e propagação de deletes para o PostgreSQL
- Runbook operacional completo para diagnóstico e troubleshooting
- Filtragem automática de tabelas via regex (somente tabelas com PK)

### 🎓 Educação & Analytics — [data-analytics-portfolio](https://github.com/BigLeno/data-analytics-portfolio)

Pipeline de análise de dados educacionais (cursinho pré-vestibular) — do dado bruto "sujo" à base analítica estruturada, com dashboard, SQL, validação e modelo preditivo.

- Pipeline em camadas (ETL): extração fiel → tratamento documentado → base em Parquet
- Camada analítica em **SQL (DuckDB)** e validação de schema com **Pandera**
- **Dashboard interativo** (Streamlit + Plotly, 6 abas) e **score de propensão** (scikit-learn)
- Ambiente reproduzível com **Docker** — roda o pipeline e sobe o painel sozinho
- Rigor: auditoria e documentação da limitação amostral dos dados

---

## 🧰 Stack

### Data Engineering (atual)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)

### Backend
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/Django_REST_Framework-A30000?style=flat&logo=django&logoColor=white)

### Ambientes
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)

### Desenvolvimento
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)

### Data & Analytics
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

### Hardware & IoT (histórico)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-C51A4A?style=flat&logo=raspberry-pi&logoColor=white)
![3D Printing](https://img.shields.io/badge/3D_Printing-FF6F00?style=flat&logo=3m&logoColor=white)
![Fusion360](https://img.shields.io/badge/Fusion_360-F58220?style=flat&logo=autodesk&logoColor=white)

---

## 🌎 Idiomas

- 🇧🇷 **Português** — Nativo
- 🇺🇸 **Inglês** — Intermediário
- 🇪🇸 **Espanhol** — Básico

---

## 📊 GitHub Stats

<a href="https://github.com/BigLeno">
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=BigLeno&theme=noctis_minimus&show_icons=true" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BigLeno&theme=noctis_minimus&layout=compact&size_weight=0.1&count_weight=1.5" />
</a>

---

## 🌐 Contato

- 💼 [LinkedIn](https://www.linkedin.com/in/rutileno-gabriel)
- 🧠 [GitHub](https://github.com/BigLeno)
- 📷 [Instagram](https://www.instagram.com/rutileno_gabriel/)
- 💬 Discord: **BigLeno#5106**

<p align="left">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" width="100%" />
</p>
