# 📊 Tata – Retail Sales Dashboard in Power BI

**Forage job simulation · Tata Data Visualisation: Empowering Business with Effective Insights · Nov 2026**
[View credential](https://www.theforage.com/completion-certificates/ifobHAoMjQs9s6bKS/MyXvBcppsW2FkNYCX_ifobHAoMjQs9s6bKS_6aeda13e3a37e82da041028f_1794126146338_completion_certificate.pdf)

**Tools:** Power BI (Power Query, DAX basics, filters, Top N, map visuals)

---

## Business context
An online retail store's **CEO and CMO** wanted to understand what drives revenue and where to expand next year. I framed their questions, chose the right visual for each, built the dashboard in Power BI and presented the insights.

## Data preparation (Power Query)
- Dataset: **541,909 transactions** (Dec 2010 – Dec 2011) – invoice, product, quantity, date, unit price, customer, country.
- Removed **returns** (Quantity < 1) and **pricing errors** (Unit Price < 0) → **531,283 clean rows**.
- Added a **Revenue** column = Quantity × Unit Price.

## Dashboard – 4 questions, 4 visuals

| # | Question | Visual | Key insight |
|---|---|---|---|
| Q1 | CEO: monthly revenue trend for 2011 | Line chart (year filter = 2011) | Lowest in **February (~£524K)**; strong rise from September to a **November peak (~£1.5M)** before Christmas. December looks low only because data stops on 9 Dec. |
| Q2 | CMO: top 10 countries by revenue and quantity (excl. UK) | Line + clustered column chart, Top N | **Netherlands (~£285K), Ireland (~£283K), Germany (~£229K)**, France and Australia lead international sales. |
| Q3 | CMO: top 10 customers by revenue | Clustered column chart, sorted, Top N | Customer **14646 (~£280K)** is the largest; even the 10th customer brings in £77K+ – a clear key-account group. |
| Q4 | CEO: demand by region for expansion (excl. UK) | Map, bubble size = quantity | Demand is concentrated in **Western Europe** (Netherlands, Ireland, Germany, France), with **Australia** the strongest market outside Europe. |

## Recommendations
1. Plan stock, staff and marketing budget for the **September–November peak**; use promotions to lift January–April.
2. Focus international expansion on the **Netherlands, Ireland, Germany, France** and **Australia**.
3. Protect top customers with a **key-account approach** (dedicated contact, loyalty offers).

## Screenshots
*Dashboard screenshots (Q1–Q4) are being added to the [images](images) folder.*

---

### Notes
- The dataset is provided by Forage for simulation use only and is **not included** here (the .pbix file embeds the data, so screenshots are shared instead).
- This is a Forage virtual job simulation, not employment with Tata.

👤 **Rehan Deshmukh** · [LinkedIn](https://www.linkedin.com/in/rehan-akhtar-deshmukh-25bb93269/) · [GitHub profile](https://github.com/rehan-deshmukh1110)
