<div align="center">
  <img src="https://github.com/user-attachments/assets/f7663c52-ff16-4e6f-a7cd-7cb43032a478" width="400" alt="Superbad Sup" />
  <h1 align="center">
    I'm Manoj Gowda 👋
  </h1>

  <h3 align="center">
    <img src="https://readme-typing-svg.herokuapp.com?font=Press+Start+2P&weight=400&size=18&pause=1000&color=20C20E&center=true&vCenter=true&width=1000&lines=Analytics+Engineer+%7C+Data+Modeler+%7C+Pipeline+Architect" alt="Typing SVG" />
  </h3>
</div>  


<p align="center">
  <a href="https://linkedin.com/in/mgvm2805"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:vmanojgowda27@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logoColor=white"/></a>
  <a href="https://manojgowda27.github.io/portfolio"><img src="https://img.shields.io/badge/Portfolio-20C20E?style=for-the-badge&logoColor=white"/></a>
  <a href="https://public.tableau.com/app/profile/mgvm/vizzes"><img src="https://img.shields.io/badge/Tableau-8A2BE2?style=for-the-badge&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ManojGowda27&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</p>

---

## 📖 About Me

I am an **Analytics Engineer** specializing in bridging the gap between raw data and decision-making. My work focuses on building **trusted analytics layers** and scalable **ELT pipelines** that actually withstand production environments.

Unlike standard data dumps, I focus on the *reliability* of the ecosystem. Whether it's **optimizing billing analytics** for finance teams or **refactoring ingestion logic** to prevent memory failures, I treat data models as products.

* 🔭 **Currently working on:** Advanced dbt modeling and establishing data governance frameworks.
* 💡 **Interested in:** Distributed systems, Data Lakehouse architectures, and identifying "silent failures" in data pipelines.
* 🎓 **Alumni:** MS in Computer Science, University of Massachusetts Lowell.

---

---

## 💼 Professional Experience Highlights

| Role | Impact |
|------|--------|
| **Billing Data Analyst @ Lob** (Currently Working) | Reduced report generation time by **30%** by unifying pricing/tracking data into trusted dbt models. Automated validation tests to ensure strict financial governance. |
| **Data Analyst @ ElevateMe** | Engineered statistical models for customer segmentation and built real-time ETL pipelines using Python and Spark. |
| **Data Analyst @ InfoTrack** | Optimized SQL queries for extraction, boosting supply chain efficiency by **15%**. |

---

## 🛠️ Tech Stack & Tools

I choose tools based on the problem at hand—reliability for finance, throughput for streaming.

<p align="center">

**Analytics Engineering & Warehousing**
<br>
<img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white"/>
<img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white"/>
<img src="https://img.shields.io/badge/Redshift-8C4FFF?style=for-the-badge&logo=amazonredshift&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>

**Orchestration & Transformation**
<br>
<img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS_Glue-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>

**Languages & Visualization**
<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Looker-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
<img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white"/>

</p>

---

## 🚀 The Story Behind The Code (Featured Projects)

*A showcase of not just "what" I built, but "why" I built it that way.*

## Featured Projects

<table>
<tr>
  
<td width="50%">
  
  ### 1. Reddit Data Lakehouse Pipeline
  **The Problem:** I needed to handle high-volume data ingestion without crashing worker nodes due to memory constraints.
  
  **The Evolution:**
  * *Iteration 1:* Basic list-based loading (O(N) memory complexity) which caused OOM failures.
  * *Iteration 2:* Refactored to **Python Generators** (lazy evaluation), reducing memory complexity to **O(1)**.
  * *Architecture:* Implemented an atomic extract-load pattern on **Apache Airflow** to resolve distributed race conditions across nodes.
    
  **Outcome:** A stable Star Schema in **Redshift** with automated schema inference via **AWS Glue**.
  
  [![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/ManojGowda27/reddit-aws-lakehouse)
  
</td>
<td width="50%">
  
  ### 2. Realtime Data Streaming Architecture
  **The Problem:** The legacy TCP prototype lacked backpressure handling, meaning any consumer downtime or network lag resulted in permanent data loss.
  
  **The Evolution:**
  * **Resilience:** Replaced legacy TCP with **Apache Kafka** & **Spark Structured Streaming** to guarantee zero data loss and replayability.
  * **Intelligence:** Integrated **OpenAI GPT-3.5** for real-time sentiment analysis, implementing selective filtering to minimize API costs.
  * **Infrastructure:** Deployed a fully containerized microservices ecosystem (Zookeeper, Kafka, Spark) using **Docker Compose**.

**Outcome:** A fault-tolerant, real-time pipeline capable of high-throughput ingestion, stream processing, and indexed search.
  
  [![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/ManojGowda27/Realtime_Data_Streaming)
  
</td>

</tr>
</table>


<p align="center">
  <i>"Good data engineering is invisible. If I do my job right, you simply trust the numbers."</i>
</p>

<p align="center">
  <b>Let's connect!</b><br>
  <a href="https://linkedin.com/in/mgvm2805">LinkedIn</a> • <a href="mailto:vmanojgowda27@gmail.com">Email</a>
</p>
