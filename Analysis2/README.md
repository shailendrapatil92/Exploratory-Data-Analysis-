Group Work:
Contributers:
Apurva Gupta, Mingyang Ma, Shailendra Patil,



The data set NHANES in the R package of the same name contains data on a representative sample of Americans. Variables include:

Gender: female or male
Age in years
Height in centimeters
Weight in kilograms.
For this problem we'll restrict our attention to adults. You can use subset() to create a data frame contain only the people sample aged 18 and up:

Adults = subset(NHANES, Age >= 18)

Q1. Submit 2 or 3 graphs (no more or we'll take off points) that let you compare the distributions of adult women's heights and adult men's heights. Does it look like the difference between the distributions is well-approximated by an additive shift or a multiplicative shift, or is it something more complicated? If it's a shift, describe that shift quantitatively; if it's something more complicated, describe the difference in words.

Note: There are a few missing values; deal with these as best you can.

Q2. Submit 2 or 3 graphs that let you compare the distributions of adult women's weights and adult men's weights. Does it look like the difference between the distributions is well-approximated by an additive shift or a multiplicative shift, or is it something more complicated? If it's a shift, describe that shift quantitatively; if it's something more complicated, describe the difference in words.

Q3. Consider the following model for the dependence of height on gender:

lm(Height ~ Gender, data = Adults)

What proportion of the variance of the data is captured by the model? Is the model any good?
