# spac-vs-ipo-event-study
Graduate finance research comparing SPAC vs traditional mergers using event study, regression, and WRDS Eventus.
# 📊 SPAC vs Traditional IPO: Event Study & Market Reaction Analysis

This project was conducted as part of my graduate finance coursework at Hofstra University (Spring 2025). It investigates the stock market's short-term reaction to mergers involving SPAC vs. traditional acquirers, using an event study methodology and regression analysis.

---

## 🔍 Objective

Compare cumulative abnormal returns (CARs) for 271 U.S. target firms acquired by:
- ✅ SPACs (n = 137)
- 🔁 Traditional acquirers (n = 134)

Event windows analyzed:  
(0,0), (0,+1), (0,+2), (0,+3), (–1,0), (+1,+10)

---

## 📂 Data & Methodology

- 📊 Data: LSEG SDC Platinum (deals), CRSP (returns)
- 🧠 Method: Market model-based Event Study
- 🛠 Tool: WRDS Eventus (for CARs and Z-stats)
- 📈 Stats: T-tests and OLS regression controlling for:
  - Deal value
  - Target asset size (TASS)
  - Profitability & Market-to-Book ratio
  - Year fixed effects

---

## 📈 Key Results

- SPAC mergers yield **significantly higher CARs** than traditional mergers, especially in (0,+1) and (0,+2) windows
- SPAC coefficient remains positive and significant across regression models
- Deal size is negatively associated with CARs
- Firm fundamentals (profitability, MTB) had no strong short-term impact

---

## 📄 Files

- `SPAC vs IPO Final.pdf`: Full report with tables and regression outputs
- `Market Reactions to SPAC.pptx`: Presentation deck for academic defense
- `SPAC DATA RESULTS.docx`: Eventus output summary for CARs and t-tests

---

## 🙋 My Role

- Extracted data from WRDS & SDC
- Cleaned and analyzed Eventus results
- Conducted t-tests and regressions
- Co-authored report and led insights during defense

---

## 🧠 Learn More

This research contributes to literature on:
- SPAC vs IPO market behavior
- M&A short-term performance
- Event study methodology in finance

---
