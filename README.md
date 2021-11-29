### Hi there 👋
This is the coding challenge for the operations group at LiveEO. \
It will check your knowledge on some basic file management skills as well as. \
Let's get started!


1. clone this repo to your machine
2. create a procedure that executes the following subtasks. You may use any language of your choice (.sh, .py, .js, .m, ... really any language/tool you want!)  
* list all tifs contained in this repo by file size 
* Move all tifs to the same folder called "all_tifs", get rid of the old folders
* the .tif filenames contain information about the band ( e.g. "...B08_10m...") Group all tifs in folders by band (you will have 4 subfolders in ./all_tifs)
3. Now let's analyze an arbitrary .tif
* create a conda env from the environment.yml and activate it
* check the raster's properties with 'gdalinfo' and export it as raster_meta.json
* what spatial reference system is the raster using?  
* [optional] whats the raster's pixel resolution? 
4. [optional] create a raster mosaic per band


Submit your zipped scripts raster_meta.json to matthias@live-eo.com \
Feel free to contact me anytime if you have questions and any issues.
