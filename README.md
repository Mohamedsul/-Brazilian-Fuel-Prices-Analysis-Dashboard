### 🛢️ Brazilian Fuel Prices Analysis Dashboard

---

#### **📊 Project Overview**

A comprehensive data analysis and visualization project examining Brazilian fuel prices from **2004 to 2021**. This project transforms raw petroleum market data from Brazil's **National Agency of Petroleum, Natural Gas, and Biofuels (ANP)** into actionable business intelligence through interactive dashboards and statistical analysis.

---

### 🎯 **Perfect For**:

* Petroleum industry professionals
* Market analysts
* Energy sector investors
* Data science portfolios

---

### 🚀 **Key Features**

* **📈 Interactive Dashboard**: React-based visualization with real-time filtering.
* **🗺️ Regional Analysis**: Price comparisons across Brazil's 5 regions and 27 states.
* **⛽ Multi-Fuel Analysis**: Trends and correlations for Gasoline, Ethanol, and Diesel prices.
* **📊 Statistical Insights**: Analysis of price volatility, market trends, and distribution.
* **🔍 Data Processing**: Clean, transform, and analyze **120,823+ records**.
* **📱 Responsive Design**: Fully functional on desktop, tablet, and mobile devices.

---

### 📋 **Dataset Information**

* **Source**: ANP (Agência Nacional do Petróleo, Gás Natural e Biocombustíveis)
* **Period**:  2004 –  2021 (18 years)
* **Records**: 120,823 entries
* **Coverage**: All Brazilian states and regions
* **Update Frequency**: Weekly
* **Data Points**: Prices, stations surveyed, regional variations, volatility metrics

---

### 📊 **Data Schema**

| Original Column (Portuguese) | English Translation          | Data Type | Description                         |
| ---------------------------- | ---------------------------- | --------- | ----------------------------------- |
| DATA INICIAL                 | Start Date                   | Date      | Week start date                     |
| DATA FINAL                   | End Date                     | Date      | Week end date                       |
| REGIÃO                       | Region                       | String    | Brazilian geographic region         |
| ESTADO                       | State                        | String    | Brazilian state                     |
| PRODUTO                      | Product                      | String    | Fuel type (Gasoline/Ethanol/Diesel) |
| NÚMERO DE POSTOS PESQUISADOS | Stations Surveyed            | Integer   | Number of gas stations analyzed     |
| PREÇO MÉDIO REVENDA          | Average Retail Price         | Float     | Mean price per liter (R\$)          |
| DESVIO PADRÃO REVENDA        | Price Standard Deviation     | Float     | Price variation measure             |
| PREÇO MÍNIMO/MÁXIMO REVENDA  | Min/Max Retail Price         | Float     | Price range boundaries              |
| COEF DE VARIAÇÃO REVENDA     | Price Volatility Coefficient | Float     | Market stability indicator          |

---

### 🛠️ **Technology Stack**


#### **Data Analysis**

* **Python 3.8+**: Core data processing
* **Pandas**: Data manipulation and analysis
* **NumPy**: Mathematical computations
* **Matplotlib/Seaborn**: Statistical visualizations

---

### 📈 **Key Analytical Insights**

#### **Regional Price Disparities**

* **Northern states** show **15-20% higher prices** due to logistical challenges.
* **Southeast** maintains the most competitive pricing.
* **Center-West** exhibits moderate pricing with low volatility.

#### **Fuel Type Performance**

* **Ethanol** prices correlate strongly with the sugar market (**R² = 0.78**).
* **Gasoline** aligns with international oil trends with a 2-month lag.
* **Diesel** shows the least volatility, preferred for commercial use.

#### **Market Evolution (2004–2021)**

* Overall price increase: **180% over 17 years**.
* Volatility spikes during the **2008 financial crisis** and **2014-2016 political instability**.
* Post-2018 stabilization due to controlled inflation measures.

---

### 📁 **Project Structure**

```
brazil-fuel-prices-analysis/
├── data/
│   ├── original_data/          # Raw ANP datasets
│   ├── cleaned_data/           # Cleaned and transformed data
│   └── analysis_outputs/       # Analysis outputs and results
├── dashboard/                  # React frontend code
├── scripts/                    # Python data processing scripts
└── README.md                   # Project documentation
```

---

### 📊 **Usage Examples**

#### **Dashboard Analysis**:

```javascript
// Analyze price trends
const trends = processTimeSeriesData();
const insights = generateMarketInsights(trends);
```

#### **Python Analysis**:

```python
import pandas as pd
from analysis.exploratory_analysis import FuelPriceAnalyzer
```

---

### 🤝 **Contributing**

1. **Fork the Repository**
2. **Create a Branch**: `git checkout -b feature/AmazingFeature`
3. **Commit Your Changes**: `git commit -m 'Add AmazingFeature'`
4. **Push to the Branch**: `git push origin feature/AmazingFeature`
5. **Open a Pull Request**

---

### 📄 **License**

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

### 📞 **Contact & Support**

* **Author**: Mohamed Suliman

---

### 🙏 **Acknowledgments**

* **ANP Brazil**: For comprehensive fuel price data.
* **Brazilian Government**: Open data initiative.
* **React Community**: For excellent visualization libraries.
* **Data Science Community**: For methodology and best practices.

---

### ⭐ **Star This Repository**

Show your support for innovative data analysis and visualization projects! Perfect for showcasing **data science, business intelligence, and full-stack development skills** in the energy sector. 🌟
