# Home_Sales
This repository contains code snippets and solutions for analyzing home sales data using PySpark. The dataset consists of home sales information, including attributes such as date of sale, price, number of bedrooms and bathrooms, square footage, and more.

Analysis Overview
In this analysis, I explored several questions related to home sales data:

Average Price for a Four-Bedroom House Sold Each Year: I calculated the average price for a four-bedroom house sold each year, rounded to two decimal places.

Average Price of a Home for Each Year Built with Three Bedrooms and Three Bathrooms: I calculated the average price of a home for each year the home was built, considering only homes with three bedrooms and three bathrooms, rounded to two decimal places.

Average Price of a Home for Each Year Built with Specific Criteria: I calculated the average price of a home for each year the home was built, considering homes with three bedrooms, three bathrooms, two floors, and a size greater than or equal to 2,000 square feet, rounded to two decimal places.

Average Price of a Home per "View" Rating: I calculated the average price of a home per "view" rating, considering only those with an average home price greater than or equal to $350,000. I also determined the runtime for this query, rounded to two decimal places.

Conclusion
Through my analysis, I gained valuable insights into the housing market:

The average price for a four-bedroom house sold each year varied slightly, ranging from approximately $296,363.88 to $301,819.44.
Homes built in different years with specific criteria, such as three bedrooms, three bathrooms, two floors, and a size greater than or equal to 2,000 square feet, had varying average prices.
Certain "view" ratings had higher average home prices, with ratings such as 99, 98, and 97 exceeding $1,000,000 on average.
The runtime for these queries varied depending on the complexity of the analysis.
This analysis provides valuable insights for homebuyers, sellers, and real estate professionals to understand market trends and make informed decisions.

For detailed code implementations and analysis results, refer to the respective Jupyter Notebook files in this repository. 
