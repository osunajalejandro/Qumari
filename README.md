# Qumari
### Quantitative Market Regime & Risk Intelligence

Qumari is a quantitative research project focused on identifying latent financial market regimes and evaluating how regime-aware portfolio allocation can improve risk management.

The project combines financial data engineering, statistical modeling, and portfolio backtesting to investigate how changing macroeconomic and credit conditions influence market risk.

## Project Objectives

- Identify latent market regimes using macroeconomic and financial indicators.
- Implement a Hidden Markov Model (HMM) for probabilistic regime detection.
- Analyze relationships between market regimes and portfolio risk.
- Develop a regime-aware risk allocation strategy.
- Evaluate performance against traditional allocation baselines.
- Prioritize drawdown protection, risk management, and model interpretability over return maximization.
- Implement a Retrieval-Augmented Generation (RAG) system to retrieve and contextualize relevant financial and macroeconomic information.
- Incorporate SEC filings as a qualitative information source.

## Project Scope

### 1. Financial Data
- US Treasury yield curve spreads (10Y–2Y).
- Corporate credit spreads.
- Historical financial time-series data.
- Data ingestion, preprocessing, validation, and storage.

### 2. Market Regime Detection
- Gaussian Hidden Markov Model.
- Hidden state estimation and transition probabilities.
- Regime classification and probability distributions.
- Model sensitivity and stability analysis.
- Economic interpretation of detected regimes.

### 3. Portfolio Risk & Allocation
- Static allocation baseline.
- Volatility-targeted allocation baseline.
- HMM-based regime-aware allocation.
- Risk budgeting and allocation adjustments.
- Transaction costs and portfolio turnover.

### 4. Backtesting & Evaluation
- Historical strategy simulation.
- Out-of-sample evaluation.
- Walk-forward validation.
- Sharpe and Sortino ratios.
- Maximum drawdown and annualized volatility.
- Stress-period and sensitivity analysis.

### 5. RAG & Explainability
- Documented modeling assumptions.
- Auditable allocation decisions.
- Factor attribution and performance reporting.
- Potential future integration of an LLM-based RAG layer for contextual analysis of FOMC communications and SEC filings.

## Technology Stack

| Component | Technology |
|---|---|
| Primary Language | Python |
| Data Processing | Pandas, NumPy |
| Statistical Modeling | SciPy, Statsmodels |
| Machine Learning | Scikit-learn |
| Regime Detection | hmmlearn |
| Data Visualization | Matplotlib, Plotly |
| Database | PostgreSQL |
| Backend / API | Django + Django REST Framework |
| Testing | Pytest |
| Version Control | Git, GitHub |
| Containerization | Docker |

*The stack is provisional and may evolve as implementation requirements become clearer.*

## Project Architecture

```text
Financial Data Sources
        |
        v
Data Ingestion & Validation
        |
        v
Data Processing & Storage
        |
        v
Feature Engineering
        |
        v
Market Regime Detection
    (Gaussian HMM)
        |
        v
Risk Allocation Engine
        |
        v
Portfolio Backtesting
        |
        v
Performance Evaluation
        |
        v
Reporting & Visualization
```

**JaiFer Initiative**  
Collaborative quantitative research and engineering project.