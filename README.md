# 🏏 T20 World Cup Analysis — Best Playing XI (Power BI)

End-to-end data analytics project that scrapes T20 World Cup match data from the web, processes it with Python, and builds an interactive **Power BI** dashboard to select the **best possible playing XI** based on data-driven performance metrics.

## 📌 Business Problem
Selecting a balanced cricket team is often driven by intuition. The goal here is to remove guesswork and pick the **optimal 11 players** (openers, anchors, finishers, all-rounders, specialist bowlers) using objective batting and bowling KPIs from the tournament.

## 🛠️ Tools & Tech
- **Web Scraping:** JavaScript (browser console) to extract batting, bowling, match and player data
- **Data Processing:** Python (pandas) in Jupyter Notebook — cleaning, transformation, feature engineering
- **Visualization & Modeling:** Power BI (Power Query, DAX measures & calculated columns)

## 📊 Approach
1. **Scrape** raw batting/bowling summaries, match results and player info (see `code/web_scraping/`).
2. **Pre-process** and clean the data into analysis-ready tables (`code/data_preprocessing/`).
3. **Model & visualize** in Power BI with custom DAX measures (strike rate, batting average, boundary %, economy, bowling strike rate, etc.).
4. **Define roles & filters** to shortlist the best XI by batting position and bowling type.

## 🗂️ Repository Structure
```
├── code/
│   ├── web_scraping/            # JS scripts used to scrape T20 WC data
│   └── data_preprocessing/      # Python notebook (pandas) for cleaning & transformation
├── data/                        # Raw scraped data (CSV & JSON, zipped)
├── dashboard/                   # Power BI dashboard (.pbix)
└── docs/                        # DAX measures reference & dashboarding notes
```

## ▶️ How to View
Open `dashboard/Cricket_Best11_Dashboard.pbix` in **Power BI Desktop** (free). To reproduce the data pipeline, run the notebook in `code/data_preprocessing/`.

## 🔑 Key Skills Demonstrated
Web scraping · Data cleaning (Python/pandas) · Data modeling · DAX · Power BI dashboarding · KPI design

---
*Project completed as part of the Codebasics data analytics resume challenge.*
