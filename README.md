# Page-View-Time-Series-Visualizer
In this project, I will visualize time series data using line charts, bar charts, and box plots.
I will use Pandas, Matplotlib, and Seaborn to visualize a dataset containing the number of page views each day on the freeCodeCamp.org forum from 2016-05-09 to 2019-12-03. The data visualizations will help me understand the patterns in visits and identify yearly and monthly growth.
<ul>
  <li>I will use Pandas to import the data from "fcc-forum-pageviews.csv". Set the index to the date column.
  <li>Clean the data by filtering out days when the page views were in the top 2.5% of the dataset or the bottom 2.5% of the dataset.
  <li>I'm creating a draw_line_plot function that uses Matplotlib to draw a line chart similar to "examples/Figure_1.png". I made the title Daily freeCodeCamp Forum Page Views 5 / 2016-12 / 2019. On the x-axis, I labeled "Date" and on the y-axis, "Page Views".
