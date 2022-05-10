# Project 1: SAT & ACT Analysis Overview

## Contents:
-Problem Statement
-Datasets to be Used
-Executive Summary
-Data Dictionary
-Conclusions and recommendations
-Possible hypotheses for future study

## Problem Statement
ACT and SAT are two exams which are accepted by various colleges across USA for acceptance into various degree programmes. Officially speaking, there is no difference between difficulty levels of ACT and SAT,so ideally speaking the participation rates of the two should be comparable across staes and years. We would like to see whether this is true or not based on the data available. What are the broad trends in the SAT and ACT participation rates across the various states and years?Which majors have highest and least participation in SAT?  

## Datasets to be Used

1. act_2017.csv
2. act_2018.csv
3. act_2019.csv
4. act_2019_ca.csv
5. sat_2017.csv
6. sat_2018.csv
7. sat_2019.csv
8. sat_2019_ca.csv
9. sat_2019_by_intended_college_major.csv

## Executive Summary
In this analysis above nine datasets have been used. They were imported and cleaned for snake case column names and making numeric values where they are expected in different datasets.

    A basic analysis was done on all of the datsets imported which includes descriptive statistics, top 10 and bottom 10 highest participation rates states across all years, when possible highest and lowest scoring states have been also determined and mentioned.
    
Some of the findings are as follows:

1.Minnesotta consistently has highest composite score for years 2017,
  2018 and 2019.
2. Alaska needs to increase its participation rate,probably the   occupation opportunities do not require a college degree. this needs to be improved.
3. In general higher SAT participation rates are associated with lower ACT participation rate for a specific state, although this is not a hard rule.
e.g., Florida, Hawaii, North Carolina and South Carolina have ACT and SAT participation rates both over 50% for year 2019
4. SAT test is more popular in California
5. Average ACT participation is consistently higher than SAT participation.
6. SAT participation has gone up each year while ACT participation has gone down.

## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|ACT/SAT|the US state under consideration| 
|**year**|*int*|ACT/SAT|can be 2017,2018,2019|  
|**participation**|*int*|SAT/ACT|percentage of high school students (freshman through senior) in the state that took the SAT/ACT in year 2017/2018 or 2019| 
|**reading_and_writing**|*int*|SAT|scaled score between 200-800 (inclusive) measuring verbal reasoning, averaged over all test takers in state in year 2017/2018 or 2019| 
|**math**|*int*|SAT|scaled score between 200-800 (inclusive) measuring mathematical reasoning, averaged over all test takers in a state in year 2017/2018 or 2019| 
|**total**|*int*|SAT|sum of verbal and reading score, averaged over all test takers in a state in 2017/2018 or 2019| 
|**english**|*float*|ACT|scaled score between 1-36 (inclusive) measuring command of grammar, averaged over all test takers in a state in 2017/2018 or 2019|
|**math**|*float*|ACT|scaled score between 1-36 (inclusive) measuring mathematical reasoning, averaged over all test takers in a state in 2017/2018 or 2019|
|**reading**|*float*|ACT|scaled score between 1-36 (inclusive) measuring reading comprehension, averaged over all test takers in a state in 2017/2018 or 2019|
|**science**|*float*|ACT|scaled score between 1-36 (inclusive) measuring scientific reasoning, averaged over all test takers in a state in 2017/2018 or 2019|
|**composite**|*float*|ACT|mean of English, Math, Reading, and Science scores, averaged over all test takers in state in 2017/2018 or 2019|

## Conclusion and Recommendations
SAT or ACT? What really matters is students participation increasing in 
either or both the exams so that college education increases. 

However there are certain factors which might tilt the balance in favour
of one on the other such as,

1. It is commonly accepted that SAT is comparatively math-heavier than 
ACT. So different people may have biases towards choosing one of the two.

2. Different states have different norms about the acceptability of the 
two scores. 

There are 11 states that require the ACT:
Alabama,Hawaii,Kentucky,Mississippi,Montana,Nebraska,Nevada,
North Carolina,Utah,Wisconsin,Wyoming

And there are 10 states/regions that require the SAT:
Colorado,Connecticut,Delaware,District of Columbia,Illinois,
Maine,Michigan,New Hampshire,Rhode Island,West Virginia

In addition, Idaho, Ohio, Oklahoma, and Tennessee require a test as part
of the graduation process, but these states allow to choose the SAT 
or the ACT.

3. Based on prevalent occupatonal opportunities, students may or 
may not want to go to college which impacts the participation rates of
bot ACT and SAT.

4. Costs of the two exams and number of chances available for each may 
tilt the participation rate of one over the other.

5. Educational achievement levels: such as institutions-teacher to 
student ratios across regions

6. Cultural Factors: race, ethnicity. Biases are also formed in students' 
minds due to their backgrounds.

7. Socioeconomic status of the students


The data presented here can only help us in analysing the trends. 

To really understand the factors behind these variations we would need 
to use more data and after understanding the causal factors, making 
changes on a broader level and recommending particular test suited to 
a student based on his aptitude by school and government authorities.

**General recommendations would be to provide SAT and ACT practice material
free of cost, subsidies in undertaking these exams to poor students,
increasing the number of chances among others.**

## Possible hypotheses to work upon for future study:

***H1: Lower participation rates for either SAT and ACT tests are associated with higher score in the respective test.***

***H2: Sciences and allied fields such as Engineering, medicine among others have a higher SAT participation rate***

***H3: States with more blue collared jobs are associated with greater SAT participation*** **

## References:

1. https://www.princetonreview.com/college/sat-act
2. https://www.usnews.com/education/best-colleges/articles/act-vs-sat-how-to-decide-which-test-to-take
3. https://blog.prepscholar.com/act-vs-sat