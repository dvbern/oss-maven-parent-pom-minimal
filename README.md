# DV Bern minimal parent pom
This pom is inteded to provide a minimal configuration for maven projects.

Mostly it defines plugin versions (via properties) **in pluginManagement**
for all [default plugins](https://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html#Built-in_Lifecycle_Bindings)
of the ["clean" and "default" lifecycle](https://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html#Lifecycle_Reference)
used by "pom" and "jar" packaging.


In addition, (and to comply to company standards), the following additional configuration is made:
* Configure deployment to DVB Nexus
* Configure jgitflow
* Configure static code analysis (spotbugs, pmd, checkstyle plugins)
* Add sources.jar
* Add default entries to META-INF/MANIFEST.MF
* Configure [maven-enforcer-plugin](http://maven.apache.org/enforcer/maven-enforcer-plugin/) when releasing.
