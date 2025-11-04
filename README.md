# **AN ANALYSIS ON HISTORICAL AVIATION ACCIDENTS(1919-2023)**
<img src="Images\Aviation_Accidents_1.jpeg" alt="Airplane_Crash" width="750">


## **Overview**
This project aims to effectively identify the risks associated with different aircraft by analysing historical aviation accident data and provide insights into the most viable aircraft options based on frequency of accidnets occurrence. Identifying the patterns, trends, and risk factors that influence such accidents, facilitates the determination of the lowest risk venture aircraft for purchase by the company and how viable the operation of the aircrafts would be for commercial and private enterprises. The dataset covers approximately 24,000 aviation accidents worldwide that occurred between 1919 and 2023. Since the company is exploring entry into the aviation sector, it is crucial to understand the historical safety records of different aircraft types, operators, and regions in order to make well-informed decisions.
 

## **Business Understanding**
The company's goal is not just to diversify its portfolio but also to efficiently identify the risk associated with each aircraft type in order to make well-informed investment decisions for their business endeavour. This lack of clarity on the potential risks involved with an aircraft venture calls for a need to have data-driven insights that would positively lead to optimized decision-making in the critical areas.

To achieve this, the following business questions have been developed:
* Which of the aircraft types contribute the least to aircraft accidents?
* Which locations are performing well, which ones are subject to the most aircraft accidents and what could be the cause?
* Which are the most profitable aircrafts types regardless of the accident frequency and based on accident frequency?
* How are the accidents trending over time e.g. (monthly, quarterly, yearly) and do they have any influx at certain time periods?

## **Data Understanding and Analysis**

### Source of data
The dataset used for this analysis is the [Aviation Accidents Dataset](https://www.kaggle.com/datasets/drealbash/aviation-accident-from-1919-2023/data) that provides a comprehensive record of aircraft accidents that occurred between the years 1919 and 2023. This dataset captures crucial details of each accident, including the date of the incident, registration number of the aircraft involved, the country where the accident occurred, the specific location, the category of the accident, and the number of fatalities. 

### Description of data
The dataset involves the following 9 columns:
* **Date of Accident**: This column contains the dates of each aviation accident, ranging from 1919 to 2023.

* **Type**: This column indicates the model of the aircraft that was involved in the accident. 

* **Registration**: This column contains the unique identification code that is usually assigned to each aircraft. It helps identify and track specific aircraft involved in incidents. 

* **Operator**: This column shows the airline that commands that specific aircraft that was involved in the accident.

* **Fatalities**: This column records the count of fatalities associated with each aviation accident. It provides information on the number of fatalities both ground fatality and aircraft fatality. 

* **Location**: This column shows the specific region within the country where each accident occurred. 

* **Country**: This column indicates the country where each aviation accident took place. This column has no missing values.

* **Cat**: This is short for Category whereby each accident is classified into different categories based on factors such as the cause, nature, or severity of the incident. The categories in the daaset are: 
    * A = Accident

    * I = Incident

    * H = Hijacking

    * C = Criminal occurrence (sabotage, shoot down) 
    * O = Other occurrence (ground fire, sabotage)

    * U = type of occurrence unknown

        * 1 = hull-loss

        * 2 = repairable damage

        * E.g. the A1 category means an Accident resulting in a total loss of the plane.

* **Year**: This is a column that includes the extracted year-data from the date column. It has no missing values but has some records labelled as 'Unknown'.