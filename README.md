<div align="center">
  <h1>Ghulam Mohyuddin</h1>
  <h3>Data Scientist | ML Engineer</h3>
  <p><strong>BS Software Engineering</strong> • National Textile University • Expected 2027</p>
  <p>
    <a href="https://github.com/ghulammohyuddin-coder">
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github" alt="GitHub"/>
    </a>
    <a href="https://www.linkedin.com/in/ghulam-mohyuddin-047408371/">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
    <a href="mailto:ghulammohyuddin.coder@gmail.com">
      <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
    </a>
  </p>
</div>

---

## 🎯 About Me

I build data systems that think. My focus: transforming raw organizational data into autonomous analytical intelligence through agentic AI pipelines, statistical rigor, and production-grade engineering.

Currently designing **OmniData Engine** — an end-to-end system combining automated data cleaning, schema-aware natural language SQL translation, and relationship inference using LLMs. The outcome: any non-technical person can upload messy data and ask questions in English.

**Why this matters:** 60% of data professional time is wasted on manual cleaning. OmniData eliminates that bottleneck.

---

## 🛠️ Technical Arsenal

**Core Data Science Stack:**
- **Statistical Analysis:** Hypothesis testing, A/B testing, k-fold cross-validation, ROC-AUC, confusion matrix, anomaly detection (Z-score, Isolation Forest)
- **Machine Learning:** Scikit-learn (regression, classification, clustering), feature engineering, time-series forecasting (ARIMA), model evaluation
- **Data Engineering:** Python (Pandas, NumPy), SQL (window functions, CTEs, query optimization), ETL pipelines

**Databases & Query:**
- **SQL:** MySQL, Oracle (PL/SQL: procedures, functions, triggers, cursors, packages, collections), PostgreSQL
- **Data Modeling:** Star Schema, dimensional modeling, relational integrity

**AI & Agentic Systems:**
- **LLM Integration:** LangChain, LangGraph, prompt engineering, schema-aware SQL generation
- **Guardrails:** Read-only database roles, SQL validation layers, hallucination prevention via schema injection

**Visualization & BI:**
- **Power BI:** DAX time-intelligence measures (YTD, MoM), interactive dashboards, Star Schema modeling
- **Python:** Matplotlib, Seaborn, Plotly (interactive charts)
- **Advanced Excel:** XLOOKUP, complex formulas, data validation, Pivot Tables

**Tools & Platforms:**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn"/>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" alt="Plotly"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/LangChain-1C3A4A?style=for-the-badge&logo=chainlink&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/Git-181717?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
</p>

---

## 🚀 Featured Projects

### **OmniData Engine — Agentic Data Analysis Pipeline** ⭐ [In Progress]
**Problem:** Non-technical users are locked out of their own data. Data cleaning takes 60% of analyst time. No accessible tool combines automated preprocessing with natural language querying.

**Solution:** Unified two-module agentic pipeline:
- **CleanQuery Agent** (LangChain): Observes column distributions, dynamically selects imputation strategy (mean/median/mode/forward-fill), detects multivariate anomalies using Isolation Forest
- **InsightFlow Agent** (LangGraph): Schema-injected prompt engineering forces LLM to only reference verified columns. Includes retry loop for self-correcting failed queries. Validation layer blocks destructive SQL
- **Schema Relation Agent:** Infers foreign keys across multi-file uploads automatically

**Tech Stack:** React (frontend), FastAPI (backend), PostgreSQL (database), LangChain/LangGraph (AI), Python (agents)

**Impact:** Any user can upload CSV → system cleans it → user asks "Show me revenue by region" in English → gets interactive chart in seconds

[View Repository](https://github.com/ghulammohyuddin-coder/OmniData-Engine)

---

### **Retail Sales Analytics — SQL + Statistical Analysis**
**Objective:** Analyze 9,694 e-commerce transactions to identify profitability drivers.

**Methods:**
- Data profiling: NULL counts, duplicates, date validation across 21 columns
- Window functions (RANK OVER PARTITION BY) for sub-category ranking within categories
- Aggregation queries with HAVING filters to identify loss-making products
- 4-year trend analysis (2014–2017): identified 51.4% YoY revenue growth

**Key Finding:** High-discount orders (40%+) average **-$106.70 profit** vs **+$66.90** standard pricing — **$173.60 gap per transaction**

**Recommendation:** 20% discount cap, Q4 inventory scaling

[View Notebook](https://github.com/ghulammohyuddin-coder/Data-Analytics-Skill-Building)

---

### **E-Commerce EDA & A/B Testing Framework**
**Objective:** End-to-end data cleaning, feature engineering, and A/B test design for discount strategy.

**Execution:**
- Cleaned 9,994 records (26 columns): dtype normalization, deduplication, null imputation
- Engineered 5 features from dates (Days To Ship, Order Quarter, etc.)
- Generated 6 visualizations revealing discount impact on profit margins
- Formulated statistical hypothesis test: null hypothesis (discount has no effect) vs. alternative (discount reduces profit)
- Calculated sample size and significance level (α=0.05) for valid A/B test

**Output:** Structured testing framework ready for real-world deployment

[View Repository](https://github.com/ghulammohyuddin-coder/Data-Analytics-Skill-Building)

---

### **Power BI Sales Dashboard — Star Schema & DAX**
**Objective:** Replace manual Excel reporting with interactive executive dashboard.

**Architecture:**
- Designed star schema: sales fact table + date/product dimensions
- Built DAX measures: YTD revenue, MoM growth rates, category rankings
- Implemented cross-page navigation with bookmark filters
- Dashboard delivers 5-page interactive report from single dataset

**Result:** Reduced reporting time from 3 days to 5 minutes

[View Details](https://github.com/ghulammohyuddin-coder/Data-Analytics-Skill-Building)

---

## 💼 Professional Experience

**Data Analyst Intern • Klash Private Limited, Faisalabad**  
*July 2026 – August 2026*

- Built 5-page interactive Power BI dashboard with dynamic cross-page navigation using bookmarks and slicers
- Analyzed 9,694+ retail transactions; discovered discount impact: 40%+ discounts generate -$173.60 profit loss per transaction
- Mastered Oracle PL/SQL: stored procedures, functions, triggers, cursors, exception handling, packages, collections
- Connected Power BI to Oracle database; designed and optimized DAX time-intelligence measures
- Documented real-world organizational workflows; learned how data flows through operational systems under production constraints

---

## 📊 Key Competencies

| Domain | Capability |
|--------|-----------|
| **Statistical Analysis** | Hypothesis testing, A/B testing, statistical significance (p-values), confidence intervals, Z-score & Isolation Forest anomaly detection |
| **Machine Learning** | Scikit-learn (regression, classification, clustering), k-fold cross-validation, confusion matrix, ROC-AUC, feature engineering |
| **Time-Series** | Trend analysis, ARIMA forecasting, seasonal decomposition, YoY/MoM growth calculation |
| **Data Quality** | Profiling frameworks, cleaning logs, audit trails, lineage tracking, data validation |
| **SQL Mastery** | CTEs, window functions, subqueries, HAVING clauses, query optimization, relational modeling |
| **AI Integration** | LangChain, LangGraph, prompt engineering, schema injection, LLM guardrails |

---

## 🎓 Certifications

- **IBM Data Science Professional Certificate** (12 courses) — Python, SQL, Data Analysis, Machine Learning, Data Science Methodologies
- **Microsoft Power BI Certificate** — DAX, Star Schema Modeling, Enterprise Dashboard Design
- **AWS AI/ML Scholar** — AI fundamentals, ML algorithms, Deep Learning, Gen AI, Prompt Engineering

---

## 💬 Let's Connect

Open to:
- **Full-time roles:** Data Scientist, ML Engineer, Analytics Engineer
- **Consulting & Freelance:** Data pipeline design, BI solution architecture, predictive modeling
- **Collaborations:** Open-source contributions, research partnerships

<p>
  <a href="mailto:ghulammohyuddin.coder@gmail.com"><strong>Email</strong></a> •
  <a href="https://www.linkedin.com/in/ghulam-mohyuddin-047408371/"><strong>LinkedIn</strong></a> •
  <a href="https://github.com/ghulammohyuddin-coder"><strong>GitHub</strong></a>
</p>

---

<p align="center">
  <strong><em>"Building data systems that don't just analyze — they think."</em></strong>
</p>
