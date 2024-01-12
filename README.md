# London-Housing-Market-Analysis
London Housing Market Analysis


![image](https://github.com/mtchagoue/Retail-data-analysis/assets/115325778/29f1b8b9-d056-4179-a530-0272ab58b02f)



## **Introduction:**
London is the 7th most expensive property market in the world, with an average asking price of $2,090 per square foot. It is also the 4th most expensive city in the world. London is the most expensive region in the UK to buy a home.

## **Problem Statement:**
Our focus here is to find the average price, the safest neighborhood, the number of house sold monthly and as  many insights as possible.
Few of the questions we will be answering:

 What is the maximum & minimum 'average price' per year in England ?
 
 What is the Maximum & Minimum No. of Crimes recorded per area ? 
 
 Are you thinking about buying in London? We will show you the different area, where average price is less than 100000 pounds
## **Data sourcing:**
Datalink: This is the link where we get the data from : https://www.kaggle.com/datasets/justinas/housing-in-london 


## Analysis and Visualization:

## Analysis:

Data Has over 13500 rows and 6 columns. During the analysis we had convert date columns into the date-time format. (pd.to_datetime(data.date)). The tricky part here was adding a new column "month" as 2nd column in the DataFrame which contains only month(data.insert(1, 'month, data.date.dt.month).
we have 104 cities with number of crimes 0. (good to buy a house there for safety concerns 😉 )
we were able to find the average, minimum and maximum price per year which is really an important insights to see how the markets have grown and also the value gainedby house per areas.
Last but not least the average price per aread is a good insight as it can guide you according to your budget.


## Visualization:

See below the visualization on Tableau Public.

![image](https://github.com/mtchagoue/Retail-data-analysis/assets/115325778/ba9bc82b-6dfa-46aa-963d-77ab13472154)



https://public.tableau.com/app/profile/archange.tchagoue1597/viz/LondonHousingAnalysis_17050189047360/LondonHousingAnalysis?publish=yes


![Thank you](https://github.com/mtchagoue/Retail-data-analysis/assets/115325778/cbc6f815-8a9d-4bcd-b4ae-314dffc3f80a)
