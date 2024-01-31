# Pizza-Sales-Analytics
## Power BI Dashboard for Sales Optimization
### Introduction
In response to the challenges faced by Domino's Pizza Outlet in Mumbai, this project aims to leverage data-driven insights to enhance sales and operational efficiency. The provided Excel dataset encompasses four interrelated tables, with two focusing on comprehensive order information throughout the year 2022, and the remaining two detailing the food varieties and their corresponding prices. By harnessing the power of data, the goal is to empower the pizza outlet with informed decision-making tools that drive growth and customer satisfaction.
### Objective
1)	To develop an engaging and informative Power BI dashboard that visually present crucial findings derived from the analysis of Domino's Pizza outlet dataset.
2)	To derive actionable recommendations and provide strategic guidance that aligns with business objectives, fostering increased revenue and customer satisfaction.
### Data Cleaning and Preparation
The source dataset exhibited consistency, obviating the need for extensive cleaning. Upon importing the Excel file into Power BI, the following transformations were implemented: 
1.	Utilized the first row as a header for a table lacking designated heading cells, ensuring uniformity in data representation.
2.	Standardized the date format from timestamp to a universally recognized type, promoting consistency for accurate temporal analysis. 
3.	Conditional columns were created to use in analysis,
  *  Introduced a 'Week_time' column by calculating the day from the date and appending a conditional indicator for weekend or weekday. 
  *  Segmented the day into distinct time ranges in a column ‘time of the day’: 
      *  Before 12 PM - Morning
      *  12 PM to 3 PM - Noon
      *  3 PM to 7 PM - Evening
      *  After 7 PM - Night	
  *  Formulated a 'Price_range' column with categories such as, 
      * Up to 200 - Low priced 	
      * 200 to 500 - Medium priced 
      * Above 500 - High priced
### Analysis
#### 1.	Analysis of most sold items
 	  
*	In the initial phase, data integration involved merging tables based on the 'pizza_id' to consolidate relevant information and the total bill amount for each order was calculated.
*	The subsequent step focused on discerning the quantities sold for individual pizzas and various pizza types. Through column merging and subsequent grouping operations, quantities of pizzas sold were accurately identified. 
*	The analysis by ranking reveals that the "Fresh Veggie Vz" category stands out as the most popular pizza type based on the quantities sold. 
*	Surprisingly, the overall most popular dish is identified as the "Double Cheese Margherita," which belongs to ‘double cheese margherita’ category not the most popular pizza type category. This finding underscores the unique appeal and popularity of specific pizza items, even outside the most favourite category.
*	The results suggest an opportunity to leverage the popularity of "Fresh Veggie Vz" by potentially introducing variations or promotions within this category to further boost sales. Additionally, recognizing the appeal of individual items like the "Double Cheese Margherita" highlights the importance of diversifying offerings to cater to distinct customer preferences.

#### 2.	Sales analysis of different categories 
 	 
*	Grouping the categories of items sold to find the outlet’s best categories, it is seen that vegetarian pizzas are the best-selling. This indicates a pronounced customer preference for vegetarian pizza varieties.
*	Non-vegetarian pizzas follow as the second-best-selling category. To maximize sales in this category, a detailed assessment is recommended to determine the root causes behind lower sales compared to veg category. This evaluation should delve into demographic considerations, customer choices, and an analysis of taste preferences and flavours. 
*	Bread and miscellaneous items are identified as the least sold categories in the outlet. This signals a need for a comprehensive menu evaluation. 
*	Strategies such as modifying the menu, introducing new items, or assessing the marketing approach for these categories could revitalize customer interest and drive sales.

#### 3.	Analysis of Quantities sold by price ranges
 		 
*	Merging tables containing prices and quantities facilitated the grouping of sales based on distinct price ranges. This approach provided a comprehensive view of the distribution of quantities sold across various price categories. 
*	A noteworthy finding emerged, revealing that highly priced food categories were sold in larger quantities compared to other items. This surprising trend signifies that customers are inclined towards premium quality and flavours.
*	The strong performance of higher-priced items not only contributes to sales but also reflects positively on the perceived quality and taste associated with the outlet. This insight reinforces the importance of maintaining and potentially enhancing the quality of premium offerings to sustain customer satisfaction and loyalty.

#### 4.	Sales and Orders trends		
 
*	A thorough analysis revealed the total sales and orders taken by the outlet over the entire year, providing a comprehensive overview of its overall performance. 
*	Utilizing trend lines for both sales and orders, a concerning dip in recent times was identified. This notable decline indicates a potential issue that urgently demands attention to understand the root cause and implement necessary adjustments.

#### 5.	Analysis of Sales during Specific Times of the week
      
*	Upon analysing weekday and weekend sales, no significant difference was observed. Sales figures for both weekdays and weekends are nearly identical, indicating a consistent customer engagement throughout the entire week.
*	Column charts depicting sales and orders throughout the day across quarters reveal a consistent trend of peak activity between 12 to 7 PM. This pattern is evident both on weekdays and weekends, emphasizing these hours as the prime periods for customer transactions. 
*	Notably, during weekends, sales peak in the afternoon hours, while on weekdays, the highest sales occur during the evening. This divergence in peak sales times between weekdays and weekends provides valuable insights for optimizing staffing and inventory management during specific periods. 
*	The consistent sales patterns observed throughout the week, irrespective of it being a weekday or weekend, indicate the outlet has successfully established a loyal and engaged customer base. This consistency highlights the potential for strategic marketing and promotional activities to further enhance customer retention and attract new customers.

### Data-Driven Dashboard
 
*	The interactive dashboard effectively communicates crucial insights into the pizza outlet's sales, order patterns, popular dishes, and weekly trends. The use of vibrant colours and slicers enhances visual appeal and user engagement.
*	The trend lines illustrating orders and sales throughout 2022 provide a clear picture of the outlet's popularity and profitability. Identifying recent downward trends emphasizes the need for strategic modifications to ensure sustained success, making it imperative for the business to adapt and thrive. 
*	Bar graphs showcasing sales and order distribution over quarters reveal peak levels during specific times of the day. This data-driven approach facilitates informed decisions for operational enhancements and resource optimization during peak hours, contributing to positive business progressions. 
*	The inclusion of a slicer connected to trend lines and bar graphs enhances interactivity, enabling a nuanced understanding of trends disparities between weekends and weekdays. This feature assists in tailoring strategies based on the specific demands of different days, fostering adaptability and responsiveness.
*	The tree map visualization offers a dynamic representation of food varieties based on quantities sold, providing valuable insights into the popularity of specific items. This aids in menu optimization, guiding decisions to enhance both the quality and quantity of dishes, ultimately catering to customer preferences and increasing overall satisfaction. 

### Recommendations
*	Implementing seasonal offers and discounts, especially on the popular category and the best-selling item can be a strategic move to create excitement and stimulate sales.
*	Evaluate the least popular food items to assess their quality and taste, to consider either refining these items to align with customer expectations or strategically removing them from menu. This ensures a streamlined menu that meets customer preferences and enhances overall satisfaction. 
*	Given the significant sales post 12 PM, it is crucial to focus on optimizing management services during these peak hours. This includes ensuring efficient staffing levels, reducing wait times, and streamlining the delivery process. Improving service efficiency during peak periods will contribute to a positive customer experience, potentially leading to increased loyalty and word-of-mouth recommendations.
*	Leverage the popularity of the 'double_cheese_margherita' and the 'fresh_veggie_vz' category in marketing campaigns. Highlighting these popular items in promotional materials, both online and offline, can attract new customers and reinforce the preferences of existing ones.
*	To address the recent downturn, a strategic adjustment plan needs to be implemented promptly. This involves a detailed analysis of operational, marketing, and customer satisfaction aspects to identify and rectify any issues affecting sales. By swiftly addressing the underlying factors, the outlet can regain its profit trajectory and maintain a positive growth trajectory. 
*	Establish a robust customer feedback mechanism to continuously monitor and gauge customer satisfaction and their experience. This information will be valuable in making data-driven decisions to further enhance the menu and service offerings.

