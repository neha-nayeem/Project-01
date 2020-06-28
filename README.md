# Project-01: Toronto Crime Analysis

## Team
Our team consists of:
- Feng Wang
- Olive Sun
- Jaehong Kwon
- XiongFei (Frank) Shi
- Neha Nayeem

## Background

This project aims to analyze and visualize crime cases in Toronto from 2014-2019. Correlations between crime and various metrics like time and seasons, premises and locations, and economy were looked at using open datasets (see 'Resources' below). 

## Questions and Observations
The following questions were asked of the data:
### 1. What are the most common / least common crimes in Toronto?
 - The MCI dataset lists five different kinds of crimes: assault, auto theft, break and enter, robbery and theft over. However, it does not contain bicycle_theft and homicide data. To get all seven types of crimes, we need to add data from bicycle_theft and homicide files.  In addition, the format of bicycle_theft and homicide data are different to MCI data, for e.g. they are missing some columns like “occurrence month” and the date is in a different format. In order to get the final dataset, we will need to rename the columns of bicycle_theft and homicide to make them consistent with the MCI file.

 - There are two types of dates in the data sets, reported date and occurrence date. The reported dates are sometimes delayed with respect to the occurrence so we will be analyzing data based on occurrence dates between 2014 and 2019 and not the reported date. 

 - From 2014 to 2019, Assault is by far the most common crime with occurrences over 110,000, it accounts for 49% of total crimes. It is more than double the number of incidents for the second most common crime Break and Enter.

 - Homicide is the least common crime over the 6 year period and only accounts for less than 0.5% of the total crime.
 
 - The crime occurrence in Toronto is increasing from 2014 to 2019.

2. What time of the year the frequency of crime is highest? 
    a.	Correlation of crime with different seasons
    b.  Correlation of crime with time of the day

3. Which neighborhoods experience the highest and lowest crime rates in Toronto? 
    a.	How close were police stations to where the crime occurred?
4. In what kinds of properties do the following crimes occur? (house, commercial, apartment, etc)
    a.	Break-and-enter
    b.	Robbery
    c.	Assault
5. Is crime decreasing/increasing over the years?
    a.  Correlation of crime with current economy







