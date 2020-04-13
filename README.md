# TMB_plotting_function

**Inputs**

1. inputDF: A panda dataframe containing two columns and however many rows of samples. Column 1 is the category the sample belongs to, column 2 is the number of mutations in that sample.
2. scale: "exome" or "genome" or an integer indicating the scale of the sequencing
3. Yrange: The range of Yaxis. The options are either "adapt", which will make the plot automatically adapt to the given dataset, or "cancer", which will set the range to 0.001 to 1000, or a list of two numbers of powers of 10 indicating the Y-axis range.