# mvn-repo
A simple Maven repository for hosting EOMasters artifacts

To use artifacts of this repository in your project add it to your Maven pom.xml as follows:

```xml
<project>
    ...
    <repositories>
        <repository>
            <id>mvn-repo</id>
            <url>https://raw.githubusercontent.com/eomasters-repos/mvn-repo/main/</url>
            <releases>
              <enabled>true</enabled>
            </releases>
            <snapshots>
              <enabled>true</enabled>
            </snapshots>
        </repository>
    </repositories>
    ...
</project>
```

The repository has been set up by following this guide:
[Using GitHub as a Maven Repository - DZone](https://dzone.com/articles/using-github-as-maven-repository)