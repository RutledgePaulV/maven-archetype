[![Build Status](https://travis-ci.org/RutledgePaulV/${artifactId}.svg?branch=develop)](https://travis-ci.org/RutledgePaulV/${artifactId})
[![Coverage Status](https://coveralls.io/repos/github/RutledgePaulV/${artifactId}/badge.svg?branch=develop)](https://coveralls.io/github/RutledgePaulV/${artifactId}?branch=develop)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.rutledgepaulv/${artifactId}/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.rutledgepaulv/${artifactId})

## ${artifactId}


#### Release Versions
```xml
<dependencies>
    <dependency>
        <groupId>${groupId}</groupId>
        <artifactId>${artifactId}</artifactId>
        <version>${version}</version>
    </dependency>
</dependencies>
```

#### Snapshot Versions
```xml
<dependencies>
    <dependency>
        <groupId>${groupId}</groupId>
        <artifactId>${artifactId}</artifactId>
        <version>${version}</version>
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
