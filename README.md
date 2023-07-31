# MavenCenter

## url
```text
Gitee: https://gitee.com/ed3/maven-center/raw/master/repository/
github: https://raw.githubusercontent.com/ed-3/maven-center/master/repository/
cdn: https://cdn.jsdelivr.net/gh/ed-3/maven-center/repository
```

```groovy
// gradle
repositories {
    //...
    maven {
        url = 'https://gitee.com/ed3/maven-center/raw/master/repository/'
    }
    //...
}
```

```xml
<!--maven pom-->
<repositories>
    <!--...-->
    <repository>
        <id>ed333-maven</id>
        <url>https://gitee.com/ed3/maven-center/raw/master/repository/</url>
    </repository>
    <!--...-->
</repositories>
```