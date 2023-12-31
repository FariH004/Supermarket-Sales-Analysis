# Supermarket-Sales-Analysis
 Analysis on sales of supermarkets.

 ![Alt text](images.jpeg)


How to run the project ?:

1. Install Jupyter notebook
2. Clone the project and save it as the folder Supermarket-Sales-Analysis.
2. Install packages by opening a terminal/command prompt.
    
    //pandas
    
    pip install pandas

    //numpy
    
    pip install numpy

    // matplotlib.pyplot
    
    python -m pip install -U pip 
    
    python -m pip install -U matplotlib

    //seaborn
    
    pip install seaborn

3. On the command prompt/terminal run the command 'jupyter notebook'. This should open the browser with an instance of a running jupyter kernel.
4. Click on the upload button and select and upload the project folder Supermarket-Sales-Analysis.
5. Navigate into that folder and open the code.ipynb file.
6. Click on Cell and then Run All.

Abstract:

The supermarket is an essential part of our daily lives. A supermarket is a self-service store that is divided into sections and offers a broad selection of food, beverages, and home items. It is larger and has a wider assortment than older grocery stores, but it is smaller and offers a narrower choice of products than a hypermarket or big-box store. Even though consumers are increasingly purchasing online, the number of supermarkets continues to grow. More and more people are focusing on one thing: speed, enjoyment, or convenience. Supermarkets are expanding in the most densely populated places, and market rivalry is intense. This dataset represents one of the historical sales of a supermarket firm, which was recorded for three months in three distinct branches. With these datasets, predictive data analytics approaches are simple to implement. The dataset contains historical sales data from three separate supermarket outlets from January to March 2019. (Sales - Analysis and Visualization, n.d.)


About Data Set:

This section explains the characteristics of the Supermarket sales data. (Sales - Analysis and Visualization, n.d.)

Invoice id: Invoice identification number generated by a computer
Branch: Supercentres branch (3 branches are available identified by A, B, and C).
City: Supercentres locations
Customer type: Customers are classified as Members when they use a member card and as Normal when they do not.
Gender: The customer's gender
Product line: Electronic accessories, Fashion accessories, Food and beverages, Health and
beauty, Home and lifestyle, Sports and travel are the general item categorization groups. Unit price: Each product's cost in dollars
Quantity: Customer's total number of purchases
Tax: Customer purchases are subject to a 5% tax.
Total: The total price includes tax.
Date: Purchase date (Record available from January 2019 to March 2019)
Time: Time to purchase (10 am to 9 pm)
Payment: Customer pays for purchase (3 methods available: cash, credit card, and e-wallet) COGS: Cost of goods sold
Gross margin percentage: Gross margin percentage
Gross income: Gross income
Rating: Customer feedback on their overall shopping experience (On a scale of 1 to 10)

Most of the datasets can be classified as numerical data or categorical data. Nominal, ordinal, interval and ratio scales are the four types of data measuring scales. I plan to use visualizations to show how sales change as a function of categories and numerical variables.

HYPOTHESIS:
My underlying hypothesis is that the product's sales are correlated with its rating.For this prediction I have done correlation analysis and produce density plots, scatter plots, and regression plots to see how the product sales vary with their rating.


After performing the analysis as explained in 'Markups' in the code.ipynb, we get the following results:

Inference:
1. The supermarket received a fair 7 out of 10, on average. For a supermarket aiming to increase sales and profit margins, this is not good enough. Owner should make an effort to enhance client purchasing experience. The client is king, as the phrase goes.
2. We can observe through an investigation of the relationship between unit price and quantity using a scatterplot that demand for commodities is not always influenced by price. The owner should therefore buy more of the things that are thought to be more expensive in order to increase profits.


Challenges faced:
1. I utilized the data set of 500 observations for the scatter plots in order to make them understandable and clear, and the data set of 1000 observations for the other models because if I use a sample of data for the bar plots, the results will be altered from the original findings. Thus, I simply used a sample of the data for scatter plots.
2. I found that, contrary to what I had previously thought, the Date and Time columns actually include an object datatype by looking at the details of the data collection. I have to switch the object data type to a Date data type as a result. After changing the data type, I had to follow a specific format for the "date," "day," "month," "year," "time," and "hour." I then had to check the data set for any missing values;



Analysis results:
To perform fundamental EDA on the data from the supermarket sales, we performed univariate, bivariate, and correlation analysis.
The following is a summary of some of the data's results and observations:

1. There is no correlation between gross income and customer ratings, which are more or less uniform with a mean rating of roughly 7.A scatter plot with a trend line between gross income and rating was created using a scatter plot node. We can infer that gross income does not significantly affect customer stratification rating because the trend line is very flat.

2. There are 3 cities/branches in the data. Branch C, or Naypyitaw, is the most profitable branch in terms of gross income, despite the fact that branch A has slightly larger sales than the others.
SUPERMARKET SALES DATA ANALYSIS 22

3. E-wallets are the most widely used payment option, however cash payments are also common.

4. Each item's price is evenly spread out from 10 to 100.

5. Male and female consumers make about the same amount of money overall, but female customers spend slightly more around the 75th percentile.
One intriguing finding from the correlation research is that customer reviews are unrelated to any variable.

6.The quantity demanded is unaffected by price.

8.The majority of shoppers gave the supermarket fair reviews.
