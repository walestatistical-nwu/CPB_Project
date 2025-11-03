### Customer's Purchasing Behaviour (CPB) Project
#### Motivation
The Management of ABC Inc. desired to leverage customers' economic choices and social characteristics data
to understand their purchasing patterns and use insights gained from the process to enhance the company's product sales, thereby positively impacting its annual bottom line.

#### Project Overview
In the project, four business questions and a hypothesis — 'All (Male and Female) customers purchase equally vs All customers do not purchase equally' — were interrogated through the analysis of a subset (1,966 records x 11 features) of the dataset sourced from [https://www.kaggle.com/brijbhushannanda1979/bigmart-sales-data] and through a 2-level data analysis approach. Machine learning classification models were constructed and consequent exploratory data analyses performed, to generate insights used to provide marketing strategy recommendations to the management team, towards achieving the goal of increased yearly profit for the company.   

#### Data Analytics Process
The 2-level data analysis procedure consists of:
1.	Level 1 – Segmentation modeling of the Customer’s purchasing behaviour using the – 
    a.	Recency, Frequency, and Monetary (RFM) analytical framework,
    b.	K-Mean Nearest Neighbour classification modeling,
    c.	Hierarchical classification modeling, and
  	d.  Performance of a statistical significance test to ascertain whether all (male and female) customers exhibit similar 
        purchasing behaviours.
3.	Level 2 – Exploratory Data Analysis (EDA) of the identified Customer segments

#### Result
##### Findings & Interpretations
1.    Four clusters of customers with similar RFM characteristics were revealed.
2.    Further analyses and interpretation of the customer clusters identified:
      a. Cluster 2 as 'Premium' customer segment
      b. Clusters 1 & 3 as 'Opportunity' customer segments
      c. Cluster 4 as the 'Least Contributor' customer segment
      d. All (Male and Female) customers were not purchasing equally    
##### Insights
The following were inferred from the findings and interpretations from the analyses performed:
1.    Within the 'Premium' segment, youths (between the ages of 26 and 32 
      years) and female customers spent the most on purchases from the company, both in absolute (total) and mean value terms. 
      Also, the difference in education level was significant in this segment.
2.    For the 'Opportunity' customer segments, the difference in annual income was significant, as there were more of recent 
      purchases by customers and many more female customers (76.5% on average) participated in both of the client company’s 
      promotional events of months 1-7, and months 8-13-than their male counterparts (23.5% on average).
3.    In the 'Least Contributor' customer segment, the gap between the annual incomes of this group of customers was not 
      significant, while many more (80.2%) female customers were not purchasing items from the company compared to their male 
      counterparts (19.8%).

#### Recommendations
The prime recommendation for the 'Premium' customer segment was for the company to always stock luxurious and expensive women's items since they are frequent buyers and heavy spenders. 

For the 'Opportunity' customer segment, the top recommendation was that educational level should the taken into consideration when designing marketing campaigns targeted at this group.

For the 'Least Contributor' customer class, the company was advised not to spend resources on retaining them, but rather let them naturally self-upgrade to a higher customer class or self-dropout. 

#### Technology
1. Jupyter Notebook IDE (Coding environment)
2. Python (Programming language)
3. MS Excel (Data aggregation)
4. MS PowerPoint (Presentation to the management team)
5. MS Word (Project report development for other company stakeholders, also for project process and results documentation)
