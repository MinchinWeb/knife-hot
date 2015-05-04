Knife Hot
=========


Table of Contents
-----------------

+ Synopsis / Introduction
+ Code Example (Screen Shots)
+ Motivation
+ Features
+ Installation
+ Usage
+ (Run) Tests
+ Contributing
+ History
+ References
+ Credits / Contributors
+ License


Introduction
------------

*Knife Hot* is a project to control my furnace remotely. This repo contains the
Python code, and is run on my end on a Raspberry Pi 2. It aims to significantly
expand on the functionality of the mercury-based thermostat it is replacing.
Once up and running, all configuration and reporting is done via a website.


Screen Shots
------------

TODO


Motivation
----------

I live in a climate where the summers are generally mild enough that air
conditioning (AC) is generally not installed in homes. When outside temperatures
get warmer (over, say 30C) in summer, the answer is the open up the windows at
night and let in the cooler outside air during the night, and then close up the
windows during the day. Summer evenings tend to be very calm, and so some sort
of mechanical venilation is require for this to be effective. Furnaces are
equiped with a 'summer switch' that just turns on the furnance fan (with no
heat) to easily allow this.

My current thermostat is an old-school mercury bimetalic style. It works well
in winter, but the biggest limitation is it can't run the fan directly.

I considered something like a Nest, but the hope is this will be a little
cheaper, more functionable, and not require rewiring.

As the project advances, I hope to make use of controlling the fan to move
evenly heat the house in winter, provide a 'schedule' function for heating,
and use the fan to help prevent the air in the house from going 'stale'.


Features
--------

 - user-configuraable swing (0.5C)
 - let furnace run for a minimum time, once switched on (3 min)
 - scheduled heating setting
 - run humidifier, based on outside temperature


Installation
------------

Nothing to install...yet


Usage
-----

TODO


Running Tests
-------------

No tests yet :(


Contributing
------------

Please feel free to submit a pull request on Github.


History
-------

 - 2015-04-26 -- first commit!


References
----------

### Similar Projects

 - [Makeatronics](http://makeatronics.blogspot.ca) (2013) -- possible PCB source
     - thermostat code -- <http://makeatronics.blogspot.ca/2013/04/thermostat-software.html>
 - [Rubustat](http://wyattwinters.com/rubustat-the-raspberry-pi-thermostat.html) (2013)
     - Linux demaon -- <http://www.jejik.com/articles/2007/02/a_simple_unix_linux_daemon_in_python/> (note seperate download for Python 3) -- alt link <http://blog.jacobean.net/?p=692>
     - code - <https://github.com/wywin/Rubustat>
     - improved code - <https://github.com/aneisch/Rubustat>
 - [Nooganeer](http://www.nooganeer.com/his/projects/homeautomation/raspberry-pi-thermostat-part-1-overview/) (2014)

### Furnace Wiring

### Readme Template

 - <https://gist.github.com/jxson/1784669>

### Possible Other Names

 - DryIce


Credits
-------

*Knife Hot* is copyright (C) 2015 by Wm. Minchin.


License
-------

TODO
