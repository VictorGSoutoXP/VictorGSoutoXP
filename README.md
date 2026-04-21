<!-- 
  README de perfil — Victor Gonçalves Souto
  Coloca esse arquivo em: github.com/VictorGSoutoXP/VictorGSoutoXP/README.md
  (repositório com o mesmo nome do usuário = README do perfil)
-->

<h1 align="center">Victor Gonçalves Souto</h1>

<p align="center">
  <b>Data & Forecasting Engineer</b> · Turning messy data into decisions executives can defend.<br>
  <sub>Brazil · Remote-friendly · Available for consulting</sub>
</p>

<p align="center">
  <a href="https://soutoconsultoria.com.br">
    <img src="https://img.shields.io/badge/Souto_Consultoria-0A66C2?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Souto Consultoria">
  </a>
  <a href="mailto:victor@soutoconsultoria.com.br">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://www.linkedin.com/in/victorgsouto/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
</p>

---

## 🇬🇧 About

I build data systems that **executives actually use**: forecasting pipelines, BI dashboards, and decision-support tools that connect raw data to real operational choices.

Currently working on data & analytics at a **Carrefour Group** business unit in Brazil, where I maintain BigQuery pipelines, Looker Studio dashboards, and forecasting models for retail, insurance sales, and digital credit card acquisition — across three banners (Atacadão, Carrefour, Sam's Club).

Outside of that, I run **[Souto Consultoria](https://soutoconsultoria.com.br)** — a small consultancy focused on data engineering, forecasting, and analytics for companies that need rigor without the overhead of a big vendor.

I'm also a cancer survivor. In 2026 I published an independent analysis of **pediatric oncology in Brazil** using public SUS data ([see featured project below](#-featured-project)) — it's how I reconcile the technical work with what actually matters.

---

## 🚀 Featured project

### [🩺 Pediatric cancer in Brazil: treatment delays and registry completeness](https://github.com/VictorGSoutoXP/Oconlogia---Brasil)

Independent analysis of **81,080 pediatric cancer diagnoses** in Brazil's public health system (SUS, 2019-2023), based entirely on open government data.

**Key findings:**
- **5,129 children** waited more than the 60-day legal limit between diagnosis and treatment — direct non-compliance with Law 12.732/2012.
- **54.5% of cases have no treatment record** in the national oncology panel. More than half.
- The "private healthcare" hypothesis that is commonly used to explain this gap does **not** survive the data (r = 0.02 with ANS coverage).

**Stack:** Python, pandas, matplotlib · Public data from DATASUS and ANS · Fully reproducible, MIT-licensed.

**Read the full article (PT-BR):** [Quanto tempo uma criança com câncer espera no Brasil?](https://github.com/VictorGSoutoXP/Oconlogia---Brasil/blob/main/artigo/quanto-tempo-crianca-com-cancer-espera.md)

---

## 🛠️ What I actually do well

**Forecasting in production.** Built an 11-stage ensemble forecasting pipeline for credit card approvals combining SARIMAX, Prophet, ETS, Ridge-Fourier, HistGBM, LightGBM Quantile, and a WhiteBox model, stacked via non-negative least squares with conformal prediction intervals and Monte Carlo simulation.

**BigQuery at scale.** Complex SQL pipelines with CTEs, window functions, dense_rank, and multi-source normalization. Comfortable with long-running queries across denormalized retail data and with debugging gnarly cross-system join issues (CONE duplication, FORMATO mismatches, grand-total double-counting in Looker).

**Dashboards people actually read.** Looker Studio dashboards for store performance, insurance sales vs. targets, hourly productivity, and schedule adherence — built from raw transactional data, not BI-team-friendly marts.

**Analysis that holds up.** Honest backtesting, out-of-sample validation, sensible baselines first, complexity only where it pays off. I report limitations openly — see the [limitations section](https://github.com/VictorGSoutoXP/Oconlogia---Brasil/blob/main/artigo/quanto-tempo-crianca-com-cancer-espera.md#limitações-e-próximos-passos) of my pediatric oncology project for the style.

---

## 🧰 Tech stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white" alt="BigQuery">
  <img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP">
  <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" alt="Oracle">
  <img src="https://img.shields.io/badge/Looker_Studio-4285F4?style=flat-square&logo=looker&logoColor=white" alt="Looker Studio">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/scikit_learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/LightGBM-00A98F?style=flat-square&logoColor=white" alt="LightGBM">
  <img src="https://img.shields.io/badge/Prophet-1C1C1C?style=flat-square&logoColor=white" alt="Prophet">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">
</p>

**Working with:** Python (pandas, NumPy, statsmodels, scikit-learn, LightGBM, Prophet, pmdarima), SQL (BigQuery, Oracle), Looker Studio, Power BI, Git.

**Familiar with:** Unity/C# (side projects), HTML5 Canvas (browser games), basic web (HTML/CSS/JS).

---

## 📜 Certifications & formal learning

- **Microsoft PL-300** (Power BI Data Analyst) — via SENAI
- **Google Data Analytics Professional Certificate**
- **FGV** — Machine Learning
- **Fundação Bradesco / Escola Virtual** — Power BI Data Analysis, Python, Logic & Programming, HTML, Digital Literacy, Information Security
- Additional coursework: Factor Analysis, Multivariate Analysis, Complex Networks, IT Governance, Risk Management, Introduction to Data Science

---

## 📊 Currently

- 🔭 Building **v2.0** of the pediatric oncology project: distance analysis between patients and specialized treatment centers (UNACON/CACON), using CNES data
- 📈 Maintaining production forecasting models for retail performance, insurance sales, and digital credit card acquisition
- 🎮 Side project: **Órbita & Queda** — a browser game set on Saturn's moon Enceladus (Unity + HTML5 versions)
- 📬 Open to consulting work in forecasting, data engineering, and health-data analysis

---

## 💼 Work with me

If you have messy data, an unanswered question, or a forecast that's been wrong for too long:

📧 **victor@soutoconsultoria.com.br**
🌐 **[soutoconsultoria.com.br](https://soutoconsultoria.com.br)**

I take on focused consulting engagements (data pipelines, forecasting, BI architecture, public-data analysis). I prefer projects where the deliverable is something an executive can actually use to make a decision — not another dashboard nobody opens.

---

<details>
<summary>🇧🇷 <b>Em português</b></summary>

<br>

Engenheiro de dados e forecasting, atualmente em uma unidade de negócio do **Grupo Carrefour** no Brasil, mantendo pipelines em BigQuery, dashboards em Looker Studio e modelos de previsão para varejo, venda de seguros e aquisição de cartão de crédito digital nas bandeiras Atacadão, Carrefour e Sam's Club.

Em paralelo, toco a **[Souto Consultoria](https://soutoconsultoria.com.br)** — consultoria focada em engenharia de dados, forecasting e analytics para empresas que precisam de rigor técnico sem o overhead de fornecedor grande.

Sobrevivente de câncer pediátrico (neuroblastoma, diagnosticado aos 6 meses). Em abril de 2026 publiquei uma análise independente sobre **oncologia pediátrica no Brasil** usando dados abertos do SUS — disponível no repositório em destaque acima.

**Áreas de trabalho:**
- Modelos de previsão em produção (ARIMA/SARIMAX, Prophet, ETS, gradient boosting, ensembles)
- Pipelines em BigQuery, Oracle, SQL em geral
- Dashboards executivos (Looker Studio, Power BI)
- Análise de dados públicos de saúde com foco em política pública

**Contato:** victor@soutoconsultoria.com.br

</details>

---

<p align="center">
  <sub>💬 "O objetivo não é adivinhar o futuro, mas produzir distribuições preditivas testáveis que informem decisões sob incerteza."</sub>
</p>
