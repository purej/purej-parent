<h1><img src="https://cloud.githubusercontent.com/assets/13910123/9427455/ac87593c-497e-11e5-806c-beac4cc50ae3.png"/> purej-parent</h1>

The Maven parent POM for <b>com.purej</b> projects. This POM specifies the versions of commonly used Maven plugins and applies the following non-standard configurations:

* compiler-plugin: configurable JDK version, show warnings
* jar/war: add implementation manifest entries automatically
* jar: add automatic-module-name for java 11 / jigsaw support

The following plugins are automatically executed:
* source-plugin: to produce a -sources.jar
* javadoc-plugin: to produce a -javadoc.jar
* enforcer-plugin: to prevent conflicting transitive dependencies
* gpg-plugin: to automatically sign generated artefacts (required by Maven Central)
* central-publishing-maven-plugin: to upload artefacts to maven-central (https://central.sonatype.com)
