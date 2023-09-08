# 1. United Kingdom Bank Customer Segmentation Dashboard
#UKBankCustomerBaseline #StoryLine #InteractiveDashboard #Bins&Parameters #Annotations 
<img width="1204" alt="Screenshot 2023-08-28 at 1 25 26 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/84c90b4a-7669-483f-adf0-2db43d6b1f79">

## Dashboard

https://public.tableau.com/app/profile/anju.haridas/viz/WeWashUSleepnewstartupinvestmentROMIAnalysis/Sheet4?publish=yes

## Dataset

https://public.tableau.com/app/profile/anju.haridas/viz/UKBankCustomerSegmentation_16933844934390/Story1?publish=yes

## Inference
#### England
- The majority of bank customers, 54%, are from the United Kingdom.
- The UK customer base primarily consists of white-collar workers, constituting 70% of their clientele. This could be attributed to London's status as the economic hub of Europe.
  
<img width="1142" alt="Screenshot 2023-08-28 at 2 32 32 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/e5a6670d-cc3e-489f-b8ea-a691bd49b2f9">

#### Scotland
- A significant majority of our customers are older individuals, with males making up the predominant group at 72%.
- Majority of the customers are more blue collar workers(48%), very few white - collar workers.

<img width="1268" alt="Screenshot 2023-08-28 at 4 03 57 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/f4d1a0ad-1090-4796-8058-da2dbc1f0140">

#### Northern Ireland
- Majority of customers are predominantly Females(74%) and maximum bank balance is below 35k within the age group of 28 - 30.

<img width="1243" alt="Screenshot 2023-08-28 at 4 13 31 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/78edae1d-1da9-4514-98f4-d94898d6290e">

#### Wales
- In contrast to the general baseline, there's a distinct pattern in the distribution of balances. While the baseline shows a decrease, the "whales" category initially experiences an increase before eventually declining.
- The data for Wales indicates a higher-than-average presence of mid-sized balances.
  
<img width="1256" alt="Screenshot 2023-08-28 at 4 05 33 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/ce63a2a0-7a25-4da1-82ff-715b9eaca473">


______________________________________________________________________________________________________________________________________________________________________________________________________________________________________


# 2. WeWashUSleep Startup Expansion
#Groups #GeographicalRoles #CalculatedField #Highlighter #Clustering #KmeansClustering #CrossDatabaseJoin #ThreeDimensionalModeling #TrendLine

### 1st Challenge
- *Average Revenue per city, Average Marketing Spend per city, Average Revenue on marketing investment per city (Revenue / Marketing Spend).*<br />
### 2nd Challenge 
- *Top 10 New locations having the best potential for the company to invest more funds into marketing.*<br />

## Dashboard

https://public.tableau.com/app/profile/anju.haridas/viz/WeWashUSleepnewstartupinvestmentROMIAnalysis/Sheet4?publish=yes

## Dataset

- https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P1-StartupExpansion.xlsx
- https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P1-US-Cities-Population.csv

## Inference from 1st Challenge 
- Region 2 has better returns on marketing spend compared to Region 1.

<img width="869" alt="Screenshot 2023-09-05 at 12 15 34 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/82297e16-03e0-4de6-a5c3-f17ccfe52360">

## Inference from 2nd Challenge 
- Two new cities are situated within the lower-clustered cities, characterized by high marketing expenses but relatively low revenue. Therefore, it is advisable to allocate investments towards the higher-clustered cities, where marketing expenditure is moderate and revenue is consistently above average.
  
<img width="1030" alt="Screenshot 2023-09-05 at 3 04 30 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/40ab8428-3223-4786-a64e-9429359315a2">

## Refined our analysis by cross joining the 2nd Dataset (Population), now inference from 2nd Challenge.
- Red Trendline: With every dollar spent on marketing, the company generates revenue of $0.94. Consequently, in this cluster or group of cities, the company is operating at a loss.

<img width="894" alt="Screenshot 2023-09-06 at 2 36 28 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/de091a30-9874-4d01-a8a5-4386a6028c6f">


- Orange Trendline: With every dollar spent on marketing, the company generates revenue of $7.32. Consequently, in this cluster or group of cities, the company is profitable.

<img width="894" alt="Screenshot 2023-09-06 at 2 36 48 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/57ee357a-46e2-49d8-9a19-9e89f5e4ed5b">

  
- Blue Trendline: With every dollar spent on marketing, the company generates revenue of $3.17. Consequently, in this cluster or group of cities, the company is profitable.

<img width="896" alt="Screenshot 2023-09-06 at 2 37 00 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/981a1adc-3cd6-48a1-8b26-836e4240fa03">

## Conclusion
- Recommend that WeWashUSleep increase its marketing efforts in three new orange cities: California, Illinois, and New Jersey.


______________________________________________________________________________________________________________________________________________________________________________________________________________________________________


# 3. New York Crime/Incidents Statistics
#ImportSpacialDataFromOpenSourcePlatforms #ImportpdfFile #JoinSpacialPdf #CleanData #RemoveDuplicates $CreategeographicalPolygons

## Dashboard

https://public.tableau.com/app/profile/anju.haridas/viz/NewYorkCrimeStatistics_16940852843130/Sheet3?publish=yes

## Dataset

- https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P1-nyc-park-crime-stats-q1-2018.pdf
- https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P1-NYC-Parks-and-Public-Spaces-Spatial-Files.zip

## Inference 

<img width="504" alt="Screenshot 2023-09-07 at 4 34 56 PM" src="https://github.com/Anjuharidas4/Tableau/assets/108412331/09b09af9-af4a-478c-a056-13f03f08fd74">


______________________________________________________________________________________________________________________________________________________________________________________________________________________________________


# 4. Average Annual Salary - Exclusively for County 
#Filters #CalculatedFields #DataCleaning #RemoveDuplicates $TooltipVizuilisation

## Dashboard

https://public.tableau.com/app/profile/anju.haridas/viz/AverageAnnualSalary-NewYorkEmploymentData/AvgAnnualSalaryMap?publish=yes

## Dataset

- https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P1-quarterly-census-of-employment-and-wages-annual-data-beginning-2000.csv


