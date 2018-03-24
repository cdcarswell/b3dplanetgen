# b3dplanetgen

*b3dplanetgen* is an in-development collection of Blender resources that streamlines the creation of planetary objects, with the main goal of it being easy to use, highly customizable, and fairly modular.

These resources are stored in a single .blend file that contains the necessary objects and shaders needed for the creation of the planet.

![preview image](https://cdcarswell.files.wordpress.com/2018/03/planet1.png?w=500&h=&crop=1)

### Table of Contents
**[Installation](#installation)**<br>
**[Usage](#usage)**<br>
**[Details](#details)**<br>
**[Compatibility](#compatibility)**<br>
**[Finished Works](#Works)**<br>
**[Feedback, License](#feedback)**<br>

## Installation

Go to the [__Releases__](https://github.com/cdcarswell/b3dplanetgen/releases) page and download one of the latest versions.

Once you have downloaded the .blend file, simply open it with Blender v2.78 or later.

## Usage

This is a quick usage guide to get you started with b3dplanetgen. Please check the [tutorial](https://github.com/cdcarswell/b3dplanetgen/wiki/Tutorial) on how to use this resource, or check the [wiki](https://github.com/cdcarswell/b3dplanetgen/wiki) for more in-depth information.

1. Select in the *Outliner* an object to modify (Planet Surface, Planet Clouds, or Planet Atmosphere).

![planetobjects](https://cdcarswell.files.wordpress.com/2018/03/planetlayers.png)

2. Go to the *Node Editor* and you will find a node group with various settings allowing for the customizable of the planetary object.

![planetshader](https://cdcarswell.files.wordpress.com/2018/03/b3dplanetgen.png?w=370&h=)

3. I know there's a lot of settings, but start playing around with the values to see which combinations work. If these inputs don't seem intuitive, check the wiki (in development) for more details on what each slider does.

4. Once you're done, render the image (or animation) and save the result, if you want.

## Details

b3dplanetgen uses node groups to create the planet surface, clouds, and atmosphere. Inside these node groups is a large network of procedural texture nodes that are mixed and combined in certain ways to create the overall material. For the surface shader, a heightmap is generated using these procedural nodes and the sphere is displaced using microdisplacement to achieve more realism and detail. Colors are computed based on the relative heights of the generated heightmap. Five colors are used for this purpose (with Color 1 being the lowest height and Color 5 being the highest peaks).

## Compatibility

b3dplanetgen was created in Blender 2.79 and is compatible with version 2.78 or later. It is possible to use with prior versions, but please note that displacement will not work.

## Feedback

Please feel free to comment and report issues, comments, bugs, and any feature requests/changes you may have.

[Report issue](https://github.com/cdcarswell/b3dplanetgen/issues).

You can also reach me on Twitter at https://twitter.com/thecdcarswell

## Works
If you managed to create something interesting or cool with this resource, please feel free to share it! Be sure to mention "b3dplanetgen" or use the hashtag #b3dplanetgen so people can find it easily.

## License

This project and all resources inside it is licensed under Creative Commons Attribution 4.0 International (CC BY 4.0): https://creativecommons.org/licenses/by/4.0/

If you distribute or modify this project, remember to provide proper attribution by mentioning me, the original author (CD Carswell).

For rendered works created with this resource, I highly recommend you mention somewhere (in post body, video description, etc.) that you used this resource (b3dplanetgen) in the creation of the render. It helps get the word out, and if you found the resource useful, it'll give others a chance to find and use it as well.
If you really don't want to provide attribution for your rendered works, you don't absolutely have to (but please do).
