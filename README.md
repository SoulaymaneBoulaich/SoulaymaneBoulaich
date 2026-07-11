<style>
  @keyframes slideInDown {
    from {
      opacity: 0;
      transform: translateY(-30px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  @keyframes slideInUp {
    from {
      opacity: 0;
      transform: translateY(30px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  @keyframes fadeIn {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }

  @keyframes pulse {
    0%, 100% {
      opacity: 1;
    }
    50% {
      opacity: 0.6;
    }
  }

  @keyframes glow {
    0%, 100% {
      text-shadow: 0 0 5px rgba(56, 189, 248, 0.3);
    }
    50% {
      text-shadow: 0 0 15px rgba(56, 189, 248, 0.8);
    }
  }

  @keyframes slideInRight {
    from {
      opacity: 0;
      transform: translateX(-30px);
    }
    to {
      opacity: 1;
      transform: translateX(0);
    }
  }

  @keyframes bounceIn {
    0% {
      opacity: 0;
      transform: scale(0.3);
    }
    50% {
      opacity: 1;
      transform: scale(1.05);
    }
    100% {
      opacity: 1;
      transform: scale(1);
    }
  }

  .animated-header {
    animation: slideInDown 0.8s ease-out;
  }

  .animated-title {
    animation: glow 2s ease-in-out infinite, slideInDown 0.8s ease-out;
  }

  .animated-subtitle {
    animation: slideInDown 1s ease-out 0.2s both;
  }

  .animated-section {
    animation: slideInUp 0.8s ease-out;
  }

  .animated-badge {
    animation: bounceIn 0.6s ease-out;
    display: inline-block;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .animated-badge:hover {
    transform: translateY(-5px) scale(1.05);
    box-shadow: 0 5px 20px rgba(56, 189, 248, 0.4);
  }

  .tech-grid {
    animation: slideInUp 1s ease-out 0.4s both;
  }

  .stats-container {
    animation: slideInUp 1.2s ease-out 0.5s both;
  }

  .link-card {
    animation: bounceIn 0.7s ease-out;
    transition: all 0.3s ease;
  }

  .link-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 8px 25px rgba(56, 189, 248, 0.3);
  }

  table {
    animation: fadeIn 1s ease-out 0.3s both;
  }
</style>

<div class="animated-header">
  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a574b944-0433-4d0c-9295-13eef60393a6" style="animation: fadeIn 1s ease-out;" />
</div>

<div align="center">

<h1 class="animated-title">Soulaymane Boulaich</h1>

<h3 class="animated-subtitle">Data Engineer • ML Engineer • Full Stack Data Specialist</h3>

<img src="https://komarev.com/ghpvc/?username=SoulaymaneBoulaich&color=38BDF8&style=flat-square&label=Profile+Views" alt="Profile views" style="animation: pulse 2s ease-in-out infinite;" />

<br />

</div>

---

## Overview

<div class="animated-section">

Passionate **Data Engineer** with expertise in building scalable data infrastructure and ML pipelines. Currently a first-year engineering student at **ENSA Tétouan** specializing in **Big Data & Artificial Intelligence**.

### Key Focus Areas

| Area | Technologies |
|------|---|
| **Data Ingestion & APIs** | REST APIs, Custom clients, Event streaming |
| **Storage & Databases** | PostgreSQL, MongoDB, BigQuery, Snowflake |
| **Orchestration & Workflows** | Apache Airflow, Workflow automation |
| **Processing & Analytics** | Spark, Kafka, dbt, Data modeling |
| **Infrastructure** | Docker, Containerization, Cloud-native |

</div>

---

## Featured Project: nexagg

<div class="animated-section">

**Multi-service Data Aggregation Platform**

A containerized, production-ready platform demonstrating end-to-end data engineering:

| Component | Details |
|-----------|---------|
| **Infrastructure** | Docker Compose stack with PostgreSQL, MongoDB |
| **Data Sources** | Riot Games API (Match-v5), Chess.com archives |
| **Database** | Typed, indexed, constrained PostgreSQL schema |
| **Dataset** | Kaggle League of Legends historical data |

**Architecture:**
```
nexagg/
├── docker-compose.yml          # Multi-container orchestration
├── clients/
│   ├── riot_client.py          # Match history ingestion
│   └── chess_client.py         # Game archive retrieval
├── db/
│   └── schema.sql              # Normalized, production schema
└── services/                   # ETL and data processing
```

</div>

---

## Technical Stack

<div align="center">

<div class="tech-grid">

### Data & Analytics
<span class="animated-badge">![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)</span>
<span class="animated-badge">![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)</span>
<span class="animated-badge">![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)</span>

### Machine Learning
<span class="animated-badge">![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)</span>
<span class="animated-badge">![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white)</span>
<span class="animated-badge">![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)</span>

### Cloud & Infrastructure
<span class="animated-badge">![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)</span>
<span class="animated-badge">![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)</span>
<span class="animated-badge">![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)</span>

### Streaming & Messaging
<span class="animated-badge">![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)</span>
<span class="animated-badge">![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)</span>

### Modern APIs
<span class="animated-badge">![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)</span>
<span class="animated-badge">![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)</span>

</div>

</div>

---

## Current Learning

<div class="animated-section">

- **Apache Airflow** - Advanced ETL & pipeline orchestration (IBM/Coursera certification track)
- **Data Warehouse Design** - Dimensional modeling and schema optimization
- **Distributed Systems** - Kafka, Spark, and stream processing patterns

</div>

---

## Highlights

<div class="animated-section">

- End-to-end project experience across the full data pipeline
- Strong focus on data quality, schema design, and architectural patterns
- Comfortable with containerized deployments and DevOps practices
- Active learner pursuing industry certifications

</div>

---

## Performance & Activity

<div align="center" class="stats-container">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=SoulaymaneBoulaich&theme=tokyonight&hide_border=true" width="60%" alt="GitHub Streak Stats" style="animation: slideInUp 1.5s ease-out; border-radius: 10px; transition: transform 0.3s ease;" />

</div>

---

## Open To

<div class="animated-section">

- Data Engineering internships and full-time roles
- ML Engineering opportunities
- Open-source collaboration on data infrastructure projects
- Technical mentorship and knowledge exchange

</div>

---

## Connect & Collaborate

<div align="center">

<div class="link-card" style="animation: bounceIn 0.8s ease-out 0.1s both;">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/soulaymane-boulaich-b08ba532b/)

</div>

<div class="link-card" style="animation: bounceIn 0.8s ease-out 0.2s both;">

[![Portfolio](https://img.shields.io/badge/Portfolio-38BDF8?style=for-the-badge&logo=vercel&logoColor=white)](https://soulaymaneboulaich.netlify.app)

</div>

<div class="link-card" style="animation: bounceIn 0.8s ease-out 0.3s both;">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:soulaiman.boulaich0@gmail.com)

</div>

<br />

<div class="animated-section">

**Always happy to discuss data engineering, ML pipelines, and system design.**

</div>

</div>

---

<div align="center">

<div class="animated-section" style="animation: slideInUp 2s ease-out;">

*Built with attention to detail and a passion for clean architecture.*

</div>

</div>
