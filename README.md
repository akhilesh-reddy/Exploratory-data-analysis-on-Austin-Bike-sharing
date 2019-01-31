## Austin Bike sharing

### Table of contents
* [Introduction](#introduction)
* [Technologies](#technologies)
* [Approach](#approach)
* [Insights](#insights)

### Introduction
Traffic is always a painful problem for both authorities and commuters. Recently bike sharing has evolved as a viable alternative to both reduce traffic and pollution.In this project, we have performed exploratory data analysis to understand the different aspects that affect bike sharing and recommendations for bike rebalancing

[Understanding bike sharing behavior in Austin.ipynb](https://github.com/akhilesh-reddy/Visualizing-different-factors-that-affect-Austin-bike-sharing-and-insights-for-bike-rebalancing/blob/master/Understanding%20bike%20sharing%20behavior%20in%20Austin.ipynb) file has the code for the analysis
[Austin bike sharing.pdf](https://github.com/akhilesh-reddy/Visualizing-different-factors-that-affect-Austin-bike-sharing-and-insights-for-bike-rebalancing/blob/master/Austin%20bike%20sharing.pdf) has the final presentation

### Technologies
Project is created with:
* Python 2.7   
**Datasource**
* Austin bike sharing dataset from Kaggle   

### Approach:
The entire analysis is divided into three parts mainly

1.Exploratory Data analysis  
    Following are the different cuts at which we will be looking at the data.  
    i.Location  
    ii.Membership      
    iii.Time   
    iv.Weather   
    v.Demographics    
2.Inference about the traffic using descriptive analysis and visualizations  
3.Insights   

### Insights:
* The Walk up membership accounts over 60% of the rides. Most of the rides taken are on weekends and are more on a ad-hoc base.  
* 24 - hour kiosks is the most popular bike sharing plan  
* Bike sharing traffic is high between 9 AM and 8 PM as expected  
* During ACL, there are peaks in the morning at 11 AM due to people going to ACL and at 10 PM due to people coming back from ACL   
* Different weather conditions affect bike sharing in different ways  
    During Rainy season, there is 67% drop in bike sharing on average    
    During Summer, there is 36% drop in bike sharing on average   
    During Winter, there is 72% drop in bike sharing on average   
* The locals are renting more bikes on weekdays, which causes the bike rebalancing problem during rush hours.  
* The above results has taken the spike of trips during SXSW and ACL into consideration.  


