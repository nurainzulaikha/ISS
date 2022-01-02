# ISS

In file named Finding ISS.ipynb, I am using API (http://api.open-notify.org/iss-now.json) to track the coordinate of International Space Station (ISS) in real time and translated into the location on the map. I am using python to do the coding. First, import all the package needed such as pandas and plotly. Then, named a variable to store the information.
In this file, I name the variable with 'coordinate' that stored the link of the latitude and longitude. 

After that, I create other variable to read the json file. As the result show, create the new column for latitude and longitude to make it easy when plotted on the map.
Then, use package plotly to plot on the map.
Lastly, on the map, there will have the dot that show the location of the ISS also the latitude and the longitude.
