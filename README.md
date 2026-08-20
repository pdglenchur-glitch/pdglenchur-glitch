# Paul Glenchur
MSBA Candidate at Georgetown University | Baseball Data Analyst at Georgetown University | Technical Intern Providing Data Analysis at FINRA
-----

I create analytical tools that turn raw data into actionable insights across a variety of industries. I am always curious, and looking to provide explanations that will create value for your organization. 

-----
## Projects

## Pitcher Report Builder ⚾️
This web application visualizes baseball-specific motion-capture data to create easily interpretable reports for player, coaches, and anyone of interest.

[View project](https://github.com/pdglenchur-glitch/Pitcher-Report-App-Yakker-) 

### Demo Video

[![Watch the Demo](https://img.youtube.com/vi/TIYtF9WfKQk/0.jpg)](https://youtu.be/TIYtF9WfKQk)

-------

## Linkedin User Prediction App 📱
This project predicts the probability that an individual is a Linkedin user depending on a series of demographic factors. This application was created as part of a project for the Georgetown MSBA program, utilizing public data from Pew (to be used for educational and training purposes only).

[View Project](https://github.com/pdglenchur-glitch/Linkedin_Log_Reg)

------- 

## Nike Competitive Analysis Dashboard
This project analyzes Nike's financial statements vs. Adidas, Lululemon, and Under Armour, FY2023–2025. The project normalized four companies' financials (multi-currency, multi-fiscal-calendar) into a PostgreSQL model, caught and fixed three real data-quality bugs during a source-reconciliation audit, and shipped a live Tableau dashboard.

**Stack:** PostgreSQL (window functions, generated columns, views) · SQL data modeling · Tableau

<img src="https://raw.githubusercontent.com/pdglenchur-glitch/nike_competitive_analysis/main/nike_dashboard_ss.png" width="600">

### Key Insights:
- **Profit is falling ~4x faster than revenue.** Nike's FY2025 revenue fell 9.84% YoY, but net income fell 43.5%, driven by real margin compression (gross margin -1.83pp, operating margin -4.30pp).
- **DTC is shrinking faster than Wholesale, the opposite of the pattern elsewhere in the set.** NIKE Direct revenue fell 12.86% YoY, nearly double Wholesale's 7.27% decline, alongside a 12.71% drop in Greater China, Nike's weakest region.
- **Nike's operating-margin lead over Adidas has fully evaporated in two years.** Nike led by 10.3 points in FY2023 (11.55% vs. 1.25%); by FY2025 Adidas leads Nike by 0.3 points (8.29% vs. 7.99%).
- **Nike's "Direct" push hasn't actually moved its channel mix.** Nike's DTC share (~42%) is barely different from Adidas's or UA's (~40%), while Lululemon's unique mix (~90% DTC) coincides with the group's highest net margin (14.22%).
- **Nike is still the largest brand by far, but contracting almost as fast as the most distressed one.** Nike is 51% of the group's FY2025 revenue, yet its 9.84% revenue decline nearly matches Under Armour's 9.43%, while Adidas and Lululemon both grew.

[View the Dashboard Here](https://public.tableau.com/views/Nike2025CompetitiveAnalysis/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---------

## 📊 ESOP Ownership Trends Tableau Dashboard

Interactive visualization analyzing national ESOP statistics from the NCEO dataset.

<a href="https://pdglenchur-glitch.github.io/esop_dashboard/">
  <img src="https://raw.githubusercontent.com/pdglenchur-glitch/esop_dashboard/main/assets/esop_preview.png" width="700">
</a>

### Key Insights
- Publicly traded companies are only 8.1% of ESOPs but hold 82.5% of participants and 83.4% of assets. The average public ESOP holds ~$2.85B vs. ~$50M for private plans.
- Plan count fell 2.5% from 2014–2022 (6,718 → 6,548) while participants grew 6.5% (14.05M → 14.96M), pointing to consolidation into larger plans.
- Manufacturing, Professional Services, and Construction make up over half of all ESOP companies; California leads in plan count (781), while Arkansas stands out with ~43K participants per plan, nearly 20x the national average.

[View the Dashboard Here](https://public.tableau.com/views/ESOPDataDashboard/ESOPDataDashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

--------

## Pitcher Report Builder SQL/Tableau Iteration
This project rebuilds the visualization output from the Pitcher Report Builder web application utilizing SQL and Tableau. The end to end process generates a processed CSV file that is then used to create an interactive Tableau visualization to further examine pitcher performance.

[View the Dashboard](https://public.tableau.com/shared/RHDJN4G2Z?:display_count=n&:origin=viz_share_link)

<img width="500" height="300" alt="Screenshot 2026-01-05 182321" src="https://github.com/user-attachments/assets/53c5ad6b-709e-40a3-93cd-2bdfdc734b2b" />

-------

## 📈 Market & AI Pulse
An end-to-end data analytics pipeline that sources market, macroeconomic, and AI-sector data from five live APIs, models it through a SQL-based medallion (bronze/silver/gold) architecture on Databricks, and publishes a free, automatically refreshing public dashboard on a daily cron with zero manual intervention.

**Stack:** GitHub Actions (orchestration) · Databricks (PySpark, Unity Catalog, medallion architecture) · Python · Cloudflare R2 · Static JS dashboard on GitHub Pages

<a href="https://pdglenchur-glitch.github.io/market_ai_pulse/">
  <img src="https://raw.githubusercontent.com/pdglenchur-glitch/market_ai_pulse/main/screenshots/DB_1.png" width="600">
</a>
<a href="https://pdglenchur-glitch.github.io/market_ai_pulse/">
  <img src="https://raw.githubusercontent.com/pdglenchur-glitch/market_ai_pulse/main/screenshots/DB_2.png" width="600">
</a>

### Key Insights
- **AI-sector concentration keeps paying off:** an AI-weighted basket is beating the S&P 500 by 66.8 points over the trailing year (+90.2% vs. +23.4%).
- **AI infrastructure names outran the core basket, at nearly double the volatility**, with 3 of 10 individual names still underwater despite the group's return.
- **10 of 11 S&P sectors show a reliable rate-sensitivity pattern**, useful for positioning ahead of a known Fed decision, with Energy the lone consistent exception.

[View the Live Dashboard](https://pdglenchur-glitch.github.io/market_ai_pulse/) · [View the Repo](https://github.com/pdglenchur-glitch/market_ai_pulse)
