[![Build Status](https://travis-ci.org/RutledgePaulV/maven-archetype.svg?branch=develop)](https://travis-ci.org/RutledgePaulV/maven-archetype)
[![Coverage Status](https://coveralls.io/repos/github/RutledgePaulV/maven-archetype/badge.svg?branch=develop)](https://coveralls.io/github/RutledgePaulV/maven-archetype?branch=develop)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.rutledgepaulv/maven-archetype/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.rutledgepaulv/maven-archetype)

## Maven-Archetype
A maven archetype to handle all the bootstrapping for a new com.github.rutledgepaulv
Java based project.

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
      <version>1.1</version>
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
