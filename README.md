# Product-Sales-Analysis
This project analyzes supermarket sales data to uncover trends in customer purchasing behavior, sales performance by product category, and branch-level insights. 
# TECHNOLOGIES USED

- Python (Pandas, Matplotlib, Seaborn)
- Power BI
- Excel

# METHODOLOGY

### **Step 1: Data Loading**

- **Code:** The dataset was loaded using `pd.read_csv()` in Python to bring raw sales data into a DataFrame.
- **Explanation:** Loading data was the first step, enabling initial examination and preparation for further analysis.

### **Step 2: Data Exploration**

- **Code:** `.head()`, `.info()`, and `.describe()` functions in `pandas` were used to inspect data structure and basic statistics.
- **Explanation:** Understanding the dataset, including data types and distributions, provided a foundation for identifying key insights and ensuring data quality.

### **Step 3: Data Cleaning**

- **Code:** We checked for any missing or inconsistent data using `isnull().sum()` and resolved them as needed.
- **Explanation:** Clean data minimizes errors, ensuring accuracy in the analysis and visualizations.

### **Step 4: Visualization in Power BI**

- **Explanation:** Power BI was used to create a dashboard that visualizes trends, including sales breakdown by gender, branch performance, and sales over time.

### **Step 5: Insights and Interpretation**

- **Explanation:** The visualizations provided detailed insights into sales performance and customer trends. These insights offer actionable takeaways to inform targeted business strategies.

# KEY INSIGHTS
### **Total Sales and Product Volume**

The dashboard shows **Total Sales** at approximately **322.97K** and **Total Products Sold** at **6K**. This provides a quick overview of revenue and volume, giving stakeholders a snapshot of sales performance.

### **Sales by Gender**

The **Average Sales by Gender** bar chart indicates higher spending by females compared to males. This insight can be used to design targeted promotions aimed at different demographics.

### **Sales per Branch**

The **Sales per Branch** pie chart shows a balanced distribution across Branches A, B, and C, with slight variations. Branch B leads with **34.24%**, suggesting it may serve a larger customer base or have higher-value transactions.

### **Monthly Sales Trends**

The **Monthly Sales** line chart shows fluctuations, with peaks in early February and mid-March. These spikes can inform future promotional efforts during high-sales periods.

### **Sales by Product Line**

The **Sales by Product Line** section reveals that **Food and Beverages** generated the highest revenue (56K), followed by **Sports** (55K). This breakdown allows the company to focus on popular product lines or explore strategies to boost sales in lower-performing categories like **Health and Beauty** (49K).

This sales analysis provides valuable insights into customer purchasing patterns, product performance, and branch-level sales trends. By leveraging these findings, the supermarket can make data-driven decisions to optimize inventory, enhance targeted marketing, and improve customer engagement. Continuous monitoring and analysis of sales data will be essential to sustain growth and adapt to evolving customer needs.
