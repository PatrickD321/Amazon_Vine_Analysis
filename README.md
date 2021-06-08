# Amazon Vine Analysis

## Overview of the analysis

The objective of this challenge is demonstrate the ablity intereact in big data file that is not stored on your personal device, that is data stored on a large server such as AWS.
Since the data is very large, it can be handled by spliting up work between team member by using MapReduce. 
- Mapping - processing input and producing small chunks of data across each computer
- Reducing, which is when you come back together to combine the results. 
This is an efficent way analysing big data using Hadoop which is an ecosystem for handling big data. With the growing intrest in big data and cloud computing a more robust and flexible form of data processing is required and Apache Spark a unified analytical engine similar to that of Python is avaiable. We will use this in this challenge to get data from big data storage facilities such as Netflix or Amazon to both move process and analyzed very large files.  

## Results

- How many Vine reviews and non-Vine reviews were there?   
  The Vine reviews are 43.   
  Non-Vines reviews are 140200.


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?   
  The five (5) star rating for vine reviews are eight (8) in total.  
  Non-Vine reviews produced 73039 five (5) star ratings.

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  The percentage Vine reviews were 5 stars is 0.002%.  
  The percentage of Non-Vine reviews were 5 5 stars is 2.193%.  

## Summary 

  Vine Reviews is an Amazon program where Amazons shoppers are invited to post oppinions about new and pre-release products to help other customers to make informed decision for buying the said produce. This similar to giving your own unbaised perception for any given item. The program is expected to be without any favor towards a given item and this is reflected in the percentage values that were detemined from Vine_table. "Y" under the vine column from the table signified user that were paid, and "N" shows those who were not. The percentage is approximaly zero (0 ~ 0.002%) for paid reviews 5 star rating, while non-paying reviews is 2.193%, this indicates the positivity of the promgram since the paid reviews are almost nonexistence.  
  An addiitional analysis that could provide to support that the nature of the program is unbaised, is to compare the amount of 5 star rating to all the other ratings combined. This should also be check against the paid and non-paid reviews since honest opinions are always needed to keep the integrity of the program.





