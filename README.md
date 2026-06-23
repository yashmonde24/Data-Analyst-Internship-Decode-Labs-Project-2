# Data Analytics Project 2: Exploratory Data Analysis (EDA)

##  Project Overview
Once data is clean, the next step is exploration. This project focuses on **Exploratory Data Analysis (EDA)**. Instead of creating standard, generic reports, this script interrogates the dataset to discover hidden trends, typical customer spending ranges, and unusual purchase behaviors.

##  Key Findings & Business Insights
 **Order Value Distribution:** Our histogram shows that the majority of our customers place smaller orders (concentrated between $0 and $700). We can use checkout up-sells (like *"Add $15 for free shipping"*) to grow this average.
 **VIP Customer Signals:** Our boxplot highlights that while the middle 50% of orders fall between $420 and $1,600, a clear group of "VIP Whales" are making massive orders between $3,300 and $3,500. We should target these spenders with exclusive loyalty rewards.

##  Tools Used
 **Python** (Pandas, NumPy)
 **Data Visualization** (Matplotlib & Seaborn)

##  Project Structure
 `eda_script.ipynb`: The Python script that runs descriptive statistics and generates clean charts.
 `order_value_distribution.png`: Histogram showing the shape of our order data.
 `order_value_boxplot.png`: Boxplot isolating normal order ranges from our VIP outliers.