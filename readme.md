[![Build Status](https://travis-ci.org/RutledgePaulV/maven-archetype.svg?branch=develop)](https://travis-ci.org/RutledgePaulV/maven-archetype)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.rutledgepaulv/maven-archetype/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.rutledgepaulv/maven-archetype)

## Maven-Archetype
A maven archetype to handle all the bootstrapping for a new com.github.rutledgepaulv Java based project.


#### Usage
```bash
mvn archetype:generate \
  -DarchetypeGroupId=com.github.rutledgepaulv \
  -DarchetypeArtifactId=maven-archetype \
  -DarchetypeVersion=1.0 \
  -DgroupId=com.github.rutledgepaulv \
  -DartifactId=<project-name>
```


#### Release Versions
```xml
<dependencies>
    <dependency>
        <groupId>com.github.rutledgepaulv</groupId>
        <artifactId>maven-archetype</artifactId>
        <version>1.0</version>
    </dependency>
</dependencies>
```

#### Snapshot Versions
```xml
<dependencies>
    <dependency>
      <groupId>com.github.rutledgepaulv</groupId>
      <artifactId>maven-archetype</artifactId>
      <version>1.1-SNAPSHOT</version>
    </dependency>
</dependencies>

<repositories>
    <repository>
        <id>ossrh</id>
        <name>Repository for snapshots</name>
        <url>https://oss.sonatype.org/content/repositories/snapshots</url>
        <snapshots>
            <enabled>true</enabled>
        </snapshots>
    </repository>
</repositories>
```

### License

This project is licensed under [MIT license](http://opensource.org/licenses/MIT).
