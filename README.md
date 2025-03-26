![Dashboard  Screenshot 1](https://github.com/user-attachments/assets/8c423a51-281c-45f2-a234-291650b53718)

![Dashboard  Screenshot 2](https://github.com/user-attachments/assets/eb8181bb-ad3b-44d0-a8cb-a8cba1ded731)

# Introduction:
This project involved creating two dashboards using Tableau to analyse and present sales and customer data. The Sales Dashboard focuses on key metrics like sales trends, profit, and performance over time, while the Customer Dashboard provides insights into customer behavior, order trends, and key customer segments. The dashboards serve as interactive tools for stakeholders, including sales managers and executives, to make data-driven decisions and enhance strategic planning.

# Project Files:
- **Dashboard File:** The Power BI dashboard file is available here: [Dashboard File](https://github.com/MadhurShekharBand/Tableau_Project_-_Sales_Dashboard/blob/27c6e4443b212920dffb596d2f4378150136635f/Dashboard%20-%20Tableau%20File.twbx)
- **Data Files:** The data files in Microsoft Excel Comma Separated Values File (.csv) format are available here: [Data Files](https://github.com/MadhurShekharBand/Tableau_Project_-_Sales_Dashboard/tree/27c6e4443b212920dffb596d2f4378150136635f/Dashboard%20Icons)
- **Dashboard Images:** The images used in the dashboard are available here: [Dashboard Images](https://github.com/MadhurShekharBand/Tableau_Project_-_Sales_Dashboard/tree/c102a9138f4e4d8fa9facbb2c55e4a3240977e45/Dashboard%20Images)

# Background:
### The questions I wanted to answer through my SQL queries were:
- **What are the total sales, profits, and quantities for the current year and the previous year?** <br>
By summarizing these KPIs, we can evaluate overall business performance and identify any significant growth or decline trends. This insight helps in understanding revenue progression, profitability, and changes in demand over time, aiding in strategic planning and resource allocation.

- **How have sales, profits, and quantities fluctuated on a monthly basis for both the current and previous year?** <br>
Analyzing monthly trends allows us to identify peak sales periods and seasonal variations. Recognizing the highest and lowest sales months can help in optimizing inventory, marketing efforts, and promotional strategies to maximize revenue during high-performing months and improve sales in low-performing ones.

- **Which product subcategories have performed the best and worst in terms of sales and profit in the current and previous year?** <br>
Comparing product subcategories helps in identifying high-performing and underperforming categories. This analysis supports better product management decisions, such as promoting bestsellers, phasing out low-demand items, and adjusting pricing strategies to maximize profitability.

- **What are the weekly sales and profit trends for the current year, and how do they compare to the average?** <br>
Tracking sales and profit on a weekly basis helps detect short-term fluctuations and patterns. By highlighting weeks above and below the average, we can understand external factors impacting performance (e.g., holidays, market trends) and take proactive measures to optimize revenue streams.

- **How many customers placed orders, what was their total sales contribution, and how many orders were placed in the current and previous year?** <br>
Summarizing the number of customers and their sales contribution helps in understanding customer base expansion and engagement. This insight can guide customer retention strategies and personalized marketing efforts to enhance customer lifetime value.

- **How have customer sales and order trends changed on a monthly basis for both the current and previous year?**
Understanding customer buying behavior over time helps businesses adjust sales strategies, promotional offers, and customer engagement efforts. Recognizing months with peak or declining customer activity can lead to targeted interventions to sustain customer interest.

- **How are customers distributed based on the number of orders they have placed?**
Segmenting customers by order frequency reveals purchasing behavior, loyalty, and engagement levels. This insight can help create targeted loyalty programs, personalized recommendations, and strategies to convert one-time buyers into repeat customers.

- **Who are the top 10 customers by profit, and what are their total orders, sales, and last order date?**
Identifying top-performing customers helps businesses understand their most valuable clients. By tracking their engagement and purchase behavior, companies can develop tailored retention strategies, exclusive offers, and premium customer service to sustain high-value relationships.

### About the Dataset:
The datasets consist of four files: Customers, Location, Orders and Products. Together, these datasets offer a comprehensive view of customer information, locations, order transactions, and product details, which can be useful for business analytics and decision-making.
<br>
<br>
The Customers file contains Customer ID and Customer Name. Location file provides geographical details such as City, Country/Region, Postal Code, Region, and State. Orders file includes transactional details like Customer ID, Order Date, Order ID, Postal Code, Product ID, Segment, Ship Date, and Ship Mode. And the Products file lists product details such as Category, Product ID, Product Name, and Sub-Category.

### Tools I Used:
For my deep dive into the datasets, I harnessed the power of one key tool:
- **Tableau:** For this project, Tableau was the primary tool used to analyze and visualize the data. Tableau allowed me to easily connect to the datasets, perform various transformations, and create interactive visualizations to answer the key questions.

# Overview of the Dashboard:
The dashboard has 10 Key Performance Indicators (KPIs) which answers all the questions mentioned in the “Background” section.
<br>
<br>
To allow the user to focus on a specific part of the data, I have made two dashboards, sales dashboard and customer dashboard, with the ability to easily switch between them. Both the dashboards are fully dynamic and has one filter (as shown below) to allow the user to select specific year, product category and location.

![Dashboard  Screenshot 3](https://github.com/user-attachments/assets/dc5403b2-3757-4d31-a294-8691ac356289)

# Insights:
- The overall sales trend indicates a positive YoY growth, particularly in the latter half of the year. The sharp increase in November suggests a seasonal effect (potential holiday promotions or peak demand). The decline in May and December may require further investigation (market conditions, inventory issues, or pricing strategies).
- In terms of customer sales trends, August and January saw the highest growth, likely due to seasonal promotions or increased high-value purchases, while May, March, and April experienced declines, suggesting lower demand or reduced marketing effectiveness. This indicates the need for targeted strategies to boost sales during slower months while capitalizing on peak periods with well-planned promotions and inventory management.
- More orders indicate higher customer engagement and potential expansion in market share. November’s spike aligns with increased sales and suggests seasonal demand or effective promotional campaigns.
- Raymond Buch is the top customer. The top 3 customers contributed significantly to profit, indicating high-value transactions. Most high-profit customers have low order counts (2-5 orders), suggesting large transaction values per order. Retaining and expanding relationships with high-value customers should be a priority.
- The best-performing product subcategories in terms of sales and profit were Phones, Copiers, and Accessories, indicating strong customer demand and effective pricing strategies. These categories contributed significantly to overall profitability and revenue growth. On the other hand, Tables, Machines, and Bookcases struggled, with losses suggesting inefficiencies in pricing, high costs, or weak demand. Addressing these issues by optimizing cost structures and revising pricing strategies could improve performance.


# Conclusion:
### What I Learned:
Through this project, I gained practical experience in utilizing Tableau to process and visualize complex datasets. I learned how to design interactive dashboards, apply filters, and create meaningful visualizations to answer business questions. Additionally, the project deepened my understanding of sales analysis, helping me recognize the importance of seasonal trends, product performance, and customer engagement in driving business decisions. I also gained insights into the importance of analyzing both high-level KPIs and trends to provide actionable recommendations.

### Closing Thoughts:
This project was an excellent opportunity to develop both my technical skills in Tableau and my ability to translate business requirements into actionable insights. By visualizing key metrics and trends, I was able to make data-driven recommendations that could have a significant impact on the company’s strategy. Going forward, I aim to continue improving my proficiency in Tableau and explore more advanced analytics techniques to further enhance business performance analysis.

