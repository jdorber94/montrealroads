# montreal cars vs bikes
To simply view the data we have produced for the city of Montreal, go to the Try it Out document and follow the steps there to view the visualization in Cesium sandcastle.
There you can edit different attributes of the visualization like the extrusion height, color gradient, and opacity.

The backend script takes two important pieces of data; A boundary polygon representing the area you want to create biking vs driving data in, in our case it is Montreal's boundaries, and a GeoJson containing data for 
the roads in your city likely representing each road as a polygon.

The script Cars_v_Bikes_Data_Gather can then be ran to calculate all data needed to create your own data to be plotted in cesium. This is a Jupyter Notebook containing all the functions necessary to produce the data.
You must enter your own google maps API key. Be careful to be mindful of the amount of API are using because it will cost you money. Every 1000 times call_gmaps is run it costs $5.



