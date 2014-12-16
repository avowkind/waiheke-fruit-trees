# Home Study Notes

# Goal 1 - Photo Mapping using Javascript and NodeJS.
I have a folder of photographs taken from the surrounding area showing the location of a number of fruit trees.  I want to plot the locations of these trees on a map.
1. Produce a simple non interactive map image showing the locations.
2. Produce a simple interactive web page e.g. leaflet, showing the locations and opening the images on screen.

This will be done using Javascript and NodeJS.
Guided by : http://ole.michelsen.dk/blog/showing-photo-gps-location-on-google-maps-with-gulp.html

## New technologies:
### Gulp - alternative to Grunt for build running.
http://markgoodyear.com/2014/01/getting-started-with-gulp/
Gulp is an intuitive, code-over-configuration, streaming build system. It's fast.
Gulp uses node.js streams, making it faster to build as it doesn’t need to write temporary files/folders to disk.
Gulp allows you to input your source file(s), pipe them through a bunch of plugins and get an output at the end, rather than configuring each plugin with an input and output—like in Grunt.
Plugins are installed to run each build stage - e.g. sass, minify etc.
Videos: https://www.youtube.com/watch?v=DkRoa2LooNM&index=1&list=PLRk95HPmOM6PN-G1xyKj9q6ap_dc9Yckm&spfreload=10


### Jade - HTML Templating for node
http://jade-lang.com

### Browserify
Browserify lets you require('modules') in the browser by bundling up all of your dependencies.
http://browserify.org
It lets you run nodejs modules as clientside browser js.


## Activities
Create workspace and tree structure
create package.json file with { }
then install gulp as local dependency
npm install gulp --save-dev
This puts "devDependencies": {
  "gulp": "^3.8.10"
}
into package.json
