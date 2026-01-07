# CarSales_BuyerInsights_powerbi
This project is an interactive Power BI dashboard developed to analyze car sales trends and buyer behavior using multiple related datasets.
The dashboard answers key business and analytical questions related to sales performance, pricing trends, geography, and buyer demographics, with a strong focus on visual clarity and actionable insights.

A date slicer is implemented to allow time-based analysis across all visuals.

The analysis is based on three datasets, each serving a distinct analytical purpose.

1.Cars Dataset (Cars.csv)
This dataset represents car purchase and pricing information.
Key attributes include:
Car Brand
Company
Department
Car Make Year
Car Price
Purchase Date
This dataset acts as the primary fact table for sales, pricing, and trend analysis.

2️.Company Dataset (Company.csv)
This dataset contains organizational details related to car manufacturers.
Key attributes include:
Company Name
Department
It supports company-level and department-level performance analysis.

3️.Buyer Dataset (Buyer Details.xlsx)
This dataset captures buyer demographic and geographic information.
Key attributes include:
Buyer ID
Gender
Country
Salary
This dataset enables customer segmentation and demographic analysis.

Data Modeling & Time Handling
Relationships were created between Cars, Buyers, and Company datasets.
A Date table was created and linked to the Cars table.
A Date slicer (slider) filters the entire dashboard consistently.

Business Questions & Observations

The dashboard answers key business questions by visually exploring sales, pricing, geography, and buyer behavior. The following insights were derived from the analysis:

The KPI section provides a high-level overview of the dataset by showing the total number of distinct car brands, companies, and departments. This gives immediate context about the scale and diversity of the data being analyzed.

The time-based analysis of car purchases shows how sales vary across years. From the trend, we can observe periods of growth and decline in car purchases, helping identify years with stronger market activity and potential seasonal or economic influences on sales.

An analysis of the top companies by total sales value highlights which manufacturers dominate the market. A small number of companies contribute a significant share of total sales, indicating brand strength and customer trust concentrated among leading players.

When examining the average car price across years, one specific year stands out with the highest average price. This suggests that higher-priced vehicles were purchased more frequently during that period, possibly due to economic conditions, premium product launches, or shifts in buyer preferences.

The distribution of car prices reveals how prices are spread across different ranges. Most cars fall within a mid-price range, while a smaller number of high-priced vehicles create visible outliers, indicating a premium segment within the market.

Geographic analysis of average buyer salary shows noticeable variation across countries. Some countries demonstrate significantly higher average salaries, which can influence purchasing power and vehicle price preferences.

The total number of buyers by country highlights where the customer base is most concentrated. Countries with higher buyer counts represent key markets, while lower counts may indicate emerging or niche markets.

By comparing average salary with average car price across countries, a positive relationship can be observed. Countries with higher average salaries tend to purchase higher-priced cars, suggesting that income level plays an important role in purchasing decisions.

Gender-based analysis of car brand preference shows that certain brands are more popular among specific genders. This insight can help tailor marketing strategies and product positioning to better align with customer preferences.

The analysis of car make year preference by gender shows how buyers differ in their choice of newer versus older models. One gender may show a stronger inclination toward recent models, while the other demonstrates a more balanced or conservative purchasing pattern.

Buyer behavior analysis distinguishes between single-time buyers and repeat buyers. Based on the available data, all buyers are classified as single-time buyers, indicating no repeat purchase behavior captured within this dataset.

Department-level analysis of average car price reveals which departments tend to purchase higher-priced vehicles. This suggests differences in budget allocation or functional requirements across departments.

Conclusion
This dashboard successfully brings together sales data, buyer demographics, and company information to provide a consolidated view of car sales performance. The insights reveal clear trends in pricing, geographic purchasing power, brand dominance, and buyer preferences. Overall, the analysis supports informed decision-making by highlighting key market patterns and areas of strategic focus.
