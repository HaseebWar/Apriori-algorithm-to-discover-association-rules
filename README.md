# Apriori-algorithm-to-discover-association-rules

Code Explanation:

# 1.	Data Import and Exploration:
	Import necessary libraries and read the dataset from a CSV file.
	Display the first few rows of the dataset.
	Check for missing values in each column.
	Get information about the dataset.
	Convert the 'Date' column to datetime format.

# 2. Top 10 Sold Items Bar Plot:	
	Group the dataset by "itemDescription" and calculate the frequency of each item.
	Select the top 10 items with the highest frequency.
	Create a horizontal bar plot to visualize the top 10 sold items.

# 3. Number of Items Sold by Month:
	Set the 'Date' column as the index of the dataframe.
	Resample the data by month and count the number of items sold.
	Create a line plot to show the number of items sold over time.

# 4. Association Rule Mining:
	Sort the dataset by "Member_number" in descending order.
	Retrieve the list of transactions for each customer.
	Apply the Apriori algorithm to find association rules.
	Specify the minimum support, confidence, lift, and length of rules.
	Store the results of the association rule mining.

# 5. Confusion Matrix and Accuracy:
	Define the ground truth rules and discovered rules as dataframes.
	Get the unique labels from both sets of rules.
	Create a confusion matrix using the ground truth and discovered rules.
	Convert the confusion matrix to a dataframe.
	Visualize the confusion matrix using a heatmap.
	Calculate and display the accuracy of the discovered rules.

# 6. Summary Statistics and Visualizations:
	Create a dataframe with summary statistics of the discovered rules.
	Plot a histogram of the support values.
	Create a scatter plot of confidence versus lift.
	Generate a bar plot of left-hand side items versus support.
	Display a heatmap of the correlation between support, confidence, and lift.
