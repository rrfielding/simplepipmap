# simplepipmap

[This](https://pattyf.github.io/simplepipmap) is a hack of http://jackdougherty.github.io/leaflet-map-simple
and
https://github.com/csessig86/leaflet-markers-within-radius

## To customize

- You only need to make changes in **index.html** file and replace the **data.csv** file with your data in same format.
    - You really just need the Title, Latitude, and Longitude columns
- Update **data.csv** to be your data but in same format with same headers.
- Get a **google maps api key** and update the **key=** line in index.html.
- Find the line in **index.html** that reads **center:** and change that to the lat/lon for your map center.
- Set the default zoom level to one appropriate for your data. With the map centered on your map center point and with your zoom level all points should display in the map. If not you may have errors. The default is set to 12 which may work for you. You can find the zoom setting in index.html at **zoom: 12**
- You may want to update the select list of search radius options.
- For help with creating your data.csv file, see: <a href="https://www.datavizforall.org/leaflet/with-google-sheets/" target="_new">https://www.datavizforall.org/leaflet/with-google-sheets</a>

#### Learn more
See the online textbook: 

- Jack Dougherty and contributors, *Data Visualization For All*, a free textbook and online course, Trinity College, Hartford CT, http://DataVizForAll.org

This really helpful book has a chapter on creating and hosting your site on github.


