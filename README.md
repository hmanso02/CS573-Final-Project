# CS573-Final-Project
Project link: ["VisA to VisB to VisC on Hamid's Github"]()
Project link: ["VisA to VisB to VisC on Emma's Github"]()
Project link: ["VisA to VisB to VisC on Xiaoyan's Github"]()

# Team

- Hamid Mansoor, hmanso02
- Mei Yang, emmagitlab
- Xiaoyan Sun, jacysun


# Overview 

Air travel has become widely available to travellers in the US. Delays and cancellations by major airlines causes a lot of problems for travellers. We want to give viewers a tool to make an informed decision about the airline, airport, time of travel etc. that they choose, based on historical flight data. 
We narrowed out scope to 30 major airports according to their rank in number of flights.
We wrote script to filtered out the filtered out the flights with origin or destination that we are not interested in. 
For the on time data for the parallel coordinates plot and the cancellation data for the treemap, we used python to group together the data by airline and years.


# Design Achievements
We used four kinds of chart to present the delay and cancel information for 30 major aiports:

The first visualization is a Parallel Coordinate plot showing the flight ontime arrival performance of nine major carriers from year 2010 to 2015.

Non-obvious features: Click each line to highlight the specific information.

![multiple](image.png)

The second visualization is a Map showing the flight routes and their average delay time for a specific month of a specific carrier, which is the average of the past 6 years from 2011 to 2016.

Non-obvious features: Click carries and month and hover over or click to check average delay information of the carrier during a perticular month.

![multiple](image.png)

The third visualization is a Table  and donut chart that allows user specify origin, destination and the month. 

Non-obvious features: After clicking the show button, the table is populated with the flight delay data for the major carriers operating those routes. The user has the ability to sort the carriers in ascending or descending order by any of the measure in the table by clicking on the arrows in the column headers. 
The proportions of flight delay causes are displayed in donut charts, each one representing a carrier. This segment gets updated every time the metrics change.

![multiple](image.png)

The final visualization we implemented a grid of treemaps.Each treemap represents one month of the year. The individual tiles represent the proportion of each cause of cancellation.  

Non-obvious features: Hovering over the tiles highlights that particular cause and carrier across all the other treemaps as well

![multiple](image.png)

#Division of responsibilities:
Hamid worked on Parallel Coordinate and Treemap.  

Mei Yang worked on data training, Table and Donut chart, and user interface.

Xiaoyan Sun worked on data filter, data training, Map with Bar chat.

#References:



