# crypto-maven-archetype
Personal base maven archetype for building crypto-related projects.

<h4>Usage:</h4>

1. Download the directory from GitHub

2. Change directory
```
cd crypto-maven-archetype
```

3. Install the maven archetype
```
mvn install
```

4. Generate new projects using the archetype
```
mvn archetype:generate                    \
  -DarchetypeGroupId=com.crypto           \
  -DarchetypeArtifactId=base-archetype    \
  -DarchetypeVersion=1.0-SNAPSHOT         \
  -DgroupId=<my.groupid>                  \
  -DartifactId=<my-artifactId>
```
