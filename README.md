
Open Undersea Cable Map
========================

This is a fork of [TeleGeography's](https://www.telegeography.com) submarine cable map from when it was last licensed under a Creative Commons license in late 2022. The map depicts active and planned submarine cable systems, their landing stations, cable length, ready for service (RFS) date, owners, suppliers, and website. Telegeography's up-to-date but now commercial map can be found at [https://www.submarinecablemap.com](https://www.submarinecablemap.com).


Installation
------------

Install a LTS version of [Node.js](https://nodejs.org/), [Yarn](https://yarnpkg.com/) for package management, and finally [RedwoodJS](https://redwoodjs.com/).

    $ git clone https://github.com/stevesong/open_undersea_cable_map.git
    $ cd open_undersea_cable_map
    $ yarn install
    $ yarn redwood dev

How did Telegeography make the Submarine Cable Map?
---------------------------------------------------

[TeleGeography](http://www.telegeography.com) draws the cable routes and plots the landing points with [Adobe Illustrator](https://www.adobe.com/products/illustrator.html). Using [Avenza's MAPublisher](https://www.avenza.com/mapublisher) plug-in, which works with Illustrator, two sets of data are exported as GeoJSON: the cable routes (as MultiLineStrings) and landing points (as Points).

This interactive map Javascript was created by Telegeography using the [RedwoodJS](https://redwoodjs.com/) web application framework.  The Javascript for the map was written in-house at TeleGeography.

How can I download the dataset?
--------------------------------------------------

__Undersea Cables:__

* [Undersea Cables GeoJSON](https://raw.githubusercontent.com/stevesong/open_undersea_cable_map/main/web/public/api/v3/cable/cable-geo.json)
* [Undersea Cable Data](https://github.com/stevesong/open_undersea_cable_map/tree/main/web/public/api/v3/cable)

__Landing Points:__

* [Landing Point GeoJSON](https://raw.githubusercontent.com/stevesong/open_undersea_cable_map/main/web/public/api/v3/landing-point/landing-point-geo.json)
* [Landing Point Data](https://github.com/stevesong/open_undersea_cable_map/tree/main/web/public/api/v3/landing-point)


License
------------------------

This map and underlying data was originally made available under the [Creative Commons License: Attribution-NonCommercial-ShareAlike 3.0 Unported (CC BY-NC-SA 3.0)](https://creativecommons.org/licenses/by-nc-sa/3.0/) and is re-published here under the same.


Questions? Corrections?
------------------------
[Steve Song](https://manypossibilities.net/contact/)

For more information on Telegeography's [Submarine Cable Map](https://www.submarinecablemap.com/) contact [cablemap@telegeography.com](mailto:cablemap@telegeography.com)
