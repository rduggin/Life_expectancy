# Life_expectancy
FACTORS INFLUENCING LIFE EXPECTANCY
BY GROUP 11 REVATHI DUGGINENI, SAHITHI BHAVANA VALLABHANENI
<br>

INTRODUCTION:
Life Expectancy:
Humanity has seen so many paradigm shifting changes in the previous century. There are so many
factors that influence the quality of human life and with the advent of modern technology,
advancements in modern medicine, availability of intricate medical practices has made human life
even better. But there is still a void which is evident in the field of life expectancy, especially in
underdeveloped and developing countries. The average length of life projected for an organism is
determined by its current age, birth year and other variables like gender can be defined as life
expectancy. This project focusses on bridging the gap between the knowns and unknowns which
effect the life expectancy of people. We adapted a dataset provided by the World Health
Organization to see what all the factors that are causing life expectancy to oscillate between
different nations. We tried to focus more on attributes like Geriatric age—How age is affecting the
life expectancy, Population density— how densely populated places are showing the trends of life
expectancy, Literacy—how schooling and increase in literacy rate will help in improving the life
expectancy and Income Compositions—How disparity in Income will create an inequality in life
expectancies. We tried to implement Statistical analysis to support our claims, we used regression
techniques to train and test models to predict our outcomes. As our analysis reached its peak, we
identified that our assumptions were true and there is a statistically significant relationship between
all the attributes we took. As we go further into the report, more details will be furnished to support
our research.
<br>

DATA:
Based on our objective we found a dataset on Kaggle that has the attributes we require. We got
our dataset from Kaggle, Link is below:
https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who
The dataset has 22 attributes. They are Country, Year, Status, Life Expectancy, Adult Mortality,
Infant deaths, Alcohol, percentage expenditure, Hepatitis B, Measles, BMI, under-five deaths,
Polio, Total expenditure, Diphtheria, HIV/AIDS, GDP, Population, thinness 1-19 years, Income
composition of resources, and Schooling. A snippet of our dataset is shown below,
<br>

METHODS:
We used following methods on our dataset to do the statistical analysis. We did Data Summary,
Descriptive Statistics, Box Plots, Distribution Analysis, Co-relational Analysis, F-Test, Two
Sample T-Test, Multiple Linear Regression Analysis and ANOVA Test.
<br>

Steps:
We imported our data into RStudio using the below command.
Then we did data summary.
Descriptive statistics of Data.
To ease the process of analysis, we converted to categorial values to numerical values using the
following command. Assigned ‘1’ for developed countries and ‘0’ for developing countries.
After dividing countries into two categories, we plotted box plots for each of the attributes which
are shown below:
We made some important observations here which are discussed in the conclusion.
After that, we did distribution analysis to find whether the attributes are normally distributed or
not. We got the following results:
If we observe most of the attributes are not normally distributed.
Then we did co-relational analysis of Life expectancy with the factors mentioned above and we
got the following results:
F-Test to check variance of the two populations
Two-Sample T-Test for the equality of the two means
The focus of our project is to measure how strong the above-mentioned factors affect Life
Expectancy through Multiple Linear Regression Analysis, which is given below:
All the insights are mentioned in the conclusion.
<br>

CONCLUSION:
Note:
Null Hypothesis (H0)
There is no association between factors such as population, mortality rate, income, schooling, and
the life expectancy.
Alternate Hypothesis (H1)
There is significant association between the factors such as population, mortality rate, Income,
schooling, and the life expectancy.
For F-Test:
The observed p-value is less than alpha (0.05). Hence, we reject the null hypothesis and accept the
alternate statement that the variance of two populations is not equal.
For T-test:
The null hypothesis is rejected against the alternative hypothesis as the p-value<0.05. Hence, we
conclude that life expectancy in developed countries is more than that of developing countries with
95% confidence.
For Multiple Linear Regression Analysis:
As it is very clear from each test performed that p value is less than 0.05, we conclude by saying
null hypothesis is rejected and the alternate statement is accepted which denotes there is significant
association between the factors such as population, mortality rate, income, schooling, and the life
expectancy in both developed and developing countries past 16 years (2000-2015).
<br>

REFERENCES:
1. Centers for Disease Control and Prevention. (2022, April 25). NVSS - life expectancy.
Centers for Disease Control and Prevention. https://www.cdc.gov/nchs/nvss/life-
expectancy.htm
2. What is a residuals vs. leverage plot? (definition & example). (n.d.).
https://www.statology.org/residuals-vs-leverage-plot/
3. Kumarrajarshi: Novice. Kaggle. (n.d.). https://www.kaggle.com/kumarajarshi
4. Zach. (2021, December 1). Multiple linear regression by hand (step-by-step). Statology.
https://www.statology.org/multiple-linear-regression-by-hand/
5. Nakajima, H., Yano, K., Nagasawa, K., Kobayashi, E., Uetake, S., Takagi, I., & Yokota, K.
(2014). Nihon eiseigaku zasshi. Japanese journal of hygiene, 69(3), 187–198.
https://doi.org/10.1265/jjh.69.187
<br>

APPENDIX
• We did ANOVA test for our data, but it doesn’t provide much useful information to us.
The test and the results are mentioned below:
For ANOVA:
Higher F-value indicates that variation between groups is larger than the individual groups
demonstrating that income composition of resources (F:5342.9) have higher effect on life
expectancy whereas population (F:1.5) have lower influencing effect while adult mortality being
the second and schooling being the third.
