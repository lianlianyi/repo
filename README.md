# repo

仓库地址
https://raw.githubusercontent.com/lianlianyi/repo/master/repository/

# maven-repo
My personal maven repository.

clean deploy -DaltDeploymentRepository=internal.repo::default::file:D:\git\repo -Drelease=true

## Usage
pom.xml:
```xml
    <repositories>
        <repository>
            <id>hengyunabc-maven-repo</id>
            <url>https://raw.githubusercontent.com/lianlianyi/repo/master/repository/</url>
        </repository>
    </repositories>
```
