# JVM Library Template
Template I'm using for the libraries published to Maven artifactory.
It contains Github Actions with build and publish tasks to Github Packages and to Bintray.

*What must be changed when creating new library:*
* [settings.gradle.kts](settings.gradle.kts) - name of the project
* [build.gradle.kts](build.gradle.kts) - description and names:
```kotlin
// ------------------------------------ Deployment Configuration  ------------------------------------
val githubRepository = "LukasForst/maven-library"
val descriptionForPackage = "Template repository for maven libary"
val tags = arrayOf("kotlin", "Gradle", "Maven library")
```
