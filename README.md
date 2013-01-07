gradle-lesscss-plugin
=====================
Gradle plugin for LESS CSS


Sample
------
There is a seperate GitHub repo [gradle-lesscss-sample](https://github.com/msgilligan/gradle-lesscss-sample) that contains a sample Gradle build using this plugin.  See the README.md file in that project for complete instructions on how to build, install, and use this plugin.

Installing
----------
Eventually you'll be able to install this (or another Gradle LESSCSS plugin) from a Maven repo, but for now you'll have to build it yourself and install into your local Maven repo:

    gradle install

Building
--------
    gradle build
    
Notes
-----
This plugin requires a download of less-rhino-1.x.x.js and the directly runs the Javascript file with Rhino.  See the sample gradle.build.

License
-------
Licensed under the terms of the Apache Software License 2.0

Acknowledgment(s)
-----------------
This plugin is based upon source code e-mailed to me (with Apache 2 license in the headers) by [Luke Daley](https://github.com/alkemist) on March 3, 2012.

Alternatives
------------
There is another Gradle LESS CSS Plugin on GitHub but it has no license, no documentation, an empty readme and has had no commits for 7 months:
https://github.com/koenongena/lesscss-gradle-plugin

This one uses lesscss-java: https://github.com/marceloverdijk/lesscss-java


