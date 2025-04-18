# retail-sales-analysis
Retail sales data analysis using Python and Matplotlib.

This project analyzes retail transaction data using Python (Pandas & Matplotlib) to extract valuable insights into sales trends, customer behavior, product performance, and regional demand. The project includes various visualizations that provide a deeper understanding of key business metrics, which can help identify growth opportunities and areas for improvement in the retail sector.

## Dataset
- **`dataset_matplotlib1.csv`** is the main data source.
- **Columns**:
  - `order_id`: Unique identifier for each order.
  - `order_date`: Date when the order was placed.
  - `customer_id`: Unique identifier for each customer.
  - `city`: The city where the order was placed.
  - `province`: The province where the order was placed.
  - `product_id`: Unique identifier for the product sold.
  - `brand`: The brand of the product sold.
  - `quantity`: Quantity of the product sold.
  - `item_price`: Price per unit of the product.

## Insights Visualized
The following key insights are visualized through various types of charts:

1. **Monthly Sales Trend**:
   - This line chart shows the total sales over time, grouped by month. It helps track the overall sales performance and identify trends or fluctuations in sales.

2. **Monthly Customer Growth**:
   - A line chart showing how many new customers made their first monthly purchase. It provides insights into customer acquisition trends and business growth.

3. **Top 5 Provinces by Sales**:
   - A bar chart highlighting the top five provinces with the highest total sales. This gives an overview of the most profitable regions.

4. **Brand Sales Contribution**:
   - A pie chart illustrating the proportion of sales contributed by each brand. This helps understand which brands are driving revenue and their market share.

5. **Top 5 Cities by Order Volume**:
   - A bar chart showcasing the cities with the highest order volume. This can help identify key customer hubs and regions with high demand.

6. **Average Order Value (AOV) by Province**:
   - A bar chart comparing the average order value across provinces. This metric helps assess regional revenue efficiency and pricing strategies.

7. **Daily Sales Distribution**:
   - A line chart that shows how sales fluctuate daily. This helps identify peak sales days and trends in daily performance.

8. **Top 10 Best-Selling Products**:
   - A bar chart displaying the top 10 products based on total quantity sold. This provides insights into which products are the most popular and contribute the most to sales volume.

## Requirements
To run this analysis, you will need the following libraries:
- `Pandas`: For data manipulation and analysis.
- `Matplotlib`: For data visualization.

You can install the required libraries using the following commands:
```
pip install pandas matplotlib
```

## How to Run the Project
1. Clone the repository to your local machine.
2. Ensure the dataset (`dataset_matplotlib1.csv`) is located in the specified path: `C:\FAWAZUL\Bootcamp\DQLab\dataset_matplotlib1.csv`.
   If you're using a different directory or operating system, you must update the file path in the script. For example:
   - On macOS/Linux, the path might look like this: /Users/yourname/Bootcamp/DQLab/dataset_matplotlib1.csv.
   - On Windows, ensure the path includes the correct drive letter and folder structure (e.g., C:\Users\yourname\Documents\dataset_matplotlib1.csv).
4. Run the Python script to generate the visualizations.
5. Analyze the graphs to gain insights into retail sales performance.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
If you'd like to contribute to this project, you can fix the repository, make improvements, and submit a pull request. All contributions are welcome!

## Acknowledgments
- The dataset used in this project is provided by DQLab as part of their retail sales analysis exercises.

## File Structure
This project contains both the Jupyter Notebook for visualization and the Python script version of the code for cleaner readability and modular use.
- `datavis_matplotlib.ipynb`: Interactive notebook with code and visualization
- `datavis_matplotlib_script.py`: Clean script version of the notebook