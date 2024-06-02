# Movie recommendations Analysis For Microsoft's New Movie Studio  
     
This project delves into the financial landscape of movie production, aiming to equip a new movie studio (or replace with the specific studio/purpose) with data-driven insights for strategic decision-making. By leveraging data on production budgets and domestic box office gross, we uncover valuable trends and relationships that can inform movie selection, budget allocation, and overall studio strategy.  

## Project Goals  

Identify key patterns and correlations between production budgets and domestic box office gross.  
Generate actionable recommendations to optimize movie selection and production strategies.  
Enhance the understanding of financial considerations for a successful movie studio.   

## Overview
Microsoft is venturing into movie production and seeks insights into successful film types. This analysis utilizes exploratory data analysis techniques to uncover patterns that can inform their content creation strategy.

## Business Understanding

> ### Stakeholder and Key Business Questions
>> *  #### Stakeholder: 
>>> Microsoft (Head of the new movie studio)   
>> * #### Key Business Questions: 
>>>  Microsoft has decided to venture into the film industry by creating a new movie studio.  However, they lack prior experience in movie production. This project aims to leverage data analysis to provide valuable insights that can inform their content creation strategy. The key question we will address is: 
>>> 1. Year-wise Performance for Domestic Gross and Foreign gross. 
>>> 2. Is there a strong correlation between a movie's budget and its box office performance? Understanding this relationship can inform budget allocation strategies for different movie types.
>>> 3. Can you identify any patterns between movie genres, budgets, and profitability (box office gross minus budget)? Profitability analysis goes beyond just box office and helps assess the financial viability of different movie concepts.
>>> 4. What is the top 10 movies from gross earnings to check if the movies trending in domestic gross are the same in worldwide gross.  
>>> 5. What is the distribution of release years for all the movies in the dataset?

## Data Analysis and Visualizations  

We leverage the power of Python's pandas library for data manipulation and cleaning, and matplotlib for creating informative visualizations. Our analysis delves into several key areas to provide insights for strategic movie studio decision-making:

### 1. Year-wise Performance:

#### Visualization:  

Line plot
##### Insights:

* This visualization helps us understand trends in total box office performance (domestic and foreign) over time.
* We can identify years with particularly strong or weak overall performance, potentially revealing seasonal patterns or external factors influencing movie success.  



### 2. Budget vs. Box Office Performance:

#### Visualization:  

Scatter Plot
##### Insights:

This scatter plot allows us to explore the relationship between a movie's production budget and its domestic box office gross.
While a strong correlation might not always exist, we can identify potential trends to inform budget allocation strategies for different movie types. It's important to consider outliers and use statistical tests for a more robust understanding.  


### 3.Profitability Analysis by Genre and Budget:

While the provided code uses a pivot table for visualization, here's an alternative approach using a violin plot:



### 4. Top Movies by Worldwide Gross:

#### Visualization:
Bar plot 

##### Insights:

This visualization helps identify the top 10 movies based on their combined domestic and foreign box office gross (worldwide gross).
By comparing this list with the top 10 domestic gross earners, we can see if there's overlap or if different movies perform better in international markets.  


### 5. Distribution of Release Years:

#### Visualization:  
Hist plot

##### Insights:

This histogram reveals trends in movie production volume over time.  
We can identify periods with higher or lower movie release activity, which might be relevant for scheduling release dates and marketing efforts.  

##### By creating these visualizations and conducting further analysis, we can gain valuable insights to inform studio decisions around:

* Genre selection and budget allocation strategies  
* Release timing and marketing efforts  
* Identification of potentially profitable movie concepts    

#### Recommendation to Microsoft's new studio 

##### Genre Analysis:  
Microsoft focus on specific genres that align with their financial goals. For instance, prioritize comedies if they offer a high potential return on investment (ROI) despite lower budgets.  

##### Budget Targeting:  
in terms of production budget and domestic gross (e.g., movies with budgets between $50M and $100M tend to have the highest average gross), I suggest that Microsoft target this budget range to optimize potential profits.

##### Risk Tolerance: 
I recommend exploring genres with higher budgets and potentially higher returns (though also higher risk).

### Conclusion
In this exploratory data analysis project, we investigated the landscape of movie production budgets and domestic gross to inform the strategic direction of Microsoft's new movie studio. By analyzing data from various sources, we aimed to identify trends and relationships that could provide actionable insights.

Our key findings, visualized through various charts and graphs, revealed several potential avenues for Microsoft's movie studio to consider. These findings suggest that Microsoft could prioritize specific genres, target certain budget ranges, and potentially optimize release strategies to maximize their chances of box office success.

We recommend that Microsoft carefully considers these insights alongside their long-term goals and risk tolerance. Focusing on genres with high potential return on investment (ROI) or targeting a "sweet spot" in production budgets could be strategically beneficial. Additionally, exploring trends in other areas like release dates could provide further avenues for optimization.

It's important to acknowledge that data limitations might exist .  Moving forward, Microsoft could implement strategies to gather more comprehensive data to refine future analyses.

Overall, this project has provided valuable insights into the financial aspects of movie production and their relationship to box office performance. By leveraging these findings and conducting further research, Microsoft's new movie studio can make informed decisions that increase their chances of achieving success in the competitive film industry.  





