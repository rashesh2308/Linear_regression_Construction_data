# Linear_regression_Construction_data

The following is an outline for a simple data analysis project. 

Please download the dataset https://s3.amazonaws.com/cc-analytics-datasets/Building_Permits.csv. The provided dataset comes from the City of Raleigh Open Data website and is
based upon pending/granted building permits.


Here are the following concepts I have worked on

2. Load the data from the provided source via a web request rather than downloading a local copy and loading from disk. 
3. Review the summary statistics for the included features.
  o Number of rows and columns in the dataset 
  o Total different types of construction 
  o Mean and median number of stories 
  o Standard deviation for the X and Y coordinates of the permits 
4. Plot the distributions for each of the following features: Estimated Project Cost and Issue Date Month. Describe the distributions for these fields and explain what insights you might be able to gather. 
5. A hypothetical executive team is interested in the behavior between Permit Issue Year and Estimated Project Cost, but only for the "New" construction work class, with a construction type of "V B", and with less than 3 stories. Perform a simple regression analysis of this relationship and describe what insights we can gleam from this using success metrics. (Hint: Implement handling for missing values and explain your reasoning.) 
6. What additional techniques or methodologies could be used to improve the results from the previous step?


![Sample Visualization Plot](https://github.com/aditya-karampudi/Linear_regression_Construction_data/blob/master/Capture.PNG)

