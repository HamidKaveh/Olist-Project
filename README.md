<div style="text-align: center;">
    <p style="background-color:#f2af29;font-family:serif;color:#000000;font-size:200%;text-align:center;border-radius:10px 10px;"><b>Brazilian E-Commerce Public (Olist) Project</b></p>
</div>

<p style=font-family:serif;text-align:right><h1><b> Content: </b></h1></p>

       
* #### [**Introduction**](#1)
    
* #### [**Data Description**](#2)

* #### [**Exploratory data analysis**](#3)

    * ##### [**Importing Libraries and Datasets**](#4)

    * ##### [**Customers Dataset**](#5)

    * ##### [**Geolocation Dataset**](#6)
    
    * ##### [**Orders Dataset**](#7)

* #### [**Summary**](#8)

* #### [**Constraints & Future Work**](#9)

# <a id="1"></a><p style="background-color:#f2af29;font-family:serif;color:#000000;color:#000000;font-size:100%;text-align:center;border-radius:10px 10px; width:400px; height:30px"><b>Introduction</b>
<img src="https://cdn.pixabay.com/photo/2019/12/14/08/36/shopping-4694470__340.jpg" alt="Olist" style="width: 600px; height: 350px;">
    
<br>Recently, there has been a growing trend in online shopping. This project works with a Brazilian e-commerce public dataset of orders made at the [Olist Store](https://olist.com/pt-br). The dataset provides information about customers' orders from 2016 to 2018 made at multiple marketplaces in Brazil.
This dataset was generously provided by [Olist](www.olist.com), the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants can sell their products through Olist Store and ship them directly to the customers using Olist logistics partners. After a customer purchases the product from Olist Store, a seller gets notified to fulfill that order. Once the customer receives the product or the estimated delivery date is due, they get a satisfaction survey by email where they can give a note for the purchase experience and write down some comments.

</p>

# <a id="2"></a><p style="background-color:#f2af29;font-family:serif;color:#000000;color:#000000;font-size:100%;text-align:center;border-radius:10px 10px; width:400px; height:30px"><b>Data Description</b>

As I mentioned above, the dataset period is from 2016 to 2018. In this analysis, however, I just used 2017 and 2018 (January 2017 - August 2018) data because there was not enough data for other years or they are missing for some monthes.
<br>The data is divided into multiple datasets, including:
<br><ol type="1">
  <li>Customer Dataset</li>
  <li>Geolocation Dataset</li>
  <li>Order Items Dataset</li>
  <li>Payment Dataset</li>
  <li>Reviews Dataset</li>
  <li>Orders Dataset</li>
  <li>Products Dataset</li>
  <li>Sellers Dataset</li>
  <li>Product Name Dictionary</li>
</ol>
For this analysis, I mainly used customer, geolocation, and order items datasets, and in some cases, products, sellers, and product dictionary datasets. The following picture from the Kaggle website illustrates the relationship between different datasets:  

<img src="https://i.imgur.com/HRhd2Y0.png" alt="Data Relationship" style="width: 600px; height: 350px;">

<br> The rest of this report is a step-by-step approach to answer some business questions. For downloading these datasets from the Kaggle website click [here](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?resource=download&select=olist_sellers_dataset.csv).

</p>

# <a id="3"></a><p style="background-color:#f2af29;font-family:serif;color:#000000;color:#000000;font-size:100%;text-align:center;border-radius:10px 10px; width:400px; height:30px"><b>Exploratory Data Analysis</b>
In this section, after importing necessary libraries and raw datasets, and cleaning the data, I will use each datasets seperately for analyzing. 

</p>

## <a id="5"></a><p style="background-color:#d3f8e2;font-family:serif;color:#000000;font-size:100%;text-align:center;border-radius:10px 10px; width:300px"><b>Customers Dataset</b></p>

## <a id="6"></a><p style="background-color:#e4c1f9;font-family:serif;color:#000000;font-size:100%;text-align:center;border-radius:10px 10px; width:300px"><b>Geolocation Dataset</b></p>

## <a id="7"></a><p style="background-color:#f694c1;font-family:serif;color:#000000;font-size:100%;text-align:center;border-radius:10px 10px; width:300px"><b>Orders Dataset</b></p>

# <a id="8"></a><p style="background-color:#f2af29;font-family:serif;color:#000000;color:#000000;font-size:100%;text-align:center;border-radius:10px 10px; width:400px; height:30px"><b>Summary</b>
#### **In this case study, I only used some Olist datasets (customers, geolocation, and orders datasets) and the relations between them for exploratory data analysis (EDA).** 
#### **-Using the ‘customers dataset’ and ‘geolocation dataset’ for finding information on sales and orders in each state and city and visualizing them.**
#### **-Using ‘orders dataset’ in order to calculating the sales, freight values, revenue, and then comparing the performance of the company in 2017 and 2018.**


# <a id="9"></a><p style="background-color:#f2af29;font-family:serif;color:#000000;color:#000000;font-size:100%;text-align:center;border-radius:10px 10px; width:400px; height:30px"><b>Constraints & Future Work</b>
    
#### **The most important constraint while analysing the dataset was insufficient datasets for many months. For instance, we did not have enough data for 2016, 2018 and even some months in 2017.**
#### **As I did not use all datasets in my alalysis, other datasets can be used for future work, such as 'order reviews' data for NLP analysing or predicting the future sales using machine learning methods. Finally, we can use dash for having better and interactive visualization.**
