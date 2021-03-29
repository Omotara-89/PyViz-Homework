## PyViz-Homework

Unit 6 - Pythonic Monopoly (Summary of the work done)

The activity involved the building of a prototype dashboard with a goal to provide charts, maps, and interactive visualizations that help customers explore the data and determine if they want to invest in rental properties in Toronto.

The first part of the activity involved the rental analysis to determine dwelling types per year, average monthly shelter costs in Toronto per year, average house value per year and some other parameters. Once the calculation and coding is okay, visualization of the various result is also included. 
Before beginning the task in this activity, the various libraries needed to complete the assignment was imported and installed.  Below are part of the information that is required to be calculated and plotted.

a.	Dwelling Types per Year: The sum number of dwelling types units per year was calculated using groupby. A bar chart function was defined/created and this was used to plot a bar chart per year to show the number of dwelling types. The bar charts were plotted using various colors with the Matplotlib library.

b.	Average Monthly Shelter Costs in Toronto per Year: The average yearly shelter costs for owned and rented dwellings. Just as above, a line chart function was defined/created and this was used to plot a line chart per year for owned and rented types. The charts were plotted using various colors with the Matplotlib library.

c.	Average House Value per Year: This is to determine how long to hold the rental property for. Mathplotlib was used to create a line chart to visualize the outcome.

d.	Average House Value by Neighborhood, Number of Dwelling Types per Year and Top 10 Most Expensive Neighborhoods: Hvplot was used to create an interactive chart of the required information.

e.	Neighborhood Map: After reading the neighborhoods location data and preparing the data by joining the location data with the mean values per neighborhood, an interactive map with the average house value per neighborhood was built using a scatter mapbox from Plotly express to create the visualization.

The second part of the activity require the visualizations from the previous analysis above into functions to create a Panel dashboard. This was done by:

i.	Copying the code for each plot type from the rental analysis notebook and placing it into separate functions that Panel can use to create panes for the dashboard. These functions will convert the plot object to a Panel pane.

ii.	Returning a Panel pane object from each function that can be used to build the dashboard.

iii.	Combine all of the plots into a single dashboard view using Panel.
