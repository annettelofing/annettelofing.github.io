---
layout: post
title:  "Coffee Shop Analysis in Excel"
date:   2023-12-09 15:10:39 -0500
categories: [Excel, Project, Maven Analytics, Dashboard]
tags: [excel,project,portfolio,analytics,analysis,coffee shop,sales,evaluation,stakeholders,self-directed] #always lowercase for tag names
image: 
    path: /assets/images/coffee-shop-analysis-excel/Coffee Shop Analysis Excel-Featured-Image.png"
    alt: Coffee Shop Analysis in Excel
--- 



I evaluated transaction records for Maven Roasters, a fictitious coffee shop operating out of three NYC locations. Dataset includes the transaction date, timestamp and location, along with product-level details.

## Overview 

**Software:** Excel <br>
**Skills:** Pivot Tables, Pivot Charts 

## Familiarize Thyself with Thy Data

<p> 
My first approach with this project was to familiarize myself with the data table. 
</p>

<p>
Upon first glance, I noticed everything was organized into one table. 
Each row is associated with a unique transaction_id, and there are <b>149,456 rows in total</b>. 
</p>

<p>
Through glancing at the transaction_date field throughout the rows, I can see that this data traverses <b>January 1, 2023 to June 30, 2023. </b>
</p>

<p>
This data is also across three different store locations and includes product information as well as transaction information. 
</p>

<p>
There doesn’t appear to be any data cleaning needed, as everything is formatted and spelled correctly. 
</p>

<caption>Preview of Transacation Data below: </caption>
<img src="/assets/images/coffee-shop-analysis-excel/first-30-rows-of-transaction-data.png" alt="Preview of Transacation Data" class="">


## Questions to Answer  

1. How have Maven Roasters sales trended over time?
2. Which days of the week tend to be busiest, and which are the slowest?
3. Which products drive the most revenue for the business?

## Create Columns for Digging Deeper

<p>
<b>Revenue Column: </b><br>
Transaction_qty * unit_price <br>
This column lists the revenue created for each transaction. 
</p>

<p>
<b>Month Name Column: </b><br>
I extracted the month from the transaction_date column using this formula: 
<br>
=TEXT(B2,"mmm") 
</p>

<p>
<b>Weekday Name Column:  </b><br>
I extracted the weekday name from the transaction_date column using this formula:  <br>
=TEXT(B2,"ddd")
</p>

<p>
<b>Hour Column: </b><br>
I extracted the hour from the transaction_time column using this formula: <br>
=HOUR(C2)
</p>
<p>
For every column value listed above, I forced the formula down on each row of each column. This allowed me to create values based on information in each row.
</p>

<img src="/assets/images/coffee-shop-analysis-excel/additional-columns.png" alt="Additional Columns in Excel" class=""  width="400" height="500">

## Pivot Tables and Pivot Charts  

<p> 
After creating these additional columns to add supporting information to the pivot tables/columns, I created 5 pivot tables to start looking closer at the data. 
</p>

<img src="/assets/images/coffee-shop-analysis-excel/revenue-by-month.png" alt="Revenue by Month" class="" width="400" height="500">

<img src="/assets/images/coffee-shop-analysis-excel/transactions-by-weekday.png" alt="Transactions by weekday" class="" width="400" height="500">

<img src="/assets/images/coffee-shop-analysis-excel/transactions-by-hour.png" alt="Transactions by hour" class="" width="400" height="500">

<img src="/assets/images/coffee-shop-analysis-excel/transactions-by-item.png" alt="Transactions by item" class="" width="400" height="500">

<img src="/assets/images/coffee-shop-analysis-excel/top-15-products-transactions-revenue.png" alt="Top 15 Products" class="" width="400" height="500">

<p>
The first four pivot tables I created allowed me to create pivot charts for the specific data I wanted to see. 
</p>

<p>
Afterwards, I put everything together in one cohesive dashboard. I added a filter based on the coffee shop location that adjusts for all of the dashboard charts and tables. 
</p>

<img src="/assets/images/coffee-shop-analysis-excel/dashboard-entire-screen-astoria.png" alt="Entire Screen of Dashboard" class="">


## Initial Insights  

* Every location increased their revenue from January to June.
* The top 3 products at every coffee shop location were 
    * Brewed Chai tea 
    * Gourmet brewed coffee 
    * Barista Espresso
* Coffee had the most transactions by category at every coffee shop location. 

## Suggestions by Location


### Astoria 
* Astoria’s location is doing well overall, but I would suggest re-evaluating the store hours for Saturday’s. This is the slowest day and they could lower overhead costs by only being open during their most popular hours. 

<!-- ## Astoria's Location Dashboard  -->
<img src="/assets/images/coffee-shop-analysis-excel/dashboard-astoria.png" alt="Astoria Dashboard" class="">


### Hell's Kitchen 
* Hell’s Kitchen location’s transactions tapers off significantly at 8:00pm, they could close this location early and not lose much revenue. 
* Hell’s Kitchen’s busiest hours are between 8 and 10 am. I would suggest adding promotions during this time, and increasing staff during this time. 

<!-- ## Hell's Kitchen Location Dashboard  -->
<img src="/assets/images/coffee-shop-analysis-excel/dashboard-hells-kitchen.png" alt="Hell's Kitchen Dashboard" class="">



### Lower Manhattan 
* Lower Manhattan’s transactions start to slow down at 7:00pm and they are open until 9:00pm. They could close this location earlier and focus on their high sale numbers between 7 and 10 am during the morning rush hours. 
* Lower Manhattan sees a huge spike in sales on Monday’s, they could take advantage of strategic promotions to increase revenue during Monday’s. 

<!-- ## Lower Manhattan's Location Dashboard  -->
<img src="/assets/images/coffee-shop-analysis-excel/dashboard-lower-manhattan.png" alt="Lower Manhattan's Dashboard" class="">


## Thanks for Reading! 
<a href="/assets/documents/Coffee-Shop-Sales-Lofing-Annette.zip" download>Click Here to Download the Excel Project File</a>