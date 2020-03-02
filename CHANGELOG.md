# Version 2.1.0

* Added changelog file
* Changed maven-source-plugin in order to upload the test-sources additionally to the main sources
* Updated maven-jar-plugin to version 3.1.2
* Updated maven-surefire-plugin to version 3.0.0-M4
* Moved all plugin versions to properties in order to make overridable in projects
* Renamed version properties for test dependencies in order to make equal to plugin versions and increase readability:
  * junit.jupiter.version to version.junit.jupiter
  * jmockit.version to version.jmockit
* Added unchecked verifications during compilation