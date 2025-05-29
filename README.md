# 🌍 Global Market Attractiveness Analysis using Open Data

This project analyzes and ranks countries based on a combination of economic, demographic, and digital indicators to support strategic international market expansion decisions. The analysis uses live data from the World Bank API and automates the full process from data collection to scoring and visualization.

---

## 🚀 Open in Google Colab

Click below to run the full notebook online:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Joel1993055/Global-Market-Attractiveness-Analysis-using-Open-Data/blob/main/notebooks/01_market_analysis (1).ipynb)


---

## 📈 Indicators Used

The analysis is based on the following World Bank indicators for the year 2022:

| Indicator                             | Code               |
|---------------------------------------|--------------------|
| GDP per capita (current US$)          | `NY.GDP.PCAP.CD`   |
| Total population                      | `SP.POP.TOTL`      |
| Internet usage (% of population)      | `IT.NET.USER.ZS`   |
| Exports of goods and services (% GDP) | `NE.EXP.GNFS.ZS`   |

Each indicator is normalized and weighted to compute a final **Market Attractiveness Score** for each country.

---

## 📊 Visualizations

- 📊 **Bar chart**: Top 10 most attractive countries for expansion
- 🗺️ **Choropleth map**: Global view of attractiveness by country

---

## 🛠️ Tools & Technologies

- Python
- Google Colab / Jupyter Notebook
- `wbdata` (World Bank API)
- `pandas`, `matplotlib`, `plotly`, `scikit-learn`

---

## 📁 Project Structure

