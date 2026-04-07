<h1 align="center"><b>Hi, I'm Arno Vifian </b><img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35"></h1>

<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Time+New+Roman&color=cyan&size=25&center=true&vCenter=true&width=600&height=100&lines=Welcome+to+my+GitHub!;Quantitative+Economics+Student;Data+Science,+Econometrics,+ML+Enthusiast;Always+seeking+new+challenges+and+projects"></a>
</p>

<br>

##  **About Me**

- Passionate about machine learning, time series, causal inference, and applied data analysis  
- Open source projects focused on data science, modeling, and forecasting  

---

## **1. French Electricity Spot Price Forecasting — MLOps Pipeline**

🔗 **GitHub:** [https://github.com/rav-lad/energy-demand-forecast](https://github.com/rav-lad/energy-demand-forecast)

A production-grade forecasting system trained on **28,405 hourly observations (Jan 2023 – Apr 2026)** of French electricity prices, demand, and weather data.

**Highlights**

* Designed a full **MLOps pipeline** covering data ingestion, feature engineering, model training, inference, and monitoring
* Implemented strict **walk-forward validation** over **~800 days (~19,000 prediction hours)** to eliminate look-ahead bias
* Engineered features combining **price lags (24h, 48h, 168h)**, **net load**, **renewable penetration**, **weather**, and **calendar seasonality**
* Achieved **MAE = 13.41 EUR/MWh** and **R² = 0.831** with **XGBoost**, outperforming the Ridge baseline (**MAE = 14.77**, **R² = 0.806**)
* Reached **78.5% direction accuracy** with Ridge Regression as a fast, robust production baseline
* Built **probabilistic forecasts** with **LightGBM quantile regression**, producing **P10/P50/P90 intervals** with **63% empirical coverage** and **33 EUR/MWh average interval width**
* Deployed a fully containerised architecture with **6 Docker services**, **GitHub Actions CI/CD**, and a **4-page Streamlit monitoring dashboard**
* Added drift monitoring and retraining alerts using **PSI > 0.25** or **20% degradation in 30-day MAE**

## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="25"> **Local Agents with Ollama** ![Ollama](https://img.shields.io/badge/Ollama-Local%20AI-000000?style=flat-square&logo=ollama&logoColor=white)

## **1. Scoring Agent — Real-Time Market Intelligence System**

🔗 **GitHub:** https://github.com/rav-lad/scoring-agent

A **local-first multi-agent system** designed to detect abnormal and potentially informed market activity in real time across crypto markets.

The system combines statistical anomaly detection, behavioral wallet profiling, and agent-based reasoning to produce a **0–100 suspicion score**, along with structured investigation outputs.

**Highlights**

* Built a fully **local architecture powered by Ollama**, ensuring privacy and low-latency inference
* Designed a **multi-stage pipeline**: anomaly filtering → agent investigation → deterministic scoring
* Monitors multiple data sources: **on-chain flows, mempool activity, and derivatives markets**
* Implements specialized agents for **security checks, behavioral analysis, macro context, and quant validation**
* Generates structured reports and **real-time webhook alerts** for high-risk events
* Includes a **Rust-based terminal dashboard (TUI)** for live monitoring and system observability  

---

## **2. Agent Orchestrator — Multi-Agent Research System**

🔗 **Orchestrator:** https://github.com/rav-lad/agent-orchestrator  
🔗 **News Agent:** https://github.com/rav-lad/news-analyst  
🔗 **Macro Agent:** https://github.com/rav-lad/macro-analyst  

A modular **local-first orchestration framework** that coordinates specialized AI agents to produce structured, decision-ready analysis.

The system integrates domain-specific agents (news and macro) into a unified research pipeline, enabling consistent and reproducible outputs.

**Highlights**

* Designed a **multi-agent orchestration layer** to coordinate agent execution and workflows  
* Integrates specialized agents:
  * **News Analyst** → extracts key events, narratives, and market-relevant signals from news flows  
  * **Macro Analyst** → provides macroeconomic context and regime-level interpretation  
* Produces **structured analytical outputs** usable in systematic workflows  
* Focus on **reproducibility, modularity, and extensibility**  
* Fully **local via Ollama**, ensuring privacy and full control over models and data  

## <img src="https://media.giphy.com/media/3o7btPCcdNniyf0ArS/giphy.gif" width="25"> **Kaggle Competitions**

🔗 **Repository:** https://github.com/rav-lad/Kaggle-

A collection of my Kaggle competition work, including feature engineering, model development, and evaluation pipelines across various datasets and problem types.

| Competition | Link | Rank / Score |
|------------|------|--------------|
| Binary Classification with a Bank Dataset | https://www.kaggle.com/competitions/playground-series-s5e8 | Top 4% (129/3365)   |
| Predicting the Beats-per-Minute of Songs | https://www.kaggle.com/competitions/playground-series-s5e9 | Top 7% (177/2581) |
| Exploring Mental Health Data | https://www.kaggle.com/competitions/playground-series-s4e11 | Top 8% (223/2685) |


## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width ="25"> **Skills**

<p align="center">

##  Languages  
![Python](https://img.shields.io/badge/Python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-%2307405e.svg?style=for-the-badge&logo=mysql&logoColor=white)

<br>

##  Data Science & Analysis  
![scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-0099C4?style=for-the-badge)
![LightGBM](https://img.shields.io/badge/LightGBM-341A19?style=for-the-badge)
![Stata](https://img.shields.io/badge/Stata-0057B8?style=for-the-badge&logo=stata&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft%20365-EB3C00?style=for-the-badge&logo=microsoft&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)

<br>

##  Cloud & AWS Ecosystem  
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![SageMaker](https://img.shields.io/badge/SageMaker-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Bedrock](https://img.shields.io/badge/Bedrock-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Glue](https://img.shields.io/badge/Glue-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Athena](https://img.shields.io/badge/Athena-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=aws-lambda&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazon-ec2&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white)

**_AWS Certified AI Practitioner_**

<br>

##  Tools & Development  
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-0078d7?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

<br>

##  GenAI, APIs & Visualization  
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFB94B?style=for-the-badge&logo=huggingface&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)


###  Other  
French (native), English (fluent)

</p>

##  **Let's Connect!**
<br>

<p align="left">

<a href="https://www.linkedin.com/in/arno-vifian-732478278/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-arno--vifian-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
</a>

<a href="mailto:arno.vfn@gmail.com" target="_blank">
  <img src="https://img.shields.io/badge/Gmail-arno.vfn-red?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail Badge"/>
</a>

<a href="https://devpost.com/2Fick" target="_blank">
  <img src="https://img.shields.io/badge/Devpost-Profile-003E54?style=for-the-badge&logo=devpost&logoColor=white" alt="Devpost Badge"/>
</a>

<a href="https://www.kaggle.com/ravvvvvvvvvvvv" target="_blank">
  <img src="https://img.shields.io/badge/Kaggle-ravvvvvvvvvvvv-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle Badge"/>
</a>

</p>

---

<div align="center">

##  **Thanks for visiting!**

</div>

---

Credit: Inspired by [Abdul Khalid](https://github.com/0xabdulkhalid)  
Last Edited on: 04.04.2026
