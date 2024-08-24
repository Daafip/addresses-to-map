# About
This script was developed to make a readable route between 5 points: `Adres1`,`Adres2` ... `Adres5`: these names are important but can be changed in lines 30 -36 of cell 2.<br>
It uses `router.project-osrm.org` for bikes, but this is the same as walking we found: thus the route is unreliable. <br>
A line can be drawn between the points, but as the map generated is intended for cycling this reduced readability.
Thus we actually just use the router to obtain the correct zoom level. The points are then ploted on the map.
This html map is loaded using seluium, screenshottedn and converted to pdf. 
At the end text is added to the bottom. 
The comments are in dutch. 