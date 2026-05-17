**ETF Performance Tracker - SPDR Funds Analysis**

**Objective:**
- To analyze 2 years of historical performance data across 8 major SPDR ETFs tracking returns, risk levels, and price trends to derive actionable investment insights.

**Data & Scope:**
- Dataset included daily market data covering open, close, high, low prices and trading volume
- ETFs tracked: SPY, GLD, XLF, XLK, XLE, IVV, QQQ, BND
- Focused on return performance, volatility, price trends, and fund-level risk profiling

**Process & Techniques:**
- **Data Collection**
  - Pulled 2 years of live historical data for 8 SPDR ETFs using Python (yfinance API)
  - Consolidated 10,000+ rows of daily market data into a single structured dataset

- **Data Cleaning & Preparation (ETL)**
  - Removed duplicates and handled missing values using pandas
  - Standardized date formats and engineered new columns - Daily Return %, Month, Year
  - Transformed raw market data into analysis-ready structured format

- **Exploratory Data Analysis (EDA)**
  - Calculated and compared daily returns across all 8 funds
  - Analysed 2-year price trends and identified periods of high and low performance
  - Profiled each fund by risk level using volatility as the key measure

- **KPIs Derived:**
    - Average Daily Return % per fund
    - Volatility % (standard deviation of daily returns - risk indicator)
    - Average & Latest Closing Price
    - Total Volume Traded
    - Risk Classification (Low / Medium / High)


**Dashboard & Reporting:**
- Built interactive Power BI dashboard with filters for fund and time period
- Visualizations included price trend line charts, return comparison bar charts, and volatility risk charts
- Generated structured Excel report with pivot tables for monthly average prices and KPI summary


**Tools & Technologies Used:**
- Python (yfinance, pandas) - data extraction, cleaning, and KPI computation
- Google Colab - end-to-end analysis and documentation
- Excel - structured reporting with pivot tables
- Power BI - interactive dashboard and visualizations


**Key Insights & Outcomes:**

- XLK (Technology) delivered the highest average daily return - strongest growth fund in the tracked period
- XLE (Energy) showed the highest volatility, indicating the highest risk/reward profile
- BND (Bonds) was the most stable fund with near-zero volatility - best suited for capital preservation
- GLD (Gold) moved independently of equity funds - effective as a portfolio hedge
