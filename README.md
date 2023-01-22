# final_capstone

This code is doing several things:

It is importing libraries for data manipulation, visualization, and clustering.
It reads in a CSV file 'UsArrests.csv' and stores it in a pandas dataframe 'data'.
It calculates summary statistics of the dataframe using the 'describe()' function.
It checks for missing values in the dataframe using the 'isnull().sum()' function.
It prints the data type of each feature using the 'dtypes' attribute.
It plots histograms of each feature using the 'hist()' function.
It calculates the Pearson correlation coefficient between each pair of features using the 'corr()' function and plots it as a heatmap using seaborn's 'heatmap()' function.
It performs Principal Components Analysis (PCA) on the data by standardizing it, fitting it to a PCA object, transforming it, and plotting the explained variance.

To install this project locally, you will need to have the following dependencies installed:

pandas: for data manipulation
numpy: for numerical computation
matplotlib: for data visualization
seaborn: for statistical data visualization
scikit-learn: for machine learning and preprocessing
scipy: for scientific computing

After installing the project, you can use it by running the script and providing the 'UsArrests.csv' file in the same directory as the script.

The script will read in the data from the CSV file, perform data analysis and visualization, and output the results in the form of plots and summary statistics.

The script will first display the head of the dataframe, which shows the first five rows of the data.

Then it will display the summary statistics for each column of the dataframe, which includes the count, mean, standard deviation, minimum, 25th percentile, 50th percentile (median), 75th percentile, and maximum for each column.

Next, it will check for missing values in the dataframe and print the number of missing values for each feature.

It will also print the data type for each feature

The script will then plot histograms for each feature to visualize the distribution of observations for each feature.

It will then plot a heatmap of the correlation matrix, which shows the correlation between each pair of features.

It will also perform Principal Component Analysis (PCA) on the data, and display the explained variance by each principal component.

Finally, it will display the plots, which will provide insight into the data and its relationships.

The script can be modified to perform additional analysis or visualization as needed.

This project was created by me, Darren Woodcock. The script is based on a sample dataset 'UsArrests.csv' from the R package "datasets", which is a built-in R package. The dataset contains statistics on the arrests per 100,000 residents for assault, murder, and rape in each of the 50 US states in 1973.

The script uses various data manipulation, visualization, and machine learning libraries such as pandas, numpy, matplotlib, seaborn, scikit-learn, and scipy to perform data analysis and visualization. These libraries are widely used in the data science community and have a large user base and active development community, which makes them a great choice for data analysis projects.

If you have any questions or need further assistance, please let me know.
