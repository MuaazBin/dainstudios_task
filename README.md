# dainstudios_task

Please generate a single(!) insight from the given data set and be prepared to communicate the insight and the methods that led you to it, including any code you have written.
 
A single insight is enough and there is no need to look for the “best” insight. We will use this task as a starting point for more discussion.
 
The data set is the European Social Survey (ESS) which can be found at http://www.europeansocialsurvey.org/downloadwizard/ 

You will need to register with your email to get access to data set. 

Select the variables you need for your analysis and the interface will give you a zip file with two files: 
  
1) a code notebook that describes the variables and 
2) a CSV data file. 

# Approach
Import the dataset and perform basic data wrangling before moving towards exploratory analytics. During exploratory analytics find a single insight of interest and then if possible confirm it using statistical techniques or other datasets.

# Dataset
Variables Selected:
1. Gender, age and household composition (72/72)
2. ESS Round = 7
3. Country = Finland

The data used in this analysis is also available in the data folder of the repository.

# Code
Please check the jupyter [notebook](https://github.com/MuaazBin/dainstudios_task/blob/master/notebook/Insight%2Bfrom%2BESS.ipynb)

# Insight

+ 1. The initial finding is whatever mechanism European social surveyors followed had a reach to both genders almost equally 
(1. Male and 2. Female) as seen from the first bar chart.

Thus first single basic insight could be that the same survey approach could be successfully used for selling unisex products or services but might not be effective for products or services highly tailored for one gender. But I could be wrong as well. The respondent of Gender A could be interested for a product relevant to Gender B.

+ 2. The other finding is that the finnish population compromises of more people in the age bracket of 45-75
rather than 15-45. Since the data for 0-15 age is missing but still one can safely assume middle aged population seems higher.

The insight is that the Finland has a negative or slow population growth. It needs more youngsters to replace the middle aged people to run its economy and perhaps is looking into solving this problem by easier immigration policies.

# Future Work

1. Confirming findings and insight using atleast one other data source.
2. Do trend analysis by incorporating other ESS rounds' (Years') data to confirm the finindg of Round 7.
3. Show your results to a third party for unbias critical evaluation of your analysis.
4. Research on the internet to see the findings make sense.

# Note

Please note that from the email it seems that I was suppose to do a very basic analysis and present only one insight.
The work I did here took about 2 hours and is quite basic. If an in depth analysis is needed with interesting insights using bigger datasets with more features, kindly suggest.
