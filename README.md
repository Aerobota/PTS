# Cesium Terrain Generator And Server (CTGAS)
CTGAS is a software that produces terrain data to be served primarily for [CesiumJS](cesiumjs.org) library.

CTGAS is written in Javascript just like Cesium itself. Cross platform and easy to install and use. 
As much as it is usable, there are lots of things to do so the source will be pending until it is ready to be released.

You can preview live demo [HERE](http://viskon.bilgem.tubitak.gov.tr/terrain/Test.html) (Data outdated for now, screenshots are more up to date)

You can get the source DEM data used for the showcase [HERE](http://naturalearth.springercarto.com/ne3_data/dem_large.zip)

Comments and inputs are quite welcome. You can follow progress from issues and here

## Showcases

![Quantized Mesh Rendered North America](https://dl.dropboxusercontent.com/s/qtuosbpvoxysghj/1.png?dl=0)
![Quantized Mesh Wireframe](https://dl.dropboxusercontent.com/s/i9i7996xu5fg28s/2.png?dl=0)
![Quantized Mesh Rendered South America](https://dl.dropboxusercontent.com/s/q8sy0retoobducb/3.png?dl=0)

## Features

CTGAS is usable at the moment as it is and have following features

1. **Heightmap** format terrain tile generation
2. **Quantized Mesh** format terrain tile generation
3. **KML** format terrain tile generation
4. **TIF** format terrain tile generation
3. Mesh Simplification Algorithm for tile generation
4. Multicore tile generation support
5. Tile Server in order to serve produced tiles


## TODO
1. Data source merge and updating (Generating and merging newly incoming data)
2. Extensions coding
3. Interface to manage application
4. Code refactoring

## FUTURE WORK

 Java and C++ porting of the software can be easily done. 
