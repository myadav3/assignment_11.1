# Used Car sales - Feature Importance and prediction

- This application makes use of CRISP-DM framework

### CRISP-DM Framework

- To frame the task, throughout our practical applications we will refer to a standard process in industry for data projects called CRISP-DM.  
- This process provides a framework for working through a data problem.  
- Our first step in this application will be to read through a brief overview of CRISP-DM <a href="https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining#:~:text=CRISPDM%20breaks%20the%20process%20of%20data%20mining%20into,Data%20Preparation%204%20Modeling%205%20Evaluation%206%20Deployment">here</a>

### Business Understanding

-  The provided dataset contains information on 426K cars to ensure speed of processing.. 
- Your goal is to understand what factors make a car more or less expensive. 
- As a result of your analysis, you should provide clear recommendations to your client -- a used car dealership -- as to what consumers value in a used car.

### Data Understanding

- The data spans 1900s to 2022
- Also, the price range of all the vehicles is approximately  ~ $10k-$50k. There are some outlier like rare cars that were sold for over a million dollars
- The data has vehicles from all 51 states. California has the most numbers of cars sold and North Dakota being the least.
- There are a total of 63 unique manufacturers in the data- ford being the most and morgan sold least cars
- There are a total of 29629 unique car models in the data
- The condition of the vehicle is classified in 6 unique categories 
    ('good', 'excellent', 'like new', 'fair', 'new', 'salvage')
- There are a total of 8 unique cylinder types listed in the data 
    ('8 cylinders', '6 cylinders', '4 cylinders', '5 cylinders', 'other', '3 cylinders', '10 cylinders', '12 cylinders')
- There are a total of 5 unique fuel attributes listed in the data 
    ('gas', 'other', 'diesel', 'hybrid', 'electric'). Null vaules were hardcoded to Unknowns to ensure they don't fall out in analysis
- Majority of the columns except (id, region, price, and state) contained NULL values 
- The data required significant cleansing as well as inferring the NULL values through Imputation

#Findings:
- Simple visualization analysis suggests that the mid size diesel fuel pick up trucks are the most expensive vehicles. However gas powered mid size pick 4 wheel drive vehicles sell more in numbers.
- Please refer to visualization file for visual analysis.
- Please refer to modeling file for visual analysis.
