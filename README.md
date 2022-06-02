# Grouping-Similar-Words-for-Aggregation-using-Python
I used a dataset about some sales values from different brands with some discrepencies in their names to determine the top selling brands.
After loading the dataset, I did some data pre-processing to separate the accurate strings required for grouping. Then, I used a function call SequenceMatcher to set a similarity score between the strings. If a threshold score is met between two or more strings, they should be grouped into one and their sales values are summed.
