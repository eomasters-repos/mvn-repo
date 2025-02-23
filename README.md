# mvn-repo
A simple Maven repository for hosting EOMasters artifacts

To use artifacts of this repository in your project add it to your Maven pom.xml as follows:

```xml
<project>
    ...
    <repositories>
        <repository>
            <id>mvn-repo</id>
            <url>https://github.com/eomasters-repos/mvn-repo/raw/refs/heads/main/</url>
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

How to setup such a repository is described in this blog:
[Homemade Public Maven Repository](https://www.eomasters.org/post/homemade-public-maven-repository)
