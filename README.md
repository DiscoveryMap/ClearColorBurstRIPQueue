ClearColorBurstRIPQueue
=======================
by Morgan Aldridge <morgant@makkintosshu.com> under contract by [Discovery Map International](https://discoverymap.com/)

OVERVIEW
--------

A utility to automatically delete jobs older than N days from  the queue for the [ColorBurst Overdrive](http://www.overdriverip.com/overdrive-mac.html) RIP running on macOS. 

USAGE
-----

`ClearColorBurstRIPQueue` accepts a single parameter, the number of days after which to delete jobs from the queue. It can be run manually, e.g. `ClearColorBurstRIPQueue 5`, or automatically using the supplied `launchd` LaunchAgent script. If using the LaunchAgent, you'll need to edit it to adjust for your installation path, number command line argument (i.e. days parameter), etc., then put it in your `~/Library/LaunchAgents/` folder and log out & in (or unload & load it using `launchctl`).

LICENSE
-------

Copyright (c) 2017 Discovery Map International. All rights reserved.

