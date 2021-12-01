# How successful are Black Friday Sales for the e-commerce sector ?

## Motivation

Each year, millions of people worldwide are filled with anticipation for Black Friday: Customers looking for good bargains and merchants hoping to increase sales. Taking the merchant’s perspective, this project is trying to generate insights on wether or not Black Friday Sales are a good idea. 

## Data 
Although being a Mid-term Project of an intensive Data Analytics Course, the research question has been addressed using real data of a Brazilian e-commerce marketplace integrator who is empowering small businesses from all over Brasil to sell online. The Public Dataset has been published by Olist (www.olist.com) and is available on Kaggle (www.kaggle.com/olistbr/brazilian-ecommerce). 

## Description 
Focusing on sales data from 2017, the key findings of the explanatory data analysis (EDA) are: 

1. Black Friday (BF) is the best and the day after BF the second best selling day of the year.
2. Cyber Monday (CM) is the third and the day after CM the fourth best selling day of the year. 
3. The time period from Thanksgiving to two days after CM are the seven consecutive days with the highest sales and the two weeks including BF and CM account for more than 10 Percent of all sales within 2017. 

Moreover, the hypothesis that “The total sales on an average day are not different than the total sales on Black Friday.” can be rejected, providing strong evidence that, in fact, sales on an average day are much lower than on BF (stat: -295.32 / p = 0.0). 

Looking at the development of total sales in 2017, the key findings of the visual analysis are: 

1. Overall, total sales tend to increase throughout the year, indicating a positive trend.
2. Before BF, there is a drop in total sales, indicating that some customers might have postponed their orders.
3. After BF, there is as well a drop in total sales, indicating that customers might have preponed their orders.

Lastly, a simple linear regression model has been used to forecast sales during the time period which is influenced by BF Promotions (a few weeks before and after BF). Calculating the differences between the sales predicted by the model (i.e. the sales that would have been generated without BF Promotions.) and the actual sales indicate an increase in total sales due to promotions (the model is able to explain almost three quarters of the variation in total sales in 2017.). 

The "Success" of BF Promotions is strongly affected by the selection of the cut-off point / duration of the forecasting period. A more conservative approach might be to look at all remaining weeks (increase in sales: about 20%) whereas a more optimistic approach might be to take the cut-off point in mid-December (increase in sales: about 40%). 

## Presentation
A Tableau presentation has been created to present the key findings of my analysis to my classmates (https://public.tableau.com/views/BF_16372629643000/Story1?:language=en-US&:display_count=n&:origin=viz_share_link). 
