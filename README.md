# Hi there 👋, I'm Nawar Toumi

💡 **Passionate about data, LLMs, and building smart data pipelines.**  
➡️ Data Engineer turning data into intelligent and high-performance solutions.  

---

## 🧑‍💻 About Me
- 🔧 Data Engineering & DataOps (ETL/ELT, orchestration, CI/CD, monitoring).  
- 🚦 Designed a **Smart Data Pipeline for Smart Cities** (Databricks, Delta Lake, Power BI, Random Forest) to manage traffic flow and detect congestion.  
- 🤖 Keen interest in **data pipelines**, **Generative AI**.  
- 🎯 Goal: transforming data into measurable business value.  

---

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Hadoop](https://img.shields.io/badge/Apache%20Hadoop-66CCFF?style=for-the-badge&logo=apache&logoColor=black)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white)

---

## 📌 Featured Projects  
- 🚦 **Smart Data Pipeline (Smart Cities)** – Big Data pipeline on Databricks for urban traffic management.
- 🧠 **AI Agents Automation (SMEs)** – Built agents for appointment scheduling, document generation, and client follow-ups.  
- 📝 **Handwritten Digit Recognition** – CNN deployed on Raspberry Pi (93% accuracy).  
- 🎥 **Video Super-Resolution (ESRGAN)** – Improved video quality using Generative AI.  
- 🩺 **Skin Cancer Detection** – CNN on Raspberry Pi for real-time skin cancer detection.  

---

## 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nawartm&show_icons=true&theme=tokyonight&cache_seconds=3600" alt="GitHub Stats" height="180" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nawartm&layout=compact&theme=tokyonight&cache_seconds=3600" alt="Top Languages" height="180" />
</p>

---

## 🔥 GitHub Streak
<p align="center">
  <img src="https://streak-stats.demolab.com?user=nawartm&theme=tokyonight" alt="GitHub Streak" />
</p>

---

## 🐍 Snake Graph
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"   # tous les jours à 00:00 UTC
  workflow_dispatch:       # permet de lancer manuellement
  push:
    branches: [ main ]

permissions:
  contents: write          # autorise l'écriture sur le repo

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4

      # Génération du SVG
      - name: Generate snake SVG
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: nawartm
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      # Publication dans la branche "output"
      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

---

## 🌍 Languages  
- 🇲🇦 **Arabic**: Native  
- 🇫🇷 **French**: Fluent  
- 🇬🇧 **English**: Intermediate  

---

## 🌐 Connect with Me  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nawar-toumi/)  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nawartm)  
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nawar.toumi01@gmail.com)  

---

⭐️ **Data is the new oil, but AI is the engine that makes it valuable.**  

