# Public Maven Repository
This GitHub "project" is being used as a Maven repository, especially for
jars that we're using from projects that don't have public a Maven
repository.

# Usage
From Gradle:

```
    mavenRepo name: 'xydo_public', urls: [ "https://github.com/gravit/public_mvn_repo/raw/master/releases" ]
```

The Maven equivalent should be something along the lines of:

```
    <repository>
      <id>public-releases</id>
        <url>https://github.com/kevinpollet/maven-repository/raw/master/releases</url>
    </repository>
```
