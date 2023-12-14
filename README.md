# Huston-flight-analysis-
**Tableau Visualization of Houston Flight Data**
**These are the steps I followed and created 2 interactive dashboards**

**Data Import and Join:**
1. Import the Flights and Airports tables into Tableau.
2. Join the two tables using the condition flights.dest = airports.iata.

**Filled Map Analysis:**
1. In the Measures box, keep Dist, Time, Dep Delay, Arr Delay from flights.csv, and Long, Lat from airports.csv.
2. Move other columns to dimensions.
3. Create a filled map that displays the number of flights into each state.
   - Show #flights as a label.
   - Use color to reflect the number of flights.
   - Show #cities and #flights in Tooltip.

**Pie Chart for Market Share:**
1. Create a pie chart illustrating the market share for each carrier.
   - Show market share as a percentage.

**Symbol Map for Carrier Market Share:**
1. Create a symbol map displaying, for each city, the market share of carriers.

**Stacked Bar Chart for Flights to Each Airport:**
1. Create a stacked bar chart showing the number of flights to each airport.
2. Sort the airports by total number of flights.
3. Use different colors to represent the number of flights delayed for <=0, 1-30, 31-60, 61-90, 91-120, >=120 minutes (create a group using dep delay).

**Box Chart for Arrival Delay Distribution:**
1. Create a box chart illustrating the distribution of arrival delay for each flight number.

**Histogram for Flights Over Hour Group:**
1. Create a histogram showing the number of flights over an hour group (5-8, 9-12, 13-16, 17-20, 21-4).

**Dashboard 1:**
1. Use a state map, market share pie chart, and airport bar chart.
2. Enable filters by:
   - Clicking on the map to filter by state.
   - Clicking on the pie chart to filter by carrier.
   - Hovering over an airport to highlight the state and filter by carrier.
3. Allow users to choose the month.

**Dashboard 2:**
1. Use a city map, hour histogram, and flight box plot.
2. Utilize the hour group as a filter.
3. Enable filters by:
   - Clicking on the map to filter by city.
   - Hovering over a flight to filter the hour histogram.
4. Allow users to choose the weekday and arrival/departure delay.

By implementing these visualizations and dashboards, the Tableau analysis will provide comprehensive insights into Houston flight data, enabling users to explore and understand various aspects of the dataset.
