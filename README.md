js-plugins
==========

A number of [JS plugins](http://www.reaper.fm/sdk/js/js.php) for [Reaper](http://reaper.fm/), mostly for work on ambisonic B-format signals. Most of the effects for transformations of ambisonic sound fields are ports of UGens from Ambisonics Toolkit (ATK) for SuperCollider [1].

Please note that these plugins are still in an early phase of development and subject to change with respect to names, interfaces, etc.

Download and install:
---------------------

* Download plugins by hitting the zip button at [GitHub](https://github.com/lossius/js-plugins)
* Unzip the resulting folder. You might want to rename it "trond-lossius-js-plugins" or something similar
* On Mac, open the folder `~/Library/Application Support/REAPER/Effects`. In OSX 10.8 the Library folder might be hidden. If so, in Finder, hold down the ALT key while clicking the "Go" menu. This will cause the Library folder to show up as one of the folders in the menu.
* On Windows you'll have to copy the unzipped folder in a similar way.
* Copy the unzipped folder to the Effects folder, and (re)start Reaper.

Changelog
---------

* 2013-04-23: Getting licenses, copyrights and credits right (hopefully...) :-)
* 2013-04-19: Adding plugins for horisontal and vertical zooming and domination of Bformat signals. Renamed plugins for ambisonic rotations so that they are more clearly grouped.
* 2013-04-18: Adding plugins for conversion between stereo and mid-side. Also adding several plugins for horisontal and vertical manipulation of Bformat signals: adjustment of directivity, focus, press and push.
* 2013-04-02: Initial commit of 6 modules for encoding mono and stereo sources as 1st order Bformat, and for pitch, roll and yaw manipulations of Bformat signals.

Licenses and credits
--------------------

Plugins developed by Trond Lossius are (c) Trond Lossius 2013 and licensed according to the new BSD license. Several of these are based on [2].

Effects ported from Ambisonics Toolkit (ATK) for SuperCollider are (c) the ATK Community, Joseph Anderson, and Josh Parmenter, 2011, and licensed according to the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.



References:
-----------

[1] http://www.ambisonictoolkit.net/

[2] Malham, Dave (1998): Spatial Hearing Mechanisms and Sound Reproduction. Available online at http://www.york.ac.uk/inst/mustech/3d_audio/ambis2.htm