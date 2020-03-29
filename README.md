# AirBnb Price preduction in New York using Machine Learning 

For this project, we pulled 2019 airbnb listings in New York City data from insideairbnb.
Once we pulled the data, we had to perform an ETL to become more familiar with the data and also give our group a direction on which informatin to include in the dashboard.
We used Pandas to Clean and message the data. We then loaded the transformed data into PostgreSQL database.
The next step was creating the actual interactive dashboard to let our data tell a story and allow freindly user interaction.
We did this by developing a user friendly dashboard through app flask, where the user can explore and reach their own conclusions on what the data is saying.
We also created a map through leaflet of our airbnb stays in New York City based on popularity to show the user which parts of the city are being booked the most.
This ties into the goal of our dashboard, which is to give the user factors that affect bookings in each burrough of New York City.
The graphs shown on the dashboard were created with plotly.
We then created a webpage, designed through css and formatted through html to give the user a place to view our dashboard.
