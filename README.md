AfterStep Classic 1.1b3 08/27/2023
-----------------------
AfterStep Classic is based on Afterstep v1.1b2. This a configuration based on FVWM. Or more simply put, it is a configuration for FVWM 2.6.x, but it is meant to be the next version AfterStep Classic.
-----------------------

Changes since last release since beta 2 released 03/08/97:

* Now based on FVWM 2.6.x. It may work on earlier versions, such as 2.5.x but not tested. It should also work on fvwm3, but also untested.

* Emulates AfterStep 1.x series as closely as possible.

* No more steprc, now its fvwm2rc

Regressions:

* The root menu isn't very AfterStep Classic-ish. I don't use the root menu that much so its not a high priority.

* No gradients. If you like them, submit a pull request.

* Minimized icons have a space between them. This may be a limitation of FVWM.

* Libreoffice sometimes obeys IconOverride, sometimes it doesn't.

* You'll need wmclock for the Wharf, if you don't want it, you can use xclock instead:
*Wharf(Swallow XClock 'Exec xclock -padding 0 -bg Grey75 -fg black &')

* If you to want to break off and pin the root menu ala Window Maker add this to AfterStepClassic menu:
"+			"Pin Menu" TearMenuOff	"
-------------------------

AfterStep Classic, like the original , is released under the GNU GPL Version 2 or, at your option, any later version.

Icons are from the original AfterStep Classic tarball.
Libreoffice icon from the Gnustep Icons package: https://www.gnome-look.org/p/1239539/
Window Decor is from the NeXTishFish Sawfish Theme: https://sawfish.fandom.com/wiki/NeXTishFish
-------------------------

Author:
Chris Turkel jct3003@yahoo.com

Original authors:
Frank Fejes frank@ssax.com
Alfredo Kenji Kojima kojima@inf.ufrgs.br
Dan Weeks dan@mango.sfasu.edu
