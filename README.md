# Opportunity Finder

This project is about creating a web map using the details from Guilford county data GIS website.
This is written in HTML, CSS, JS and using the leaflet library

** Base maps**

We have used 3 base maps - Stamen toner, ESRI world and Open Street Map.
If you want to look into the parcels with a better view on highways, then stamern toner lite is a better layer to be "on" to view. Hence choose the view most suited.

Some of the useful links and information:

To add the parcel data : you can acces the link  from " http://gis.guilfordcountync.gov/arcgis/rest/services/Cadastral"
Other links are also added from the services layer from the same repository. 

** To search using address or street name**

Use the search bar and search with "address" or "street name" or "PINCODE"

** Filter using specific land classification**

TO choose and filter to a specific land class type, Choose the "Land Type"
 You can find the values that correspond to each of them below:
 
        "LAND_CLASS='RESIDENTIAL'">RESIDENTIAL
        "LAND_CLASS='TOWNHOUSE'">TOWNHOUSE
        "LAND_CLASS='APART'">APARTMENT
        "LAND_CLASS='IND'">INDIVIDUAL PROPERTY
        "LAND_CLASS='CONDO'">CONDOMINIUM
        "LAND_CLASS='MULTI-FAMILY<4'">MULTI-FAMILY
        "LAND_CLASS='GOV OWNED'">GOVT OWNED>
        "LAND_CLASS='VACANT'">VACANT 
        "LAND_CLASS='INSTITUTIONAL'"
        "LAND_CLASS='COMM'">COMMERCIAL
        

** Filter and Hover **

In order to see parcel files particular to just a single class type, choose a filer from the above and hover the map to the location you need.
Also, you can find the place by using the search bar and then zooming in. This helps to give an idea of reoccurance of the same parcel files in a specific area or address.


If you need more info or help about this tool, please email : lalitha@nmsu.edu or kasuttl2@uncg.edu

For more information of Leaflet :  https://leafletjs.com/
For more infomation on ESRI Github : https://esri.github.io/esri-leaflet/

Reference : We reffered to the LAND (Land Access Neighborhood Development Tool) for the tool design and the link to the website would be https://land.ccs.miami.edu/explore/parcels
 

