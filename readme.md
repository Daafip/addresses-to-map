# About
This script was developed to make a readable route between 5 points.
These should be called `Adres1`,`Adres2` ... `Adres5`: these names are important but can be changed in lines 30 -36 of cell 2.<br>
It uses `router.project-osrm.org` for bikes, but this is the same as walking we found: thus the route is unreliable. <br>
A line can be drawn between the points, but as the map generated is intended for cycling this reduced readability.
Thus we actually just use the router to obtain the correct zoom level. If you want a cyclic map, then you can have the start and end the same as in the example. <br>
The points are then ploted on the map, with the adresses.<br>
This html map is loaded using seluium, screenshotted and converted to pdf. <br>
At the end text is added to the bottom, this can be edited in lines 100 of cell 2.<br>
Some initial comments are in dutch, ill update those if needed along the way. <br>
Feel free to create an issue if something is unclear. <br>
Conda environment added can be installed using `conda env create -f environment.yml`. 