# Customer Segmentation and Sales Forecasting for Business Growth

## Business Problem

Many large businesses struggle to understand the contributions of their various customer segments. This often leads to:

- **Misallocation of Resources**: Marketing and customer service efforts might not be targeted effectively.
- **Revenue Loss**: Potential opportunities within specific customer segments might be missed.
- **Decreased Customer Satisfaction**: Customers may not receive the tailored experiences they desire.

**Example**: If a store primarily caters to individual consumers, it's essential to tailor their marketing and customer service efforts accordingly. Focusing on the needs of consumers and avoiding misallocating resources to large corporates helps provide a satisfying experience and ultimately leads to loyalty and revenue growth.

## Project Goal

The objective of this project is to use data analysis and machine learning to address this business problem.

This includes:

- **Customer Segmentation**: Grouping customers into meaningful segments based on their behaviors and characteristics.
- **Sales Forecasting**: Predicting future sales to optimize inventory and resource allocation.
- **Geographical Analysis**: Identifying high potential areas or underperforming stores
- **Shipping Method**: Analyze the shipping methods used by customers and which methods are most cost-effective and reliable.
- **Product Analysis**: Identifying top-selling products, categories, and subcategories to understand customer preferences.
- **Time Series Analysis**: Analyzing sales trends over time and detecting anomalies.
- **Visualizing Data**: Creating dashboards and visualizations to explore and communicate data insights.
- **Recommendations**: Providing actionable recommendations to improve business performance.

## Data Source

The dataset used in this project is the "train.csv" file and it consists of records of purchases made by different consumers

**Data Preprocessing**

- The dataset was loaded using pandas.
- Missing values in the 'Postal Code' column were filled with 0 and the type for column was converted to integer.
- Any duplicate rows were checked before analysis.
- 'Order Date' and 'Ship Date' columns were converted to datetime objects using the dayfirst argument.

## Methodology

### **Customer Segmentation**

- Identified different customer segments (e.g., consumers, corporates, home office).
- Determined the proportion of each segment and their contribution to sales.
- Analyzed customer order frequency and spending habits to identify loyal customers and top spenders.

### **Sales Forecasting**

- Aggregate the sales data for easier forecasting.
- Performed time series analysis to identify trends and patterns.
- Utilized the SARIMA model to predict sales and gain an estimate of future projections.

### **Geographical Analysis**

- Mapped the sales to the states to see how much every state generated
- Created horizontal bar chart for the distribution of sales by state.

### **Product Analysis**

- Explored popular categories and sub-categories.
- Identified the most and least performing categories and sub-categories by sales.

### **Time Analysis (Trends)**

- Visualize sales trends over years and periods (Quarterly and Monthly)

### **Mapping**

- Mapped the sales to the states to see how much every state generated

## Results

- The analysis provided valuable insights to help the business understand its customers and sales patterns.
- Identified potential areas for improvement in sales strategy, customer relationship management, and operations.

## Key Visualizations

- Pie chart for customer segments and sales contributions.
- Bar chart for product performance.
- Line graphs for sales trends over time.
- Choropleth map for geographical sales distribution.
- Treemap and Sunburst charts for hierarchical sales data visualization.

## Recommendations

- Target loyal customers to improve retention and increase revenue.
- Focus marketing efforts on specific customer segments for better results.
- Consider opportunities to improve cost-effectiveness and customer satisfaction by optimizing product offerings.
- Adapt sales strategy based on seasonal variations and trends.

## How to Use

- Open the Colab Notebook.
- Install the necessary packages by running the code cells in the package installations section.
- Change the path for the CSV data to your CSV file.
- Run the code cells sequentially to understand the analysis.
- Modify the code to make custom analysis.

## Dependencies

- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

## Conclusion

This project demonstrated the potential of data science to solve a significant business challenge. The analysis and recommendations offered valuable insights for business growth and customer satisfaction.
