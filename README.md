# NYC-Taxi-Analysis

This study explores the use of crowdsourced traffic data for effective evacuation planning in large cities, emphasizing the potential of such applications in enhancing public safety. The project specifically focuses on the Latest Taxi and Limousine Commission (TLC) trip record data for September 2023 in New York City. The objective is to analyze the impact of Taxicab and livery Passenger Enhancement Programs (TPEP) providers on Cost per mile and tip amount. The project employs statistical methodologies and conducts 100 simulations, revealing consistent failure to reject the null hypothesis regarding average fares among TPEP providers. The results also indicate an insignificant difference in tip amounts paid to different providers. The project focuses on examining the impact of Taxicab and livery Passenger Enhancement Programs (TPEP) providers on cost per mile and tips charged in New York City, utilizing historical taxi trip data obtained from the NYC Taxi and Limousine Commission (TLC). This project also aims to identify economical and better service providers through statistical modeling, with potential applications in improving taxi dispatching and overall service quality. The dataset used is the TLC Trip data records for September 2023, providing up-to-date information compared to previous analyses that often focused on data collected before 2018.

### Data Anlysis conducted over 4 key attributes for Hypotheses Analyses: 

![image](https://github.com/kalp1202/NYC-Taxi-Analysis/assets/76723038/8669a193-523f-43bd-beb2-17a19b163f5d)

### Data Cleaning:

The data was then cleaned. Following things were done for the process of cleaning:
- Taking only positive values and Null values were removed in Trip distance, Tip Amount, Total Amount and Fare Amount.
- Since the number of data points are very high, as per Central Limit Theorem, we assume the data to be normally distributed.
- Taking ≈ 98%(2.5 SDs) of the data into consideration for dealing with outliers

### Visualizations of before and after Data Cleaning:
![image](https://github.com/kalp1202/NYC-Taxi-Analysis/assets/76723038/d599b9f9-5acb-4d37-b758-a8dc316a3af9)

![image](https://github.com/kalp1202/NYC-Taxi-Analysis/assets/76723038/0e46363a-eabf-446c-bea6-2a81122f76dd)

![image](https://github.com/kalp1202/NYC-Taxi-Analysis/assets/76723038/4a86cc07-3cbc-4bed-a23c-bb9dbd464271)



### This project formulates two hypotheses using the two-sample t-test for analysis:

#### 1. Cost per Mile Differences Between Taxi Providers:
Null Hypothesis (H0): There is no significant difference in the average cost per mile between taxi trips provided by Vendor1 and Vendor2 (μ1=μ2).
Alternative Hypothesis (H1): Average cost per mile amounts vary between taxi trips provided by Vendor1 and Vendor2 (μ1≠μ2).

![image](https://github.com/kalp1202/NYC-Taxi-Analysis/assets/76723038/8d2bf709-a1c9-429a-ac94-0678842bbb70)


#### 2.Tip Amount Differences Between Taxi Providers:
Null Hypothesis (H0): There is no significant difference in the average tip amounts between taxi trips provided by Vendor1 and Vendor2 (μ1=μ2).
Alternative Hypothesis (H1): Average tip amounts vary between taxi trips provided by Vendor1 and Vendor2 (μ1≠μ2).

![image](https://github.com/kalp1202/NYC-Taxi-Analysis/assets/76723038/ee523163-32e7-4d4c-baab-bcaa1dab0b6e)


In these hypotheses, μ1 and μ2 represent the population means of the cost per mile and tip amount for Vendor1 and Vendor2, respectively. The paper emphasizes the use of the latest data to address these hypotheses, contributing insights into the economic and service-related dynamics of taxi providers in New York City.



### Conclusion:
From both the hypotheses:
- There is no significant difference in the average cost per mile amounts between taxi trips provided by Vendor 1 and Vendor 2.
- There is no significant difference in the average tip amounts between taxi trips provided by Vendor 1 and Vendor 2.
- These results suggest there is no complex relationship between provider-to-provider fare discrepancies as well as tip awarded. 




