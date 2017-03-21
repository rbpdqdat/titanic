# titanic

# Introduction

This is an investigation about a sample of passengers from the titanic manifest.  The decription of the data can be found in the description_titanic_data.txt.  The analysis was performed in the DataDive.ipynb Jupyter Notebook.

# Summary

Initially, most of the data seemed to be available. A count of the rows of data show there to be 892 rows of data including the header. The web site [titanic facts](http://www.titanicfacts.net/titanic-passengers.html) idicates that this data set does not include all of the passengers aboard the titanic when it sank. According to this web site there were approximately 1,317 passengers actually on board.

The data set in this study only has 891 passengers. The 'Age' column had over 150 missing values. There are many different ways to look at the data. This study focused on 'Pclass'- passenger class, 'Sex'- male/female, and 'Age'. All of which for this study, end up as factor variables.

The best relationships appear to be when combining the Age Factor Variables, Passenger Class, and Sex. There are issues with very small sample sizes. So, the next best categorical search seemed to be when both the class and sex were combined. In conclusion, a person would theoretically be most likely to survive the titanic disaster if you were a women from first class. To properly test this theory it would be necessary to take a smaller random sample from the population and then create probabilities, and then test the probabilities with the remaining data. 
