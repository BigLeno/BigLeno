<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=190&section=header&text=Rutileno%20Gabriel&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=Data%20Engineer%20%C2%B7%20Python%20%C2%B7%20Airflow%20%C2%B7%20SQL&descSize=17&descAlignY=58" width="100%" alt="Rutileno Gabriel — Data Engineer" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rutileno--gabriel-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rutileno-gabriel)
![Data Engineer](https://img.shields.io/badge/Data_Engineer-Confian%C3%A7a_FIDC-203a43?style=flat-square)
![Natal, RN](https://img.shields.io/badge/Natal%2C_RN-Brasil-2c5364?style=flat-square)

</div>

<br />

Sou engenheiro de dados na **Confiança FIDC**, onde trabalho com pipelines de ETL, CDC e integração entre sistemas, quase sempre em Python, SQL e Airflow.

Me formei em Ciências & Tecnologia pela UFRN. Antes de ir para dados, passei pelos laboratórios da universidade (URA, inPACTA, GPH) trabalhando com hardware, IoT e prototipagem, e ainda carrego dessa época o gosto por Linux e por colocar as coisas para rodar em produção.

## O que eu faço

- Pipelines de ETL em camadas e CDC em tempo real entre SQL Server e PostgreSQL
- DAGs de produção com Apache Airflow e Docker
- Integração entre sistemas legados e novos em Python
- SQL analítico, dashboards e alguns modelos preditivos

## Projetos em destaque

### 🏦 [bcb-indicadores-pipeline](https://github.com/BigLeno/bcb-indicadores-pipeline)

Pipeline que busca Selic, CDI, IPCA e dólar na API SGS do Banco Central, organiza os dados em camadas no Postgres (raw → staging → marts) e expõe os indicadores numa API REST com Django.

![Airflow](https://img.shields.io/badge/Airflow_3-017CEE?style=flat-square&logo=apache-airflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Django REST](https://img.shields.io/badge/Django_REST-092E20?style=flat-square&logo=django&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

- Carga histórica de 26 anos em cerca de 1 minuto, depois incremental, com backfill
- Rodar de novo não duplica dados; só revisões reais do BCB atualizam linhas
- Checagens de qualidade antes dos marts, com os valores conferidos contra o IPCA oficial de 2024
- 118 testes, parte deles em Postgres real, rodando no CI

### ⚡ [cdc-sqlserver-postgres-kafka](https://github.com/BigLeno/cdc-sqlserver-postgres-kafka)

Change Data Capture do SQL Server para o PostgreSQL: cada INSERT, UPDATE e DELETE na origem chega ao destino via Kafka e Debezium.

![Apache Kafka](https://img.shields.io/badge/Kafka_4.3_(KRaft)-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![Debezium](https://img.shields.io/badge/Debezium_3.5-6A9FB5?style=flat-square)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)

- Kafka 4.3 em modo KRaft (sem Zookeeper), Debezium com Source e JDBC Sink Connector
- Upsert no destino e propagação de deletes
- Tabelas selecionadas por regex, só as que têm PK
- Runbook para diagnóstico e troubleshooting

### 🎓 [data-analytics-portfolio](https://github.com/BigLeno/data-analytics-portfolio)

Análise dos dados de um cursinho pré-vestibular, partindo de planilhas brutas até uma base analítica, um dashboard e um modelo preditivo.

![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Pandera](https://img.shields.io/badge/Pandera-150458?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

- ETL em camadas com o tratamento documentado e base final em Parquet
- Consultas em DuckDB e validação de schema com Pandera
- Dashboard em Streamlit + Plotly e score de propensão com scikit-learn
- Sobe inteiro com Docker; as limitações da amostra estão documentadas

## Stack

**Engenharia de dados**<br />
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Backend e infraestrutura**<br />
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/Django_REST_Framework-A30000?style=flat-square&logo=django&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**Análise de dados**<br />
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)

<details>
<summary><b>Outras linguagens e hardware</b></summary>
<br />

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-C51A4A?style=flat-square&logo=raspberry-pi&logoColor=white)
![3D Printing](https://img.shields.io/badge/Impress%C3%A3o_3D-FF6F00?style=flat-square)
![Fusion 360](https://img.shields.io/badge/Fusion_360-F58220?style=flat-square&logo=autodesk&logoColor=white)

</details>

## GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=BigLeno&theme=noctis_minimus&show_icons=true&hide_border=true&hide_rank=false" alt="Estatísticas do GitHub" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BigLeno&theme=noctis_minimus&layout=compact&size_weight=0.1&count_weight=1.5&hide_border=true" alt="Linguagens mais usadas" />

</div>

## Idiomas

🇧🇷 Português (nativo) · 🇺🇸 Inglês (intermediário) · 🇪🇸 Espanhol (básico)

## Contato

Me chama no [LinkedIn](https://www.linkedin.com/in/rutileno-gabriel).

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=110&section=footer" width="100%" alt="" />
