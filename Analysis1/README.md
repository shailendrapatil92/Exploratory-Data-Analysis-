The file tips.txt contains data on tipping. The variables it contains are:

total_bill in dollars
tip in dollars
sex (Female or Male) of the bill payer
smoker (whether or not there was a smoker in the party)
day of the week
time of day (Lunch or Dinner)
size of the party (number of people)

Obviously the tip depends heavily on the total bill, so the quantitative variable we'll study will be the percentage tipped (tip over total bill as a percentage.) The lowest percentage tipped was 3.6% and the highest was 71%.

Q1. Use ggplot() to draw ONE graph of the percentage tipped for the sample that enables you to see the center, spread, and shape of its distribution. Make sure your graph looks nice (meaningful titles and labels, sensible choices of any adjustable parameters.) Describe (numerically or in words) the center, spread, and shape of the distribution. Is the distribution normal?

Q2. Use a set of faceted plots to display the distribution of percentage tipped for each party size in a way that allows easy comparison. Are there clear differences between the distributions for different party sizes, or are they about the same? Or is it impossible to say? Explain.

Q3. Pick a measure of center for the percentage tipped distributions (either mean or median), and explain your choice. Use the aggregate() function to find the center of percentage tipped for each party size, and display these using a dot plot. Without doing a formal statistical test, answer: which (if any) differences in the centers for different party sizes look real, and which can be reasonably explained by chance variation?
