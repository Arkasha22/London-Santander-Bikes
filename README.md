# London-Santander-Bikes

I used the website MapTiler for the base mapping and hosting of the GeoJSON file with the bike locations. I also used the Transport for London (TfL) API in order to get the real-time number of standard bikes, e-bikes and the number of empty docks.

Each icon represents the location of a docking station, and uses a colour scheme, with red symbolising 0 facilities available, orange symbolising 1 - 4 facilities available and black for 5 or more facilities available. Within the map window, the colour of the icon is selected by the lowest value of standard bikes, e-bikes and empty docks. Clicking on a bike icon shows the name of the docking station, number of standard bikes, e-bikes and empty docks available.
