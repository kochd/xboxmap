# xboxmap
xboxmap is a easy to use and preconfigured wrapper for remapping the xboxdrv. It makes it possible to play games that have zero or broken controller configuration.
It does so by mapping keyboard and mouse actions to the gamepad using xboxdrv.
# Prerequisites
You'll need xboxdrv and ruby

* Debian: `apt-get install xboxdrv ruby`

# Usage
<pre>
steam@steambox:~/xboxmap$ ./xboxmap --help
Usage:
	 xboxmap FILEPATH 	 Use FILEPATH as configfile
	 xboxmap NAME 		 Use NAME as configfile as located in gameconfigs ( without extension )
</pre>

You can either provide the path to a gameconfig or use the name of the file inside the gameconfigs dir. e.g `./xboxmap amongthesleep` will load the amongthesleep.yaml

You'll also find a config.yaml after the first start of xboxmap which contrains various options.  

# Contributions & Missing games
If you have any problems or miss a game feel free to contact me. 
If you want to contribute the format is quiete easy to understand see [generic.yaml](https://github.com/kochd/xboxmap/blob/master/gameconfigs/generic.yaml) for example as it maps all keys.
