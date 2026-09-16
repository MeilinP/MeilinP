# Meilin Pan

**Quantitative Research | Machine Learning | Data Science**

I am an applied data scientist and quantitative researcher with an M.S. in Applied Data Science from the University of Southern California and a B.S. in Statistics and Data Science from the University of California, Santa Barbara.

I currently research systematic equity signals as a WorldQuant BRAIN Research Consultant. My interests sit at the intersection of statistical modeling, machine learning, financial markets, and reproducible research.

I have engaged in independent discretionary options trading since October 2024, with a focus on volatility, option pricing, Greeks, position construction, and risk management.

## Selected Work

### Quantitative Research and Financial Modeling

- **[Derivatives Pricing & Risk](https://github.com/MeilinP/derivatives-pricing-risk)**  
  End-to-end chain from market quotes to a risk number: a 40-year SOFR OIS curve bootstrapped from SR3 futures and swaps under exact market conventions, a SABR calibration of the SPY implied-volatility surface with static-arbitrage diagnostics, Greek P&L attribution on an eight-leg option book with FRTB PLA testing, and a VaR/ES and stress-testing framework documented to SR 11-7. Second-order Greek terms cut unexplained P&L by 87.6%; the validation report states the framework's failures alongside its results.

- **[Alpha Research Orchestrator](https://github.com/MeilinP/Alpha-Research-Pipeline)**  
  Offline-first, evidence-gated research engine for WorldQuant BRAIN alpha research. A SQLite ledger records every candidate's identity, state transitions, and gate decisions, so every surviving alpha is reconstructable and auditable rather than a black box; deterministic code owns validation, routing, and limits, while an LLM can only propose. Ships a CLI and a local MCP server — no submission capability, every candidate stops at human review. Built on this pipeline: [36 equity alphas](https://github.com/MeilinP/worldquant-iqc-2026) for WorldQuant IQC 2026, finishing 578th of 152,452 participants globally (top 0.4%).

- **[IMC Prosperity 4 Review](https://github.com/MeilinP/imc-prosperity-4-review)**  
  Reconstructed and evaluated trading strategies across market making, options, auctions, and multi-asset relative value using market replay, order reconciliation, and P&L attribution.

### Machine Learning and Data Systems

- **[Audio Event Detection and Notification System](https://github.com/MeilinP/dsci560_final_project)**  
  Group project integrating mobile audio collection, AWS EC2, SageMaker inference, and automated alerts. I was responsible for data preprocessing and model training.

- **[Hybrid Recommendation System](https://github.com/MeilinP/hybrid-recommender-system)**  
  Built a PySpark-based rating prediction pipeline combining collaborative filtering with XGBoost and gradient-boosting models using user, business, check-in, photo, and interaction features.

- **[Two-Stage Recommender, Bandit & A/B Evaluation](https://github.com/MeilinP/feed-reco-lab)**  
  Extends the recommender above into a full ranking system: CF retrieval → LambdaMART learning-to-rank → LinUCB contextual-bandit re-ranking → offline A/B evaluation. On the real 455K-rating Yelp dataset, item-CF retrieval beats a popularity baseline by 3.8x NDCG@10; the A/B harness adds CUPED variance reduction and always-valid (mSPRT) significance testing.

- **[Credit Portfolio Analytics](https://github.com/MeilinP/credit-portfolio-analytics)**  
  End-to-end consumer-credit case study: SQL portfolio analytics, a PD model (logistic regression + XGBoost, AUC 0.767) with a fair-lending disparate-impact check, decile-level risk-return pricing, and KMeans customer segmentation, delivered as a dashboard and a one-page executive summary. Declining or repricing the riskiest 40% of the book lifts modeled portfolio profit by 184%.

## Highlights

- WorldQuant International Quant Championship 2026: **top 0.4% globally**
- IMC Prosperity 4: **top 3.1% overall**, 10th in China
- Independent discretionary options trading experience since October 2024
- Experience researching equity signals across 10 global regions and 50,000+ data fields
- Experience analyzing semiconductor telemetry and test logs with Python and SQL

## Tools

- **Programming:** Python, SQL, R
- **Machine Learning:** PyTorch, scikit-learn, XGBoost, statsmodels
- **Data:** pandas, NumPy, SciPy, PySpark, Polars
- **Cloud and Systems:** AWS EC2, SageMaker, Git
- **Quantitative Methods:** option pricing and Greeks, volatility-surface modeling, interest-rate curve construction, market microstructure, stochastic processes, time-series analysis, Monte Carlo simulation, numerical optimization, statistical arbitrage, backtesting, and P&L attribution

## Connect

- [LinkedIn](https://www.linkedin.com/in/meilinp123/)
