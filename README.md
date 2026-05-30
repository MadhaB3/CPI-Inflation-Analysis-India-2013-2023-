# CPI-Inflation-Analysis-India-2013-2023-
This case study analyzes India's CPI inflation trends over a decade using government-released monthly data. The analysis covers 5 key questions across category contribution, year-on-year trends, food inflation patterns, COVID-19 disruption, and oil price correlation all built in Excel with pivot tables, calculated fields, and a summary dashboard.

📂 File Structure
1. **All_India_Index_Upto_April23**-Raw CPI data Rural, Urban, Rural+Urban across 28 categories (Jan 2013 – May 2023)
2. **Clean Data**-Processed and structured data used for analysis

Q1.Contribution CategoryCPI basket weight breakdown by category
| Bucket Category   | Contribution (%) |
|-------------------|------------------|
| Bucket Food       | 51.41            |
| Bucket Apparel    | 12.39            |
| Bucket Housing    | 0.00             |
| Bucket Energy     | 4.08             |
| Bucket Healthcare | 4.15             |
| Bucket Transport  | 3.69             |
| Bucket Education  | 3.96             |
| Bucket Others     | 20.32            |

Chart-<img width="1008" height="388" alt="image" src="https://github.com/user-attachments/assets/3612a2f7-dcc0-4240-a7e9-98efc1c64b0c" />

Insight: Food is the dominant component of India's CPI basket (51.41%), reflecting how central food expenditure is in Indian household budgets — especially for rural consumers.


Q2 – YOY Inflation RateMonth-wise and year-wise Year-on-Year inflation rate

| Year | Avg YoY Inflation (%) |
|------|----------------------:|
| 2017 | 3.33 |
| 2018 | 3.97 |
| 2019 | 3.97 |
| 2020 | 4.89 |
| 2021 | 7.13 |
| 2022 | 6.62 |
| 2023 | 5.58 |

Chart-<img width="1374" height="446" alt="image" src="https://github.com/user-attachments/assets/08f28f83-e0cf-498f-8a9c-de14520ca5b0" />

Insight: Inflation trended downward from 2014 to 2017, stayed stable through 2019, then spiked sharply in 2020–2021 due to COVID-19 supply chain disruptions. April–May 2021 saw spikes above 16% YoY due to the low base effect from the 2020 lockdown months.

Q3 – Food Inflation Deep DiveFood sub-category MoM changes (Jun 2022 – May 2023)

| Category                 | Jun-22 | May-23 | Absolute Change |
|--------------------------|-------:|-------:|----------------:|
| Cereals and Products     | 155.0  | 173.7  | 18.7  |
| Meat and Fish            | 219.4  | 214.3  | -5.1  |
| Egg                      | 170.8  | 173.2  | 2.4   |
| Milk and Products        | 165.8  | 179.5  | 13.7  |
| Oils and Fats            | 200.9  | 170.0  | -30.9 |
| Fruits                   | 169.7  | 172.2  | 2.5   |
| Vegetables               | 182.3  | 161.0  | -21.3 |
| Pulses and Products      | 164.3  | 175.6  | 11.3  |
| Sugar and Confectionery  | 119.9  | 122.7  | 2.8   |
| Spices                   | 187.1  | 218.0  | 30.9  |
| Non-alcoholic Beverages  | 167.9  | 173.4  | 5.5   |
| Prepared Meals, etc.     | 183.9  | 194.2  | 10.3  |

Chart-<img width="883" height="542" alt="image" src="https://github.com/user-attachments/assets/c23c04ba-cb92-4b10-b80c-9d1c6cd466d3" />

Insight: Spices and cereals were the biggest contributors to food inflation pressure in this period. Oils & Fats saw a significant correction, likely influenced by falling global edible oil prices post the Russia-Ukraine supply shock.

Q4 – Covid-19 Impact on InflationMoM% changes in Food, Apparel, Energy, Healthcare (2019–2021)

| Category   | Pre-COVID | Post-COVID | Change |
|------------|----------:|-----------:|-------:|
| Food       | 0.67      | 0.71       | 0.04   |
| Apparel    | 0.16      | 0.66       | 0.50   |
| Energy     | 0.42      | 0.59       | 0.17   |
| Healthcare | 0.34      | 0.78       | 0.43   |

Chart-<img width="832" height="452" alt="image" src="https://github.com/user-attachments/assets/6778b244-c27f-43d1-9c6f-ca2906829297" />

Insight: Apparel and Healthcare saw the sharpest acceleration post-COVID. Apparel inflation spiked due to supply chain disruptions and factory shutdowns. Healthcare inflation surged due to increased demand for medicines, PPE, and medical services. April–May 2020 recorded deflation in Apparel (−16.5% MoM) due to near-zero demand during the national lockdown, followed by a sharp rebound.


Q5 – Oil Price InflationBrent crude oil price vs. CPI category correlations (2021–2023)

| Category           | Correlation with Oil |
|--------------------|--------------------:|
| Cereals            | -0.33 |
| Meat               | 0.50 |
| Egg                | -0.26 |
| Milk               | -0.27 |
| Oils               | 0.36 |
| Fruits             | 0.07 |
| Vegetables         | 0.03 |
| Pulses             | -0.11 |
| Sugar              | -0.18 |
| Spices             | -0.10 |
| Non-Alcoholic Beverages | 0.13 |
| Prepared Meals     | 0.02 |
| Food & Beverages   | 0.09 |
| Pan & Tobacco      | 0.15 |
| Clothing           | -0.01 |
| Footwear           | 0.11 |
| Clothing & Footwear| 0.03 |
| Housing            | 0.13 |
| Fuel               | 0.10 |
| Household Goods    | -0.08 |
| Health             | 0.03 |
| Transport          | 0.11 |
| Recreation         | 0.09 |
| Education          | -0.12 |
| Personal Care      | 0.07 |
| Miscellaneous      | 0.09 |

Chart-<img width="1067" height="535" alt="image" src="https://github.com/user-attachments/assets/a0d1aa90-984e-4f89-b0ef-d12690ca5cbb" />

Insight: Contrary to intuition, Fuel & Light shows only weak correlation with oil prices — because India regulates domestic LPG/kerosene prices and absorbs global price shocks through subsidies. Meat and Oils & Fats show stronger correlation, likely reflecting input cost (feed, transport) transmission. Cereals show a negative correlation, suggesting other domestic factors (MSP, monsoon, procurement) dominate over oil.

Answer SheetConsolidated answers and insights for all 5 questions
Dashboard Visual summary of key findings
Excel Dashboard-<img width="1869" height="528" alt="image" src="https://github.com/user-attachments/assets/658da8c4-637f-4295-baa6-cc1ca2661846" />


🛠️ Techniques Used

1.Pivot Tables (category bucketing, year/month aggregation)
2.Calculated Fields (YoY%, MoM%, correlation coefficients)
3.Data Cleaning (handling Rural/Urban/Combined sector splits)
4.Conditional Formatting (highlighting peaks and troughs)
5.Chart Design (line charts, bar charts, contribution pie)
6.Dashboard layout with summary KPIs


📈 Key Takeaways

Food dominates India's inflation basket — over half of CPI weight, making food prices the single biggest driver of headline inflation.
COVID-19 caused a structural break — the 2020 lockdown caused a temporary deflation shock in April–May 2020, followed by persistent above-trend inflation through 2021–2022.
Spices and cereals are high-risk categories — both showed double-digit index increases in 2022–23, driven by monsoon variability and global commodity pressures.
Domestic fuel prices are policy-insulated — low oil-CPI correlation confirms the government shields consumers from global crude shocks via subsidies and price controls.
Inflation moderated in 2023 — after peaking in 2021–22, YoY inflation eased to ~5.6% by May 2023, still above the RBI's 4% target.


📎 Data Source
MoSPI CPI Data: mospi.gov.in
Base Year: 2012 = 100
Frequency: Monthly
Coverage: All India — Rural, Urban, Rural+Urban Combined
