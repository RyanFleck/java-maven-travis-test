# Maven Test
Simple Maven project with Travis CI

[![Build Status](https://travis-ci.com/RyanFleck/java-maven-travis-test.svg?branch=master)](https://travis-ci.com/RyanFleck/java-maven-travis-test)

> If your project has pom.xml file in the repository root but no build.gradle, Travis CI builds your project with Maven 3.

```bash
# Compile to target, then run:
mvn package 
java -cp maven-test-01-1.0-SNAPSHOT.jar com.rcf.app.App

# Compile application sources:
mvn compile

# Remove target:
mvn clean

# Compile sources and run unit tests:
mvn test
```

Adding dependencies requires adding text to `pom.xml`.
```xml
<!-- https://mvnrepository.com/artifact/org.dom4j/dom4j -->
<dependency>
    <groupId>org.dom4j</groupId>
    <artifactId>dom4j</artifactId>
    <version>2.1.1</version>
</dependency>
```

**Resources:**

1. <https://docs.travis-ci.com/user/languages/java/>
2. <https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html>
3. <https://www.ahundredanswers.com/insights/maven-is-a-tool-every-java-developer-should-embrace>
4. <https://maven.apache.org/guides/mini/guide-configuring-maven.html>
5. <https://maven.apache.org/guides/getting-started/index.html#What_is_Maven>

