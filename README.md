<img width="1920" height="4401" alt="image" src="https://github.com/user-attachments/assets/c4d1283e-9663-4362-a562-9622b5ada8cd" /><h1 align="center">Pedro Henrique Prado</h1>

<p align="center">
  <b>Engenharia de Dados</b> · Python · SQL · ETL/ELT · Airflow · Industrial Data
</p>

<p align="center">
  <a href="https://dev-pprado.github.io"><img src="https://img.shields.io/badge/Portfólio-dev--pprado.github.io-0F172A?style=for-the-badge&logo=astro&logoColor=white" alt="Portfólio"/></a>
  <a href="https://www.linkedin.com/in/pedro-hsprado-dataengineer"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://dev-pprado.github.io/cv.pdf"><img src="https://img.shields.io/badge/Currículo-PDF-334155?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Currículo"/></a>
</p>

---

## Sobre mim

## Sobre mim

Sou Engenheiro de Controle e Automação, com mais de 3 anos de experiência em sistemas industriais na indústria automotiva, atuando em um ambiente que integra PLCs, MES, SCADA, bancos de dados e sistemas corporativos.

Na minha experiência profissional, trabalho com SQL Server, análise de logs, investigação de falhas e integração entre sistemas industriais. Esse contexto me proporcionou uma visão prática sobre o fluxo de dados, a confiabilidade das informações e a importância de sistemas bem integrados.

Atualmente, direciono meus estudos e projetos para **Engenharia de Dados**, desenvolvendo soluções com Python, SQL, PostgreSQL, APIs e pipelines ETL/ELT. Tenho explorado também testes automatizados, Docker, dbt e orquestração de pipelines, aplicando boas práticas de desenvolvimento aos meus projetos pessoais.

Meu objetivo é construir pipelines confiáveis, processos de integração e arquiteturas de dados escaláveis, aproveitando minha experiência com sistemas industriais como diferencial para trabalhar com dados em ambientes complexos.

A longo prazo, também tenho interesse na interseção entre Engenharia de Dados e Inteligência Artificial, especialmente na construção da infraestrutura de dados necessária para aplicações de IA.

Este repositório reúne meus projetos práticos, experimentos e estudos em Engenharia de Dados.

---

## Projetos em destaque

### 📈 [Pipeline de estatísticas do GitHub](https://github.com/Dev-PPrado/Dev-PPrado.github.io)
Pipeline ETL que coleta toda semana dados dos meus repositórios pela API do GitHub e publica o resultado no meu [portfólio](https://dev-pprado.github.io).
- Extract, transform e load separados; a transformação é uma função pura coberta por **11 testes com pytest**
- Validação de schema com **Pydantic**, gravação atômica e idempotente, retry com backoff e plano B quando a API não responde
- **CI/CD no GitHub Actions**: testes → coleta → commit só se os dados mudaram → deploy no GitHub Pages

`Python` `httpx` `Pydantic` `pytest` `GitHub Actions`

### 🌤️ [Weather Data Pipeline](https://github.com/Dev-PPrado/weather_data_pipeline_ETL)
DAG do **Airflow** que roda a cada hora: extrai dados da API OpenWeatherMap, normaliza o JSON com Pandas, grava um intermediário em **Parquet** e carrega no **PostgreSQL**. Ambiente completo em Docker Compose.

`Python` `Airflow` `Pandas` `Parquet` `PostgreSQL` `SQLAlchemy` `Docker`

### ⚡ [Pokémon ETL Pipeline](https://github.com/Dev-PPrado/Pokemon-ETL-Pipeline)
Pipeline modular (extract → transform → validate → load) sobre a PokeAPI, que uso como estrutura de referência para os próximos projetos. Validação com Pydantic antes da carga, logging em console e arquivo, tratamento de erros e configuração por variáveis de ambiente.

`Python` `Pydantic` `SQLAlchemy` `SQLite` `pytest`

### Outros
- **[Northwind Sales Analytics](https://github.com/Dev-PPrado/northwind-sales-analytics)**: SQL analítico em PostgreSQL com CTEs, window functions e análise temporal
- **[Product CRUD API](https://github.com/Dev-PPrado/product-crud-api)**: API REST com FastAPI, PostgreSQL e front em Streamlit, tudo em Docker Compose

---

## Stack

**Uso profissional** (Engineering Brasil)

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MES](https://img.shields.io/badge/MES-475569?style=flat-square)
![SCADA](https://img.shields.io/badge/SCADA-475569?style=flat-square)
![OPC UA](https://img.shields.io/badge/OPC_/_OPC_UA-475569?style=flat-square)
![Kepware](https://img.shields.io/badge/Kepware-475569?style=flat-square)
![PLC Rockwell](https://img.shields.io/badge/PLC_Rockwell-475569?style=flat-square)
![APIs](https://img.shields.io/badge/APIs_/_Web_Services-475569?style=flat-square)

**Projetos pessoais**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Estudando agora**

![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Spark](https://img.shields.io/badge/Spark_/_PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)

---

## O que estou construindo

| Trilha | Status |
|---|---|
| Python, SQL, Git/GitHub e workshop de dbt (Jornada de Dados) | ✅ Concluído em 2026 |
| Imersão Databricks: Unity Catalog, Delta Lake, arquitetura medallion, MLflow | ✅ Concluído em 2026 |
| Trilha de Engenharia de Dados (Jornada de Dados) | 🔄 Em andamento |
| Projeto dbt + Airflow com Astronomer Cosmos | 📌 Próximo projeto |
| Modelagem de dados, bancos relacionais/NoSQL e governança | 📌 Planejado |
| PySpark, Data Lake/Lakehouse e AWS | 📌 Planejado |
| Data & AI: pipelines que alimentam aplicações de IA, MLflow e LLMs | 📌 Planejado |

```text
Automação industrial  →  SQL + Python  →  Engenharia de Dados  →  Cloud + Spark  →  Data & AI Engineering
     (hoje, no trabalho)     (projetos)         (foco atual)           (estudando)          (próximo passo)
```

---

<p align="center">
  Aberto a conversas sobre vagas de <b>Data Engineer Júnior</b>, Analytics Engineer e Data Platform.<br/>
  📍 Belo Horizonte, MG · 💬 Português (nativo) · Inglês (intermediário)
</p>
