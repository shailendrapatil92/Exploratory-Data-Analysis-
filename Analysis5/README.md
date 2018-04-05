Group Work

Contributors:

Apurva Gupta, Shailendra Patil, Surbhi Paithankar

The file rustdrugs.txt contains county-level data on 2016 deaths from drug-related causes
in the East North Central region, consisting of the states Ohio, Michigan, Indiana,
Illinois, and Wisconsin. The region is sometimes called the Great Lakes (although this
usually includes Minnesota) or the Rust Belt (this usually includes Pennsylvania.)
The variables are:

County
Deaths: number of drug-related deaths in 2016
Population in 2016
Area: land area of county in square miles
PctWhite and PctBlack: percentage of the population who are white and black respectively
Income: median household income
Trump: proportion of 2016 Presidential election votes that went to Trump
Obama: proportion of 2012 Presidential election votes that went to Obama

Your goal is to fit a model that explains variation in drug-related deaths in these
counties in 2016. For simplicity, a linear model is recommended. (You can fit a
nonparametric model if you feel ethically obligated to, but you won't get any extra
points for it.) Your response variable will be the rate of drug-related deaths per
100,000 population (the standard way to measure this.) We'll take the counties as our
units, so there's no need to weight the model by population.

Question

1. Create a variable DeathRate giving the rate of drug-related deaths per 100,000
population. Put this in a data frame with three numerical predictors:

Income (might be better to express this in thousands of dollars rather than dollars),
Trump percentage (percentages are more widely understood than proportions),
One other quantitative variable of your choice.
Draw a pairs plot of your data and comment on potential problems with model-building
(outliers, extreme skewness, multicollinearity), or say "it's all good" if there are no
such problems.

2. We wish to determine whether our model requires an income:Trump interaction. Draw sets
of one-way and two-way faceted plots to graphically examine this potential interaction.
Explain what your plots tell you (or don't tell you) about the need for this interaction
in your model.

3. Fit a model to explain the drug death rate in these counties. Your model must include
at least one interaction. You can decide on your model by looking at graphs or by using
your favorite numerical criterion (AIC/BIC/etc.); there are many valid choices. Display
the model fit graphically in a way that emphasizes the interaction. You must truncate your
plots to remove regions that are far away from the observed values of the explanatory
variables (e.g. very high incomes.) Explain how the interaction shows up (or doesn't show
up) in your plots.
