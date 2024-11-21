## RESTAURANT INVENTORY SALE REPORT

![image](https://github.com/user-attachments/assets/e0c963fc-8e7b-4065-a95c-939ab414a9d3)

## VISUALS:
### Top 10 Best selling items 
From this visual, we can deduce that the Veg Alfredo Pizza pizza was the best-selling item over the course of 12 months, with 10,452 units sold. I decided to use a line chart to clearly show the sales trend between the top 10 items.

### Top 10 Worst selling items 
From this visual, we can deduce that the Cheese fries were the worst-selling item over the course of 12 months, with 9,628 units sold. 

### Sales by Month
From this visual, we can deduce the top performing months were January and August with 30,800 sales, followed by May at 30,700 sales and then March and October at 30,600 sales. The lowest selling month was February at 28,500 sales.

### Sales by Month (Lowest to Highest)
This visual is to represent the worst-selling and best-selling months. This visual is useful to quickly analyse which months were the best-performing.

## ANALYSIS: 

#### SALES ANALYSIS
- Total yearly sales are 361,785
- This means average monthly sales equate to 30,148.75
- February is the lowest selling month. However, it's important to know that February has fewer days than any other month.
- August is the highest selling month. As mentioned earlier, this could be due to school holidays and tourism.

#### TRENDS 
- The top 3 lowest-selling items are all in the forms of fries. The top 3 best-selling items were 2 Pizzas and 1 garden salad. This could give us an indication the restaurant is Italian themed, due to the sales of Pizza and veggie dishes. The lack of sales from cheese, Peri Peri and masala fries could indicate the type of customers in the store.
- Sales climbed from June to August. This could be due to school summer holidays as well as potential tourists (as it's summertime)
- Months in which sales were on a downward trend (February, April, June and September) always rebounded strongly with sales reaching over 30,000. This could be due to many factors. Some logical reasonings could be due to sales (to help recover from the downward trend), seasonal change or a lack of school holidays.

#### OTHER TRENDS TO CONSIDER
- February has fewer days. While this doesn't entirely account for the sales drop, it's an important factor to keep in mind.
- Religious events like Ramadan could affect sales. Whilst Ramadan doesn't specifically prohibit people from eating for 24 hours, it may deter people from ordering due to scheduling reasons.
- Seasonal changes and school holidays are likely to be influencing factors in sales trends.

## BRIEF GUIDE ON WORKFLOW: 
Here is a brief explaination on the workflow which I used for this project.

### SQL
I used SQL to perform data cleaning and data aggregation. There were some columns which were not needed, so I removed them. Following this, I spent time getting a better understanding of the dataset writing queries. One example of me getting a better understanding was to write a query to see the total sales per month. Here's the query I wrote:

![image](https://github.com/user-attachments/assets/18cfe2db-e49b-4eb2-ad3b-29e7290383e5)

And here is the result:

![image](https://github.com/user-attachments/assets/4330c99f-2f68-4976-abdb-7c4710acef7c)

This is only one example of aggregating the data to get a better understanding, since I want to keep this report brief. Now we know the total sales per month, but we can't visualise it. For this, we need Python (and Power BI, but Power BI is more of a final stage process)

### PYTHON
After cleaning and getting a better understanding of the data, I moved onto Python. Here is where I conduct analysis of the data using the Matplotlib and Pandas library. I utilised these libraries to create visualisations of the data. Whilst we can create visualisation in Power BI, it's important to see what our charts would look like here and to make sure everything is correct. Here's a screenshot of the code I used to create a line chart which displays the total sales per month:

![image](https://github.com/user-attachments/assets/d453d61e-13ee-4220-b9b7-a214ae32350a)

And here is a result of this specific code:

![image](https://github.com/user-attachments/assets/a8bcc17d-89a9-4b87-ab53-52ce2bbaf624)
