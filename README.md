 ## Project Overview
You have been hired as a Business Intelligence Analyst by a global manufacturer of cycling equipment and accessories. The company is seeking to enhance its decision-making process by leveraging data insights to track performance and inform strategic planning.

This project involves developing a comprehensive BI solution to meet the management team’s analytical needs using the company's sample data.

## Key Objectives
1. Track Key Performance Indicators (KPIs):

- Sales
- Revenue
- Profit
- Returns
2. Analyze Regional Performance:

- Compare sales and revenue metrics across regions.
- Identify areas of growth and underperformance.
3. Explore Product-Level Trends:

- Understand which product categories drive the most revenue.
- Identify underperforming products.
4. Identify High-Value Customers:

- Determine customer segments contributing the most to sales.
- Spot trends in customer purchasing behavior.

5. Built an ELT Azure data pipeline

## Deliverables
### Azure Data Analytics Pipeline

#### Components Used:
- **Azure Data Factory**: For orchestration and data movement
- **Azure Databricks**: For data transformation and processing
- **Power BI**: For visualization and reporting
- **Azure Data Lake**: For raw data storage

#### Pipeline Flow:
1. Data ingestion from multiple sources via ADF
2. Raw data storage in Data Lake
3. Transformation logic in Databricks notebooks
4. Processed data loaded to analytical storage
5. Power BI connects for visualization

### Power BI Dashboard:

#### Steps to Get Started
1. **Understand Business Requirements**: Review objectives and KPIs to align with management needs.
2. **Explore and Prepare Data**: Use SQL or other tools to clean and structure the dataset.
3. **Develop the Dashboard**: Create visuals for each KPI and analysis area using the selected tool.
4. **Test and Validate Insights**: Ensure data accuracy and relevance of insights.
5. **Prepare Deliverables**: Document findings and prepare the dashboard for presentation.

#### Dashboard Highlights
1. Key Metrics:

- Profit and Revenue:
  - Profit: $771.58K (Goal: $825.83K, -6.57% deviation).
  - Previous Month Profit: $750.75K (+2.77% growth).
- Revenue per Customer: $1.431K.
- Top 100 Customers: Insights into high-value customer contributions.
- Regional Analysis:
  - Performance across Europe, North America, and Pacific regions.
  - Visual mapping to compare regional revenue distribution.
- Customer Segmentation:
  - Revenue breakdown by occupation and income level.
- Key influencers for revenue increase (e.g., product categories and geographic trends).
- Product Trends:

  - Bikes, particularly Mountain and Touring models, are primary revenue drivers.
  - 2020 was the peak year for average revenue.
#### Objectives Achieved
- **Track KPIs**: Sales, revenue, profit, and returns visualized for easy tracking.
- **Analyze Regional Performance**: Geographic segmentation highlights high-performing areas.
- **Identify Trends**: Product and customer insights inform targeted marketing and product strategies.
- **Highlight High-Value Customers**: Focus on key contributors to sales growth.

#### Future Recommendations
- Focus marketing efforts on high-performing regions and product lines.
- Develop targeted campaigns for low-income or clerical customer segments.
- Explore additional data integration to monitor returns and customer satisfaction.

