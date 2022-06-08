# MavenCenter

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