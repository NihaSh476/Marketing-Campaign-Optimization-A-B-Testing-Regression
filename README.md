**📊 Project Overview:** Marketing Campaign Optimization through A/B Testing & Regression Analysis

**📝 Background:**

As part of the strategic team at a marketing agency, our core objective was to maximize the return on investment (ROI) for client advertising campaigns. This project focused on identifying the more effective advertising platform—Facebook or Google AdWords—based on clicks, conversions, and cost-efficiency. Gaining these insights enables strategic budget allocation and improves advertising outcomes for clients.

**🎯 Objective:**

To determine which advertising platform—Facebook or Google AdWords—delivers higher conversions, better click-through rates (CTR), and greater cost-effectiveness.

**📊 Data Description:**

The analysis is based on daily campaign performance data collected throughout 2019. Each entry represents one day’s metrics for both platforms and includes the following features:

* **📅 Date:** Daily records from January 1st to December 31st, 2019

* **👀 Ad Views:** Total number of impressions

* **🖱 Ad Clicks:** Number of user clicks on the ads

* 🔄 **Ad Conversions:** Number of successful conversions from clicks

* 💸 **Cost per Ad:** Daily expenditure on each platform

* 🔗 **Click-Through Rate (CTR):** Ratio of clicks to impressions

* 📈 **Conversion Rate:** Ratio of conversions to clicks

* 💵 **Cost per Click (CPC):** Average cost for each click

The dataset consists of 365 entries—one for each day in 2019.

**🔍 Methodology:**

 **1. Data Cleaning**
   * Standardized date formats.
   * Handled missing or inconsistent data to ensure accuracy.
     
  **2. Exploratory Data Analysis (EDA)**
   * Visualized the distribution and trends of clicks and conversions
   * Identified seasonal or platform-specific patterns

  **3. Statistical Analysis**
   * Performed t-tests to compare key performance metrics between platforms
   * Conducted correlation analysis between clicks and conversions
   * Used cointegration tests to examine long-term relationships between ad spend and conversions

  **4. Predictive Modeling**
   * Built a linear regression model to predict conversions based on ad clicks
   * Evaluated model performance using R² and Mean Squared Error (MSE)

**📈 Key Insights :**

* **Platform Performance:** Facebook consistently outperformed Google AdWords in terms of conversion efficiency, achieving higher conversion rates and lower CPC.

* **Budget Optimization:** Results suggested that reallocating a larger portion of the advertising budget to Facebook could enhance campaign ROI.

* **Seasonal Trends:** Conversion performance varied across the year, indicating that campaign timing should be optimized based on historical patterns.

💻 **Technologies Used :**

* **Python:** End-to-end data analysis and modeling

* **Pandas & NumPy:** Data manipulation and numerical analysis

* **Matplotlib & Seaborn:** Visualizations

* **SciPy:** Hypothesis testing and statistical analysis

* **Scikit-learn:** Building and evaluating regression models    

    
