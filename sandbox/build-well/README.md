<span style=display:none; >[You are now in a GitHub source code view - click this link to view Read Me file as a web page]( http://ladybug-tools.github.io/spider/#sandbox/build-well/README.md "View file as a web page." ) </span>


[Build Well Read Me]( #README.md )
====
_A well for building well._

<iframe class=iframeReadMe src=http://ladybug-tools.github.io/spider/sandbox/build-well/index.html width=100% height=600px onload=this.contentWindow.controls.enableZoom=false; ></iframe>

## Full Screen: [Build Well]( http://ladybug-tools.github.io/spider/sandbox/build-well/index.html )



## To Do

* 2017-09-20 ~ Update size of grid

## Change Log


### 2017-09-20 ~ Theo

* 14:56 ~  Start R2
* Rebuilding in 'everything is a recipe' style. Using mnu-template & test-threejs basic
* 16:15 ~ 'Site Context' looking good
* 17:47 ~ adjacent buildings,html looking good
* 22:23 ~ Geometry.html is working
* 22:56 ~ Currently three separate standalone scripts
	* Makes testing and coding and understanding what's going on a bit easier
	* Currently the data is not shared between the scripts. The liaison should happen in the next release
* Also coming soon will the internal walls, adjusting window sizes and the different shapes
 
### 2017-09-18 

### Buildings Menu

* Three buildings created by default
	* Add and delete buildings: future release
* Save file
	* Saves buildings as a single 3D object
	* All data stored in the 3D models
	* File format is standard Three.js JSON
	* Seems to be working just fine
	* Many more options will become available
* Open file
	* Works barely OK
	* Building data fields are updated but edits do yet update geometry
	* L Shape models not being loaded. Try using JSON loader instead of Object loader

### Site Context Menu

* When played with after a fresh reload, mostly works just fine
* Needs error-checking and more user entry safeguards
* As mentioned above, editing is broken when opening a file


### Geometry Menu

* Mostly unfinished, only a few items work
	* Changing floor height updates some of the other fields
	* Footprint shape draws a partially parameterized L Shape - very badly
* A work in progress


### 2017-09-17 ~ Theo

* First commit