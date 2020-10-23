# D3 Times - Data Journalism

### Using data pulled form the U.S. Census Bureau via a CSV file, this site creates a scatterplot to show visual correlations between Healthcare Risks and Age/Financial demographics.

### The chart is drawn using HTML5 , CSS, and raw JavaScript along with the D3.js plugin. Multiple axes on the chart allow the user to select their chosen metrics and instantly re-populate the chart with the correct axis and datapoints. Simply select the axis you would like and watch the circles move around! 

### It not only shows the datapoints with state abbreviation labels, but also will display a tooltip when clicked on for the specific data at that datapoint. These tooltips utilize the d3-tip.js plugin and adjust accordingly to which axis is selected.

*Note: attempts to call data from data.csv directly results in a CORS error. Rather than permantently open a port on my local machine, I've opted to include the dataset within app.js. This involved importing the data via D3.csv(), parsing the data into a text file, and hard coding the array of objects into app.js.*

-----