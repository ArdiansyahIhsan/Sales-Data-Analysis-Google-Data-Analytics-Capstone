# 🧾 Sales Data Analysis Project

This project is the result of exploring and analyzing sales data using **Python** by utilizing the `Sales.csv` dataset. The analysis was conducted to understand sales patterns, product profitability, seasonal trends, and the relationship between financial variables. This project also follows the analytical work stages taught in the **Google Data Analytics Course**.

## 📂 Dataset  

The dataset used is called **Europe Bike Store Sales** and comes from **Kaggle**.  
This dataset contains sales transaction data that includes information such as order date, product category, number of items purchased, unit price, total revenue, and profit.  
This data represents sales activities from several main product categories, namely **Bikes**, **Clothing**, and **Accessories**.  
Each row in the dataset represents one sales transaction, which can be used to analyze business performance, price efficiency, and seasonal sales trends.

---

## 📁 Project Structure
├── Sales.csv # Main sales dataset    
├── analysis.ipynb # Main notebook containing analysis & visualization processes    
└── README.md # Project documentation


---

## 🧰 Technologies Used
- **Python 3.x**
- **Pandas** → data processing and analysis  
- **Matplotlib** & **Seaborn** → data visualization  

---

## 📊 Project Workflow

This project is structured according to professional data analysis stages, namely:

### 1️⃣ Asking
Determine the main questions to be answered through data:
- Which countries or regions generate the highest revenue?
- Which products are the most profitable?
- Are there seasonal patterns in sales?
- What is the relationship between price, order quantity, and profit?

---

### 2️⃣ Prepare
Prepare the `Sales.csv` dataset for analysis:
- Remove empty data (if any)  
- Convert the date column to `datetime` format  
- Create additional columns such as `Year`, `Month`, and `Profit_Margin`  

---

### 3️⃣ Process
Use *pandas* for transformation and calculation:
- `groupby()` for aggregation by country, product, and time  
- Calculate metrics such as `Revenue`, `Profit`, and `Profit_Margin`
- Organize data for visualization of trends and distribution

---

### 4️⃣ Analyze
Main and additional analyses performed include:

#### 🔹 Main Analysis
1. **Top 10 Countries by Revenue & Profit**  
  → Identifying regions with the largest sales contributions.  
2. **Revenue Distribution by Product Category**  
  → Identifying the product categories that dominate sales.  
3. **Annual Revenue Trends**  
  → Examining sales growth and fluctuations between years.  
4. **Revenue Comparison by Gender & Age Group**  
  → Analyzing customer segmentation.

5. **Correlation Between Financial Variables**  
   Shows the relationship between *Revenue*, *Profit*, *Cost*, and *Order Quantity*.  
   Results: a very strong relationship between *Revenue* and *Profit*, while *Order Quantity* has a slight negative correlation.

6. **Seasonal Sales Analysis (Revenue per Month)**  
   Describes the average monthly sales pattern.  
   Results: sales increase sharply towards the middle and end of the year, indicating a strong seasonal pattern.

7. **Profit Margin per Product Category**  
   Measures profit efficiency per category.  
   Results: the *Accessories* category has the highest margin (~57%), followed by *Bikes* (~33%) and *Clothing* (~31%).

8. **Effectiveness of Price on Quantity Sold**  
   Illustrates the relationship between unit price and sales volume.  
   Results: negative correlation — the higher the price, the lower the number of products purchased.

---

### 5️⃣ Visualize
Visualization was performed using **Matplotlib** and **Seaborn**, with graphs such as:
- **Bar Chart** → Comparison between categories and countries
  
- **Line Chart** → Seasonal revenue trends  
- **Heatmap** → Correlation between financial variables  
- **Scatter Plot** → Relationship between price and quantity  

Examples of visualization results:
- Correlation between financial variables  
- Seasonal sales analysis  
- Profit margin per category  
- Effectiveness of price on quantity

---

### 6️⃣ Share
**Key insights from the analysis results:**
- High revenue is generally followed by large profits, but cost control is necessary for efficiency.  
- *Accessories* products are the most profitable and efficient in terms of margin.  
- Seasonal patterns show peak sales in the middle and end of the year.  
- Price has a negative impact on quantity — an appropriate pricing strategy is needed to maintain sales volume.  

---

## 💡 Conclusion
This analysis provides a comprehensive overview of sales performance based on actual data.  
The results can be used to:
- Determine pricing and promotion strategies.  
- Focus sales on high-margin products.  
- Plan inventory and campaigns based on seasonal patterns.  

---




Translated with DeepL.com (free version)
