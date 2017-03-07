# StereoCubeMapImporter

This is a fork of the [original StereoCubeMapImporter](https://github.com/opamp77/StereoCubeMapImporter) fixed to compile and work under UE4.15 

A simple stereo cubemap importer for displaying stereo cubemaps such as the ones availible [here](https://render.otoy.com/forum/viewforum.php?f=97)
within UE4.<br>
The Plugin take a pano stereo cubemap image splits it and generates two standard UE4 cubemaps.

## Installation and Use

Copy the StereoCubeMapImporter folder into /Plugins folder of your project.

To import a stereo cubemap simple click the new button in the editor.
![](http://i.imgur.com/i5P4DDn.png)


The Plugin will generate a standard ue4 cubemap for each each eye.
To uses the cube maps please check out StereoCubeMap_MAT and StereoCubeMap_PP_MAT within the plugin's content folder.
![](http://i.imgur.com/vNSmPXR.png)
