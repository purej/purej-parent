<h1><img src="https://cloud.githubusercontent.com/assets/13910123/9427455/ac87593c-497e-11e5-806c-beac4cc50ae3.png"/> purej-parent</h1>

The Maven parent POM for <b>com.purej</b> projects. This POM specifies the versions of commonly used Maven plugins and applies the following non-standard configurations:

* compiler-plugin: explicit JDK version, show warnings
* jar-plugin: add implementation manifest entries

The following plugins are automatically executed:
* source-plugin: to produce a -sources.jar
* javadoc-plugin: to produce a -javadoc.jar
* enforcer-plugin: to prevent conflicting transitive dependencies
* gpg-plugin: to automatically sign generated artefacts (required by Maven Central)
