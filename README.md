# data_trafficers_project

This project was a four person team effort to create a web app which takes in traffic incident, volume and volecity data from the City of Austins
website and visualize that data.  A geojson API of data from 2018, thus far, was pulled and imported into a javascipt file where it was 
mapped as a heat map using leaflet.  A line graph using Plotly on the opening page shows the number of traffic incidents for each day showing a 
very variable pattern day to day.  A Sqlite database was used to store the traffic volume and speed data which is graphed using d3 as 
scatter plots in which the user can select the month they would like to look at.  The app was assembled using Flask and launched on
Heroku
