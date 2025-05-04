# S&P 500 Intraday News Sentiment Analysis (Mar–Apr 2025)

This project uses Natural Language Processing (NLP) techniques to perform **hourly sentiment analysis** of major S&P 500 stocks based on financial news headlines scraped from Finviz. It aims to identify how investor sentiment evolves in real-time across different sectors in response to macroeconomic and firm-specific events.

We analyze the period from **March 26 to April 15, 2025**, with special attention to companies like **Apple Inc. (AAPL)**, whose sentiment exhibited a sharp reversal aligned with key headlines and analyst actions.

---

##  Key Objectives

- Track **hourly sentiment trends** across top S&P 500 constituents
- Group sentiment patterns by **sector** (Technology, Energy, Healthcare, etc.)
- Identify **spikes or reversals** linked to macroeconomic news (e.g., U.S. tariff policy)
- Visualize sentiment behavior through **bar charts and line plots**

---

##  Example Insight – Apple Inc. (AAPL)

Between **April 13 and 14**, AAPL exhibited consistently **negative sentiment**, likely influenced by concerns over trade tensions and potential supply chain disruptions. On **April 15**, sentiment surged to highly positive levels following major **analyst upgrades** and coverage like:

> *“Apple stock pops 6% as investors bet tariffs ease.”*

This illustrates how investor sentiment can shift rapidly in response to headline framing and analyst narratives — a phenomenon that can be quantified and visualized using NLP.
![AAPL_hourly_sentiment_bar_chart](https://github.com/user-attachments/assets/fcf4185c-e23e-42dc-a20d-de3ef35c8f32)


---

##  Tools & Libraries

- Python (Jupyter Notebook)
- `VADER` for sentiment scoring
- `BeautifulSoup` for web scraping
- `pandas`, `matplotlib`, `seaborn` for visualization
- Data source: [https://finviz.com](https://finviz.com)

---

##  Repository Contents

- `Sentiment_Analysis_S&P500.ipynb`: Main notebook containing data scraping, sentiment scoring, and visualization.
- Hourly sentiment line and bar plots (sector-wide and per stock)
- Charts saved in `/hourly_sentiment_charts/`

---

##  Future Work

- Merge with stock return data (e.g., Yahoo Finance) to test predictive relationships
- Add keyword frequency analysis (e.g., "tariffs", "earnings", "upgrade")
- Build a sector-level sentiment dashboard using Streamlit

---
