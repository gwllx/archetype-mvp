# Archetype MVP

A simple Minimum Viable *Project* archetype for Maven.

This archetype will generate a Java 21 project with JUnit 5 and Logback
dependencies, a Logback config file and a build step that creates a
self-contained executable JAR.

## Usage

This archetype is available in [Maven Central](https://central.sonatype.com/artifact/co.gwllx.maven/archetype-mvp). To generate a new project simply run:

```shell
mvn archetype:generate \
  -DarchetypeVersion=<version> \
  -DarchetypeGroupId=co.gwllx.maven \
  -DarchetypeArtifactId=archetype-mvp
```
