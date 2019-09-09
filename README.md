js-plugins
==========

An incomplete and failry arbitrary set of [JS plugins](http://www.reaper.fm/sdk/js/js.php) for [Reaper](http://reaper.fm/), developed mostly for my own use.

Download and install:
---------------------

* Download plugins by hitting the zip button at [GitHub](https://github.com/lossius/js-plugins)
* Unzip the resulting folder. You might want to rename it "lossius-js-plugins" or something similar
* On Mac, open the folder `~/Library/Application Support/REAPER/Effects`. In OSX 10.8 and later the Library folder might be hidden. If so, in Finder, hold down the ALT key while clicking the "Go" menu. This will cause the Library folder to show up as one of the folders in the menu.
* On Windows you'll have to copy the unzipped folder in a similar way.
* Copy the unzipped folder to the Effects folder, and (re)start Reaper.
* Several plugins depends on [coocdsp](http://ajaxsoundstudio.com/software/cookdsp/). Please ensure that you have that library installed as well.

Changelog
---------

* 2019-09-09: Adding classes and effects for 4 channel linked and unlinked granular delay
* 2018-12-02: Adding helper effects that can be used for parallel 4 channel processing
* 2017-02-25: Adding ping-pong delay
* 2016-06-12: Adding graphics library with a KnobMan-based GUI slider widget. Adding 4 channel 6 band EQ.
* 2016-01-06: This library now depends on the awesome [coocdsp](http://ajaxsoundstudio.com/software/cookdsp/).
* 2015-11-01: Repurposing this repo for general JSFX plugins. Ambisonic plugins are now maintained as [Ambisonic Toolkit for Reaper](http://www.ambisonictoolkit.net).


Licenses and credits
--------------------

Plugins are licensed according to the new BSD license.