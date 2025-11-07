# ds_preeti

---
##  Project Overview
This project analyzes how **Bitcoin market sentiment** (Fear vs Greed) affects **real trader performance** using data from **Hyperliquid**.

The goal is to uncover patterns between investor emotions and trading outcomes — showing whether fear or greed leads to better results.

---

## 📊 Datasets Used
1. **Bitcoin Market Sentiment**  
   - Source: Fear & Greed Index  
   - Tracks investor emotions daily (Fear, Neutral, Greed)

2. **Trader Data (Hyperliquid)**  
   - Contains trading metrics like:
     - Daily profit/loss (PnL)
     - Trade volume and direction
     - Fees and asset details

After cleaning and merging both datasets by **date**, only **6 overlapping dates** were available for combined analysis.

---

## Key Analysis Steps
1. **Data Cleaning**  
   - Removed duplicates, missing values, and irrelevant columns  
   - Standardized dates and formats  

2. **Data Merging**  
   - Matched market sentiment and trader performance by date  

3. **Exploratory Data Analysis (EDA)**  
   - Visualized profit distributions, trading volumes, and correlations  

4. **Statistical Testing**  
   - Conducted T-test and Mann-Whitney U-test  
   - Measured effect size (Cohen’s d) to evaluate the "Fear Advantage"

---

## 📈 Main Findings
| Metric | Fear Period | Greed Period | Key Insight |
|:--|:--:|:--:|:--|
| **Average PnL** | \$6,699,925 | \$841,645 | Fear periods outperform Greed by 696% |
| **Profit Days** | 100% | 75% | Traders always profitable during Fear |
| **T-test p-value** | 0.0443 | — | Statistically significant at 95% confidence |
| **Effect Size (Cohen’s d)** | 3.74 | — | Very large difference |

**Conclusion:**  
Markets driven by *fear* often present the **best trading opportunities**, contradicting the usual belief that “greedy” markets are more profitable.

---

## 🧩 Limitations & Next Steps
- Only 6 overlapping dates → results are early indicators, not final proof.  
- Expanding dataset (more dates or assets) could improve reliability.  
- Future work could build:
  - Predictive models for sentiment-based trading
  - Real-time dashboards to monitor fear/greed impact

---

## 🧠 Key Takeaways
- **Greed Periods** → More trades, higher risk-taking  
- **Fear Periods** → Fewer trades, but *much* better profits  
- **Overall Message:** Contrarian trading (buying in fear) can statistically outperform optimistic markets.

---

## 👩‍💻 Author
**Preeti Yadav**  
M.Sc. in Bioinformatics | Data Science Enthusiast  
 

---
