# Stock-Analysis
A stock analysis for Steve

## Overview of Project: Explain the purpose of this analysis.
The purpose of this analysis is to compare stock performance between a select number of tickers over years 2017 and 2018.
We decided to refactor the stock market vba script to test if the results would produce a faster time than the original non-refactored analysis.

## Results:
One of the biggest differences between the original and refactored code was the creation of the new arrays.

![image](https://user-images.githubusercontent.com/98003050/158029211-6272b194-bc29-4dc2-8271-1a57c7e66b57.png)


The original code used a nested loop when looping through the tickers

![image](https://user-images.githubusercontent.com/98003050/158029454-95f2a228-f1b6-4e3e-9204-e697ac6528b2.png)

where as the refactored code took a slightly different approach

![image](https://user-images.githubusercontent.com/98003050/158029505-e4fefd4a-4c2b-4abc-8249-85355282ff76.png)


These are the results of the stock analysis for the year 2017

![image](https://user-images.githubusercontent.com/98003050/158029016-dd9f3334-c5bd-45cc-94e4-d51fc463a8d1.png)


These are the results of the stock analysis for the year 2018

![image](https://user-images.githubusercontent.com/98003050/158028987-939fc8d4-322e-4aeb-94fd-774ac94837e9.png)


The results for the original code ran for both years 2017 and 2018

![image](https://user-images.githubusercontent.com/98003050/158028853-ed634d52-5948-42ba-8798-9c4e87f47036.png)
![image](https://user-images.githubusercontent.com/98003050/158028873-ff89bb2b-7e50-4070-b058-ae91f61fd860.png)


The result for the refactored code ran for year 2017 and 2018 analysis

![VBA_Challenge_2017](https://user-images.githubusercontent.com/98003050/158028776-bd7f27fb-06c3-4ca9-b37f-ca022ad59219.PNG)  ![VBA_Challenge_2018](https://user-images.githubusercontent.com/98003050/158028779-9a669290-8fc3-4211-bc67-405e39f9c3cd.PNG)


## Summary: 
Some advantages of refactoring code include
- having faster run times
- the code can be reused

Some disadvantages include
- code becomes a bit more complex and take longer to write compared to non-refactored code
- more bugs may be introduced

## How do these pros and cons apply to refactoring the original VBA script?
Refactored code can be reused to speed through other loops for other projects, allowing for faster calculations that can help save a lot of time when dealing with larger datasets.
However, with refactored code, it is easier to get lost as you are trying to navigate through and find bugs and discrrepancies
