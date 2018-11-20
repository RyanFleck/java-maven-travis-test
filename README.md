# Maven Test
Simple Maven project with Travis CI

[![Build Status](https://travis-ci.com/RyanFleck/java-maven-travis-test.svg?branch=master)](https://travis-ci.com/RyanFleck/java-maven-travis-test)

> If your project has pom.xml file in the repository root but no build.gradle, Travis CI builds your project with Maven 3.

<https://docs.travis-ci.com/user/languages/java/>


```bash
mvn package
java -cp maven-test-01-1.0-SNAPSHOT.jar com.rcf.app.App
```