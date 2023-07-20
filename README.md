# Module_5_Challenge

Run the provided package dependency and data imports, and then merge the mouse_metadata and study_results DataFrames into a single DataFrame.

Display the number of unique mice IDs in the data, and then check for any mouse ID with duplicate time points. Display the data associated with that mouse ID, and then create a new DataFrame where this data is removed. Use this cleaned DataFrame for the remaining steps.

Display the updated number of unique mice IDs.

Generate Summary Statistics:

Create a DataFrame of summary statistics, including a row for each drug regimen and columns for mean, median, variance, standard deviation, and SEM of the tumor volume.
Create Bar Charts and Pie Charts:

Generate two identical bar charts showing the total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study:
Create the first bar chart with the Pandas DataFrame.plot() method.
Create the second bar chart with Matplotlib's pyplot methods.
Generate two identical pie charts displaying the distribution of female versus male mice in the study:
Create the first pie chart with the Pandas DataFrame.plot() method.
Create the second pie chart with Matplotlib's pyplot methods.
Calculate Quartiles, Find Outliers, and Create a Box Plot:

Calculate the final tumor volume of each mouse across four promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
Calculate the quartiles and IQR, and identify potential outliers for all four treatment regimens using the upper and lower bounds.
Generate a box plot with Matplotlib, showing the distribution of final tumor volume for each treatment group and highlighting potential outliers.
Create a Line Plot and a Scatter Plot:

Select a single mouse treated with Capomulin and generate a line plot of tumor volume versus time point for that mouse.
Generate a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.
Calculate Correlation and Regression:

Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.
Plot the linear regression model on top of the previous scatter plot.

Sources for code used in this challenge: https://stackoverflow.com/questions/tagged/matplotlib+python
