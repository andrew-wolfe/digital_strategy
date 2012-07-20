Digital Strategy Drupal Module
===========================================

Creates 3 page nodes for digital strategy progess on enable. Also creates menu callbacks which load the page nodes and output just the body with the appropriate content type headers.

Goals
----------

In order to generate a Gov't wide report to show all agencies progress toward meeting the Gov't Digital Strategy each agency is required to provide easy access to their report in 3 machine-readble formats (xml, json, and jsonp).

Requirements
------------

* Drupal 6.x
* Path module enabled

Usage
-----

Place the module in the /sites/all/modules directory of your Drupal installation and enable it in the admin UI.

How it Works
------------

When the module is enabled (.install file) 3 page nodes are created: digital-strategy/progress-xml, digital-strategy/progress-json, digital-strategy/progress-jsonp. Menu callback items are created, digital-strategy/xml, digital-strategy/json, and digital-strategy/jsonp in the .module file.

These urls provide the progress reports without the theme and with the correct content type headers.

Contributing
------------

Federal employees and members of the public are encouraged to contribue to the project by forking and submitting a pull request. All code must be licensed to the public under GPLv2 or later.

License
-------

This project constitutes a work of the United States Government and is not subject to domestic copyright protection under 17 USC § 105. 

The project utilizes code licensed under the terms of the GNU General Public License and therefore is licensed under GPL v2 or later.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.