# Covid-19
This code is written in Python and uses several libraries such as pandas, numpy, seaborn, and matplotlib. The code reads a CSV file named "Latest Covid-19 India Status.csv" using the pandas library and stores the data in a pandas DataFrame object named 'data'. The first few rows of the DataFrame are displayed using the 'head()' function.

The code then uses the seaborn library to create visualizations of the data. Specifically, it creates three different plots using the 'relplot()', 'pairplot()', and 'catplot()' functions.

The first plot is a scatter plot created using 'relplot()' function that displays the relationship between the 'Population' and 'Total Cases' variables. The plot also uses the 'hue' parameter to color the data points based on the 'Discharged' variable. The 'hue' parameter can be used to differentiate between categories in the data, in this case, discharged and not discharged cases.

The second plot is a pair plot created using the 'pairplot()' function. This plot displays pairwise relationships between different variables in the DataFrame. This plot can be used to identify patterns and correlations between variables.

The third plot is a categorical plot created using the 'catplot()' function that displays the relationship between the 'Death Ratio' and 'Total Cases' variables. This plot also uses the 'hue' parameter to differentiate between categories of the 'Discharged' variable.

This code reads a CSV file and uses seaborn library to create three different plots that help visualize the relationships and patterns in the data.
