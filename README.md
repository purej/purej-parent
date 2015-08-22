The Maven parent POM for <b>com.purej</b> projects. This POM specifies the versions of commonly used Maven plugins and applies the following non-standard configurations:

<ul>
<li>compiler-plugin: explicit JDK version, show warnings</li>
<li>jar-plugin: add implementation manifest entries</li>
</ul>

The following plugins are automatically executed:
<ul>
<li>source-plugin: to produce a -sources.jar</li>
<li>javadoc-plugin: to produce a -javadoc.jar</li>
<li>enforcer-plugin: to prevent conflicting transitive dependencies</li>
<li>gpg-plugin: to automatically sign generated artefacts (required by maven central)</li>
</ul>
