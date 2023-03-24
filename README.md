# swagger-demo-mvn

```
    <repositories>
        <repository>
            <id>swagger-demo-mvn-git</id>
            <url>https://raw.github.com/grace788/swagger-demo-mvn/main</url>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
    </repositories>
    <dependencyManagement>
        <dependencies>

          <dependency>
              <groupId>io.swagger</groupId>
              <artifactId>swagger-java-client</artifactId>
              <version>1.0.0</version>
           <dependency>
        <dependencies>
    <dependencyManagement>
```   

```
repositories {
    maven {
        url 'https://raw.github.com/grace788/swagger-demo-mvn/main'
    }
}

dependencies {
    implementation 'io.swagger:swagger-java-client:1.0.0'
}
```
        
