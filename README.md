# Lviv Transport Analysis

## About
- Obtaining information about public transport stops and routes from the results of the project "Optimization of transport connections Lviv UCU-2022.
- Collection of information about public transport traffic schedules in divisions of the Lviv City Council
- Development of algorithms for determining the fact of public transport visiting stops based on open data on public transport traffic, which are published in the GTFS format.
- Identification of metrics for the detection of mass non-compliance with public transport traffic schedules.
- Development of algorithms for calculating metrics for detecting mass non-compliance with public transport traffic schedules and their testing on data for one month.

## Content of the repository
- _tools_ - code for receiving the data of fact of visiting stops based on data gathered for certain day. Also storing in database.
- _data_ - all the data received by ourselves such as open sources and Lvivavtodor documentation.
- _analysis_ - code for analysis, building heatmaps, histograms, dashboard and running linear regression model for certain day.

## Analysis
In the analysis folder there are 5 scripts responsible for the creating all the necessary visualization used in producing the insights about the situation with the Lviv transport following the schedule.
For example, `bus_stops_histogram_builder` is respondible for creating the histograms for each busstop on each route. The histogram created with this tool, will show the number of arrivals of the bus with the certain time interval.
In the `heatmap_builder` there are a couple of functions that are responsible for constructing the heatmaps, based on the collected data. Produced heatmaps will show the average waiting time for the certain hour on each bus-stop present on the route. The brighter is the color, the longer on average it took for the arbitrary person to wait for the bus.
In the interval plot builder we ...
The script in the `intervals_for_stops_map_builder`

## The team - students of IT and Business Analytics Programm:
- Sofiia Yamkova
- Dmytro Batko
- Tetiana Vinnik
- Andrii Vandzhura
- Veronika Shevtsova
- Valeriia Fedorchak
- Mariana Skoropad
