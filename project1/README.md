Group Work

Contributors:

Apurva Gupta, Shailendra Patil, Surbhi Paithankar

A researcher for a thinktank wants to learn about life expectancy and its relationship to
GDP per capita. He notices there is an R package called gapminder that contains a data
set of the same name giving the GDP per capita (adjusted for inflation) and life
expectancy in 142 countries for a selection of years from 1952 to 2007. He has taken an
introductory statistics course using R, but that was a long time ago, so he is outsourcing
 the exploratory data analysis to YOU.

His major research question is: Can the increase in life expectancy since World War 2 be
largely explained by increases in GDP per capita? However, he recognizes this question
may be difficult to answer, at least straight away. So he has brainstormed a series of
questions he would like you to address, which can be divided into three groups:

1. GDP and life expectancy in 2007: How does life expectancy vary with GDP per capita in
2007? Can the trends be well-described by a simple model such as a linear model, or is a
more complicated model required? Is the pattern the same or different for every continent?
If some continents are different, which ones? Can differences between continents be
simply described by an additive or multiplicative shift, or is it more complicated than
that?

2. Life expectancy over time by continent: How has average life expectancy changed over time
in each continent? Have some continents caught up (at least partially) to others? If so,
is this just because of some countries in the continent, or is it more general? Have the
changes been linear, or has it been faster/slower in some periods for some continents?
What might explain periods of faster/slower change?

3. Changes in the relationship between GDP and life expectancy over time: How has the
relationship between GDP and life expectancy changed in each continent? Can changes in
life expectancy be entirely explained by changes in GDP per capita? Does it look like
there's a time effect on life expectancy in addition to a GDP effect? Has there been
"convergence" in the sense that perhaps GDP and/or continent don't matter as much as it
used to? Are there exceptions to the general patterns?


Constraints:

1. The researcher is familiar with elementary methods like linear models, but not with n
onparametric methods such as loess and gam. That means that if you want to use those more
fancy models, you need to briefly explain what those techniques are doing in words that a
non-statistician can understand.

2. He is comfortable with transformations, but they would have to be interpretable.

3. He took his statistics course from a fairly skeptical lecturer, so he knows all models are
wrong. However, he is willing to accept some wrongness in exchange for a simple
description of the data.

4. He doesn't need to see the R code, but wants to be able to reproduce your work if required.

5. The researcher has noticed that student reports on complex real-world phenomena often
(accidentally one hopes) say offensive things, and would prefer if you didn't do that
