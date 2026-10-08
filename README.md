# Hi, I'm Aymen 👋

B.Sc. student in Statistics and Data Science at LMU Munich (minor: Economics). I build carefully evaluated projects across applied statistics, quantitative finance, machine learning and LLM systems, from small analyses to a full RAG application running in the cloud.

🎓 Statistics & Data Science, LMU München — since 2024
📍 Munich, Germany
🗣️ Arabic & French (native) · German & English (fluent)
🛠️ Python · R · SQL · PyTorch · Power BI · SAP · Excel
☁️ PostgreSQL + pgvector · FastAPI · LangChain · LangGraph · Docker · GitHub Actions · Azure

## Featured project

### [paper-tutor](https://github.com/AymenFeki/paper-tutor)
A study assistant that answers questions only from a curated database of 7,000+ research papers, cites its sources, and refuses when nothing relevant is found.

- **Data pipeline:** OpenAlex papers filtered by credibility rules (venue list, retractions, spam preprint servers), deduplicated, embedded in PostgreSQL + pgvector
- **Retrieval:** vector search + cross-encoder reranking + a calibrated relevance threshold; evaluated on 444 pooled relevance judgments (hit@5 30/34, MRR 0.76, 84/84 correct answer/refuse decisions)
- **Apps:** FastAPI service, LangGraph tutor with memory, Streamlit chat, MCP tool for Claude Desktop, n8n automations (daily Telegram quiz, weekly paper refresh)
- **Cloud:** Docker image built by GitHub Actions, deployed on Azure Container Apps with Azure PostgreSQL and the Groq API, scale-to-zero and API-key auth

`Python · PostgreSQL · pgvector · FastAPI · LangChain · LangGraph · MCP · n8n · Docker · Azure`

## More projects

| Project | What it does | Stack |
|---|---|---|
| [turbofan-rul-prediction](https://github.com/AymenFeki/turbofan-rul-prediction) | Predicting remaining useful life of jet engines from sensor time series — gradient boosting vs LSTM, 1D-CNN and Transformer, with calibrated prediction intervals and SHAP explanations | Python / PyTorch |
| [Robust-covariance-portfolios](https://github.com/AymenFeki/Robust-covariance-portfolios) | Covariance shrinkage & eigenvalue-clipping estimators for portfolio construction, validated via walk-forward backtesting through the 2008 crisis | Python |
| [options-pricing-basics](https://github.com/AymenFeki/options-pricing-basics) | Option pricing from scratch — binomial tree, Black-Scholes, Monte Carlo — with measured convergence rates, delta hedging, and exotic payoffs | Python |
| [life-expectancy-analysis](https://github.com/AymenFeki/life-expectancy-analysis) | Multi-method analysis of global life expectancy (2000–2015): OLS, mixed-effects models, LASSO, ridge classification, hypothesis testing | R |
| [stats-concepts-lab](https://github.com/AymenFeki/stats-concepts-lab) | Interactive Shiny app for building intuition on the CLT, Type I error/power, and confidence interval coverage — via live simulation | R / Shiny |
| [ab-testing-analysis](https://github.com/AymenFeki/ab-testing-analysis) | A/B test simulation and statistical analysis — hypothesis testing, confidence intervals, power analysis, with full test coverage and CI | Python |
| [pbi-job-market](https://github.com/AymenFeki/pbi-job-market) | Power BI dashboard analyzing salaries across 95K data/stats job postings — star schema, DAX measures, regional pay comparisons | Power BI |
| [Social-Inequality](https://github.com/AymenFeki/Social-Inequality) | University practical project — international panel data on social inequality, cleaned and merged, with trends over time and cross-country comparisons | R |

## Get in touch

📫 Fekiaymen04@gmail.com
