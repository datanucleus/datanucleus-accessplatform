datanucleus-accessplatform
==========================

DataNucleus AccessPlatform packaging project.

Release of AccessPlatform zip distributions :
* Update the details of jars in build.properties, in particular the versions required
* "ant archive" -> creates the archive zips under "target"

Build of AccessPlatform Maven pom artifacts is achieved by invoking `mvn clean install`.
Release of AccessPlatform Maven pom artifacts is achieved by invoking `mvn clean release:clean release:prepare release:perform`.
