# Travel Insurance Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building and Evaluation](#model-building-and-evaluation)
- [Results/Findings](#resultsfindings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

### Project Overview

This project aims to provide insights into the take up rate of travel insurance by analyzing AirAsia's booking data including purchase of ancillaries. The objective is to translate these insights into actionable recommendations that will boost the take up rate of travel insurance.

### Data Sources

Flight booking data: The dataset used for this analysis is "AncillaryScoring_insurance.csv". It contains the flight route information as well as the purcahse of ancillaries such as meal and seat.

### Tools

- Microsoft excel
  - Power pivot
- Tableu

### Data Cleaning/Parsing

In preparing the data, following tasks are performed:
1. Identifying variable type (categorical/ continuous)
2. Checking missing data
3. Categorization of variable
4. Converting string data to number
5. Converting airport location to latitude and longitude

### Exploratory Data Analysis

EDA involves exploring the booking data to solve following questions:
1. What affects the purchase of travel insurance?
2. Which flight route is taken by most customer and has highest travel insurance take up rate?
3. Which group of passengers tends to purchase travel insurace?

### Data Analysis

![map](https://github.com/87Iodo/VI_CapstoneProject_TravelInsuranceAnalysis/assets/143507039/229a28e7-6121-4a77-a4c7-dad015dd6d3c)

### Results/Findings

The analysis results are summarized as follows:
- Flight durtion, length of stay, number of baggage, solo or group travel, planned or unplanned trip could affect the take up rate of travel insurance.
- The flight route with high number of bookings as well as high take up rate of travel insurance is Penang-Taipei route.
- Tech savvy passengers on leisure travel with family for duration less than 1 week, and have more baggages than average passengers, are more likely to take up travel insurance.

### Recommendations

Based on the analysis, the following actions are recommended:

- Improve mobile platform in terms of ease of booking as well as highlighting the benefits of travel insurance when a family booking for duration less than 1 week with more baggae is detected.
- Market a cheaper insurance package as a bundle with other ancillaries.
- Prioritize marketing on flight to trourist spots.

### Limitations

The analysis based on just one dataset can have limited insights. More information such as travelling cost and type of trvael insurance purchased would be useful to gain more insights.

### References
- [kaggle](https://www.kaggle.com/datasets/mundher/airasia passengers)
