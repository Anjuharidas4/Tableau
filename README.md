# 1. United Kingdom Bank Customer Segmentation Dashboard
#UKBankCustomerBaseline #StoryLine #InteractiveDashboard #Bins&Parameters #Annotations 
<img width="1204" alt="Screenshot 2023-08-28 at 1 25 26 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/84c90b4a-7669-483f-adf0-2db43d6b1f79">

## Dashboard

https://public.tableau.com/app/profile/anju.haridas/viz/UKBankCustomerSegmentation_16933844934390/Story1?publish=yes

## Dataset

[UK-Bank-Customers.csv](https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P1-UK-Bank-Customers.csv)

## Inference
#### England
- 54% of Bank customers are from the United Kingdom which is the majority.
- White-collar workers represent 70% of Customers in the UK perhaps because London is the economic center of Europe.
  
<img width="1142" alt="Screenshot 2023-08-28 at 2 32 32 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/e5a6670d-cc3e-489f-b8ea-a691bd49b2f9">

#### Scotland
- The majority of customers are much older customers and predominantly males(72%).
- Majority of the customers are more blue collar workers(48%), very few white - collar workers.

<img width="1268" alt="Screenshot 2023-08-28 at 4 03 57 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/f4d1a0ad-1090-4796-8058-da2dbc1f0140">

#### Northern Ireland
- Majority of customers are predominantly Females(74%) and maximum bank balance is below 35k within the age group of 28 - 30.

<img width="1243" alt="Screenshot 2023-08-28 at 4 13 31 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/78edae1d-1da9-4514-98f4-d94898d6290e">

#### Wales
- Very different from the overall baseline in the Distribution of Balances, it reduces in the baseline but in the whales increases first then reduces.
- Data for Wales shows above average representation of mid-sized balances.
  
<img width="1256" alt="Screenshot 2023-08-28 at 4 05 33 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/ce63a2a0-7a25-4da1-82ff-715b9eaca473">

______________________________________________________________________________________________________________________________________________________________________________________________________________________________________

# 2. WeWashUSleep Startup Expansion
#Groups #GeographicalRoles #CalculatedField #Highlighter #Clustering #KmeansClustering #CrossDatabaseJoin #ThreeDimensionalModeling #TrendLine

### 1st Challenge
- *Average Revenue per city, Average Marketing Spend per city, Average Revenue on marketing investment per city (Revenue / Marketing Spend).*<br />
### 2nd Challenge 
- *Top 10 New locations having the best potential for the company to invest more funds into marketing.*<br />

## Dashboard

https://public.tableau.com/app/profile/anju.haridas/viz/UKBankCustomerSegmentation_16933844934390/Story1?publish=yes

## Dataset

- https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P1-StartupExpansion.xlsx
- https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P1-US-Cities-Population.csv

## Inference from 1st Challenge 
- Region 2 has better returns on marketing spend compared to Region 1.

<img width="869" alt="Screenshot 2023-09-05 at 12 15 34 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/82297e16-03e0-4de6-a5c3-f17ccfe52360">

## Inference from 2nd Challenge 
- Two New Cities lie in the lower clustered cities where marketing spend is high and revenue is low hence investing in the higher clustered cities is ideal where marketing spend is average and revenue is also equally above average.
  
<img width="1030" alt="Screenshot 2023-09-05 at 3 04 30 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/40ab8428-3223-4786-a64e-9429359315a2">

## Refined our analysis by cross joining the 2nd Dataset (Population) now inference from 2nd Challenge.
- Red Trendline : For every dollar of marketing spend revenue is $0.94. Hence the company is losing money in this cluster/group of cities.

<img width="894" alt="Screenshot 2023-09-06 at 2 36 28 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/de091a30-9874-4d01-a8a5-4386a6028c6f">


- Orange Trendline : For every dollar of marketing spend revenue is $7.32. Hence the company is making money in this cluster/group of cities.

<img width="894" alt="Screenshot 2023-09-06 at 2 36 48 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/57ee357a-46e2-49d8-9a19-9e89f5e4ed5b">

  
- Blue Trendline : For every dollar of marketing spend revenue is $3.17. Hence the company is making money in this cluster/group of cities.

<img width="896" alt="Screenshot 2023-09-06 at 2 37 00 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/981a1adc-3cd6-48a1-8b26-836e4240fa03">

## Conclusion
- Recommend that WeWashUSleep increase its marketing efforts in three new orange cities: California, Illinois, and New Jersey.





