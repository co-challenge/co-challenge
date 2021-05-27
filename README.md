### Hi there 👋
This is the coding challenge for the cloud operations intership at LiveEO. \
It will check your knowledge on some basic file management skills. \
Let's get started!


1. clone this repo to your machine
2. create script that executes the following subtasks. You may use any language of your choice (.sh, .py, .js, .m, ... really any language you want!)  
* list all tifs contained in this repo by file size 
* Move all tifs to the same folder called "all_tifs", get rid of the old folders
* the .tif filenames contain information about the band ( e.g. "...B08_10m...") Group all tifs in folders by band (you will have 4 subfolders in ./all_tifs)
3. Now let's analyze an arbitrary .tif
* create a conda env from the environment.yml and activate it
* check any raster tifs meta data with the gdalinfo command and export it as meta.txt
* what projection is the raster using?  
* [optional] whats the raster's pixel resolution?


Submit your zipped script and meta.txt to matthias@live-eo.com \
Feel free to contact me anytime about the questions and any issues! 
