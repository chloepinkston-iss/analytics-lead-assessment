# ISS STOXX — Analytics Lead Assessment
## Deriving Financial Insights
**Estimated Time:** 6–10 hours (please do not exceed ~12 hours)

---
## Overview
You are working on a financial analytics platform that integrates **structured** (numeric financial data) and **unstructured** (earnings call transcripts) information to generate insights for analysts.

You are provided with two datasets:
- **structured_financials_clean.csv** — quarterly financial metrics for 25 companies (2022–2024)
- **transcripts_25_tickers_2022_2024.csv** — earnings call transcripts (12 per company)

An optional starter notebook is also provided:
- **candidate_template.ipynb**

The goal is to evaluate your ability to:
- Clean, join, and derive insights from messy real-world data
- Apply NLP/text analytics
- Build simple models (optional)
- Design a data model and pipeline
- Communicate results clearly

---
## Part 1: Data Processing (Python)
Using Python (Jupyter / VS Code):
- Load and clean both datasets
- Join the structured and unstructured data
- Create **at least two** derived features (e.g., margins, revenue growth, trend indicators)
- Document assumptions and decisions

---
## Part 2: NLP / Text Analysis
Apply NLP techniques to extract insights from transcripts.
Examples:
- Sentiment analysis
- Topic modeling
- Keyword/phrase extraction
- Embeddings or clustering

You may use libraries such as spaCy, scikit-learn, HuggingFace, or LLM APIs.

Then:
- Aggregate NLP results appropriately (e.g., by company or quarter)
- Compare textual signals to financial performance

---
## Part 2B (Optional): Modeling
If time allows, build a simple predictive model. Options include:
- Predicting revenue growth direction (up/down)
- Sentiment classification
- A risk indicator

Requirements:
- Train 1–2 models (e.g., logistic regression, tree-based)
- Define input features & target variable
- Evaluate using standard metrics
- Compare models and discuss performance

*Note: Focus on reasoning, not model complexity/performance.*

---
## Part 3: Data Modeling & Transformation
Design how this data should be structured for analytics.

### Provide:
- **Logical data model** (fact/dimension tables, grain, keys)
- **Transformation layer** (Python or SQL examples)
- **Pipeline design** (describe ingestion → transformation → storage → analytics)

This can be written, diagrammed, or tabular.

---
## Part 4: Dashboard (Power BI or Tableau)
Build a dashboard that communicates key insights.

### Dashboard Requirements:
- Key financial metrics
- Text/NLP-based insights
- At least one visualization that conveys a meaningful/interesting insight
- Filters for: **Company**, **Sector**, **Region** (if applicable)

---
## 📝 Part 5: Insights & Write-Up
Provide a short write-up (≈1 page, or in the notebook) covering:
- Key insights from your analysis
- Data quality issues identified
- NLP approach chosen and why
- Modeling approach (if completed)
- Limitations of your solution
- What you would improve with more time

---
## Deliverables
Submit:
1. **Python notebook (.ipynb)** or script
2. **Dashboard file** (Power BI or Tableau)
3. **Short write-up** (PDF, Word, or README)

You may zip these into one archive.

---
## ✔ Tools Allowed
- Python (Jupyter / VS Code)
- Power BI or Tableau
- SQL (optional)
- External libraries and AI tools (explain your approach)

You may use any open-source tools, but ensure you can explain your methodology.
