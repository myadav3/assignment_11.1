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
- Also, the price range of all the vehicles is approximately bet ~ $8k-$39k with some outlier to be eliminated
- The data has vehicles from all 51 states (50 states + Washington DC) in the US and 404 distinct regions
- There are a total of 42 unique manufacturers in the data
- There are a total of 29629 unique car models in the data
- The condition of the vehicle is classified in 6 unique categories 
    ('good', 'excellent', 'fair', 'like new', 'new', 'salvage')
- There are a total of 8 unique cylinder types listed in the data 
    ('8 cylinders', '6 cylinders', '4 cylinders', '5 cylinders', 'other', '3 cylinders', '10 cylinders', '12 cylinders')
- There are a total of 5 unique fuel attributes listed in the data 
    ('gas', 'other', 'diesel', 'hybrid', 'electric')
- There are a total of 5 unique title statuses listed in the data 
    ('clean', 'rebuilt', 'lien', 'salvage', 'missing', 'parts only')
- There are a total of 3 unique types of transmission listed in the data 
    ('other', 'automatic', 'manual')
- There are a total of 265838 unique VINs (Vehicle Identification Numbers) listed in the data
- There are a total of 3 unique dive-types are listed in the data 
    ('rwd', '4wd', 'fwd')
- There are a total of 4 unique vehicle sizes listed in the data 
    ('full-size', 'mid-size', 'compact', 'sub-compact')
- There are a total of 13 unique vehicle types listed in the data 
    ('pickup', 'truck', 'other', 'coupe', 'SUV', 'hatchback', 'mini-van','sedan', 'offroad', 'bus', 'van', 'convertible', 'wagon')
- There are a total of 12 unique paint colors listed in the data 
    ('white', 'blue', 'red', 'black', 'silver', 'grey', 'brown', 'yellow', 'orange', 'green', 'custom', 'purple')

- Majority of the columns except (id, region, price, and state) contained NULL values (NaN in data science terms)
- The data required significant cleansing as well as inferring the NULL values through Imputation
