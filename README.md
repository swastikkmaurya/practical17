# practical17

Aim: Basic Charts and Visual Encoding

Theory:

This experiment focuses on Data Visualization, a critical component of data analysis used to transform complex datasets into visual representations like charts and graphs to uncover patterns, trends, and correlations.
By utilizing the matplotlib and seaborn libraries, the program demonstrates how to generate various plots—such as bar charts, histograms, and scatter plots—to interpret categorical and numerical distributions effectively.

Visualizations map complex mathematical structures into visual formats that humans can easily interpret to find patterns, trends, and outliers.

Line Chart: Used for tracking trends over time. The algorithm maps independent variables (like days) to the X-axis and dependent variables (like sales) to the Y-axis, connecting the coordinates with continuous line segments.

Bar Chart: Used for comparing discrete categories. The algorithm calculates the frequency or specific value of distinct categories and draws rectangular bars from a baseline to a height proportional to that value.

Histogram: Used to visualize the distribution of continuous data. The algorithm determines the data range, divides it into equal-width "bins," counts how many data points fall into each bin, and draws adjacent vertical bars representing those frequencies.

Scatter Plot: Used for discovering relationships and correlations between two variables. The algorithm plots standalone dots on a 2D Cartesian plane for every pair of data points. If the dots form a recognizable pattern (like an upward slope), it indicates a correlation.

import matplotlib.pyplot as plt: Imports the primary library used for creating static, interactive, and animated visualizations in Python.

import seaborn as sns: Imports a high-level interface based on matplotlib for drawing attractive and informative statistical graphics.

plt.bar(): Creates a bar chart to compare different categories of data using rectangular bars.

plt.xlabel() / plt.ylabel(): Sets the text labels for the x-axis and y-axis respectively to provide context to the plot.

plt.title(): Adds a main heading to the top of the chart to describe the visualization.

plt.show(): Renders and displays all currently active figure objects onto the screen.

plt.hist(): Generates a histogram to represent the distribution of a continuous numerical variable by binning data.

plt.scatter(): Produces a scatter plot to observe the relationship or correlation between two numerical variables.

plt.pie(): Creates a pie chart to illustrate numerical proportions as slices of a circle.

plt.legend(): Places a box on the graph to describe the different elements or data series plotted.

sns.lineplot(): Draws a line graph to show data trends over a continuous interval or time period.

sns.countplot(): Uses bars to show the frequency of observations in each categorical bin.

sns.boxplot(): Displays the distribution of data based on a five-number summary (minimum, first quartile, median, third quartile, and maximum).

Conclusion:

Through this experiment, it is concluded that Data Visualization is essential for effective data storytelling. By selecting appropriate plots—such as bar charts for comparisons, histograms for distributions, and scatter plots for correlations—analysts can present data in an intuitive way that simplifies the decision-making process.
