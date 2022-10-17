Pymaceutical ANOVA Tukey
For this assignment, you’ll first apply an analysis of variance (ANOVA) model to the Pymaceutical dataset and then do a post-hoc analysis of the results by using Tukey Honest Significant Difference (HSD) to determine which drug treatments in the dataset significantly reduce tumor volume and metastasis. After you perform your analysis, you’ll write a summary of your findings.

Read the Pymaceutical_data.csv file into a DataFrame.

Determine which drug treatments significantly reduce tumor volume by completing the following steps:

Create a box plot that compares the drug regimens with tumor volume.

Create a Series of data for each drug treatment that has the tumor volume for each mouse.

Perform ANOVA to compare the means of the tumor volume for each drug regimen.

Perform a pairwise Tukey HSD test to compare the means of the tumor volume for each drug regimen.

Answer the following question: Which drug treatments significantly reduce tumor volume? Use the statistical analysis to support your results.

Determine which drug treatments are more effective than the others at reducing the number of metastatic sites at 45 days by completing the following steps:

Create a new DataFrame that contains data from the the last time point—that is, 45 days.

Create a box plot that compares the drug regimens and metastatic sites.

Create a Series of data for each drug treatment that has the number of metastatic sites for each mouse.

Perform ANOVA to compare the means of the metastatic sites for each drug regimen.

Perform a pairwise Tukey HSD test to compare the means of the number of metastatic sites for each drug regimen.

Answer the following question: Which drug treatments significantly reduce the number of metastatic sites? Use the statistical analysis to support your results.

Write a summary based on both statistical analyses.
