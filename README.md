# Amazon_Vine_Analysis
## Overview of Project
### Purpose
The purpose of this project is to analyze the Amazon Vine program, and determine whether is a bias towards favorable views. This analysis utilizes PySpark to perform the ETL process to extract the dataset, transform data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics. The focus of this analysis is on U.S reviews for video games.

## Results and Analysis
### Results
 1. Vine Reviews
 
![image](https://user-images.githubusercontent.com/109991916/204624618-80564d4c-d45c-46b0-b466-4cea4abf2314.png)

The total in Vine reviews is 94.


2. Non-Vine Reviews

![image](https://user-images.githubusercontent.com/109991916/204624932-76309b04-40f7-48c2-84b4-dbb2f23ad585.png)

The total in non-Vine reviews is 40,471.
 
3. 5-Star Vine Reviews

![image](https://user-images.githubusercontent.com/109991916/204625381-cb7d88f6-fda3-4f62-a3fb-04e77e860f1a.png)

The total in 5-star Vine reviews is 48.

4. 5-Star Non-Vine Reviews

![image](https://user-images.githubusercontent.com/109991916/204626119-a0f25c55-6244-4401-8884-20a2ce004b08.png)

The total in 5-star non-Vine reviews is 15,663.

5. Percentage of 5-Star Vine Reviews

![image](https://user-images.githubusercontent.com/109991916/204627087-a57573f3-a522-46d6-bbc7-75ed058d4678.png)

The percentage of 5-star Vine reviews is 51.1%.

6. Percentage of 5-Star Non-Vine Reviews

![image](https://user-images.githubusercontent.com/109991916/204627639-ba2f782c-97b5-40d6-88ab-02a6459f0cbe.png)

The percentage of 5-star non-Vine reviews is 38.7%.

## Summary
Based on the data, 51% of reviews in the Vine program were 5-star reviews, whereas non-Vine reviews resulted in only 39%. There is a positivity bias for reviews in the Vine program.

In addition, the overall statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews could be reviewed for future analysis.
