Location API
=========

Applications use the RESTful Terminal Location interface to get a location for an individual terminal or a group of terminals; to get the distance of the terminal from a specific location; and to start and stop notifications, based on geographic location or on a periodic interval.

Version
----

6

Usage
----

Follow this steps:

+ Request your credentials on the [Oracle's TADHack website](http://tadhack.optaresolutions.com).
+ Download the source code:

```sh
git clone https://github.com/OTADHack/Location.git
cd Location
```
+ In [SoapUI 5.0 or above](http://www.soapui.org/), go to File -> Import project and choose the file Location/SoapUI/API-Terminal-Location-soapui-project.xml
+ Double click on Request 1 of the Service http://ocsg60.optaresolutions.com:8001
+ In the Request Properties box, change Username and Password with the credentials requested in the first step.
+ Click on the green arrow of the Request 1 window.
+ Done! Your first location request is done!

Documentation
----

All the documentation can be found in the [Oracle's TADHack website](http://tadhack.optaresolutions.com/?page_id=94).


Support
----

If you have any doubt, ask it in [the Issues section](https://github.com/OTADHack/Location/issues).

License
----

Copyright © 2007, 2015, Oracle and/or its affiliates. All rights reserved. Usage only allowed for TADHack Developers.
