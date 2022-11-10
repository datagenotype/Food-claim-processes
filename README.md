# Food-claim-processes
Vivendo is a fast food chain in Brazil with over 200 outlets. As with many fast food establishments, customers make claims against the company.For example, they blame Vivendo for suspected food poisoning.The legal team, who processes these claims,is currently split across four locations. The dataset for this case study comprises of 8 columns and 98 rows. In this analysis, the following modules are used:
Matplotlib
Pandas
Numpy
Seaborn

The analysis as well is in the following order:
introduction
Data wrangling
Exploratory data analysis
conclusion

During the exploratory data analysis, it was realized that some rows in 'Cause' columns are NAN which was changed to Unknown. For the claim amount column, it was realized that some characters are needed to be remove so we can easily change the data type to a float. 
The followings are what were deduced from the dataset:
It can be deduced from the analysis that most cases are not linked to another cases.
It is shown that Claim Amount and Amount paid have a strong positive correlation, Claim Amount and Time to close has a weak negative correlation, Amount paid and Time to close have a weak negative correlation.
It can be deduced from the analysis that most cause of the poison is not known and the other causes are meat and vegetables.
The distribution of time to close is right skewed which means the mean is greater than the median and the mode as well. It is also observed that most claim takes 500 days to close.
It can be deduced from the above bar chart that SAO LUIS and NATAL have the highest and lowest claims respectively.
