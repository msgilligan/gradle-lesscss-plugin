gradle-lesscss-plugin
=====================
Gradle plugin to compile .less files to CSS with [LESS](http://lesscss.org) CSS pre-processor.

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
This plugin requires a download of less-rhino-1.x.x.js and then directly runs the Javascript file with Rhino.  See `gradle.build` in the [sample project](https://github.com/msgilligan/gradle-lesscss-sample).

TO DO
-----
1. Update to more recent LESS
1. Publish to a public Maven repo (who can help with this?)
1. Use [lesscss-java](https://github.com/marceloverdijk/lesscss-java)
1. More complete sample project ([Bootstrap](http://twitter.github.com/bootstrap/) demo?)
1. [Spock](http://code.google.com/p/spock/) unit tests

Longer term possibilities
--------------------------
1. Run LESS under [Nashorn](http://openjdk.java.net/projects/nashorn/)?
1. Use Native [less4j](https://github.com/SomMeri/less4j) ?
1. Integration with [Grails resource plugin](http://grails.org/plugin/resources)?  (How would that work?)

License
-------
Licensed under the terms of the [Apache Software License 2.0](http://www.apache.org/licenses/LICENSE-2.0).

Acknowledgment(s)
-----------------
This plugin is based upon source code e-mailed to me (with Apache 2 license in the headers) by [Luke Daley](https://github.com/alkemist) on March 3, 2012.

Alternatives
------------
When I created this repository there was only one other Gradle LESS CSS plugin out there.  Now there are a handful.

* [gradle-less-plugin](https://bitbucket.org/davidmc24/gradle-less-plugin/) davidmc24 Bitbucket

    Engine: [lesscss-java](https://github.com//lesscss-gradle-plugin)

    License: ASL 2.0

    Published: Bintray

* [gradle-lesscss-plugin](https://github.com/obecker/gradle-lesscss-plugin) obecker github

    Engine: Rhino + less-rhino-1.3.3.js

    License: ASL 2.0

    Published: Maven Central

* [gradle-less-plugin](https://github.com/skhome/gradle-less-plugin) skhome github

    Engine: lesscss-java

    License: WTFPL

    Not Published

* [lesscss-gradle-plugin](https://github.com/koenongena/lesscss-gradle-plugin) koenongena github

    Engine: lesscss-java

    License: ?

    Not Published

