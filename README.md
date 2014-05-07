This is a temporary Maven repository for Arcus Java client.

arcus-java-client repo:  
https://github.com/naver/arcus-java-client

Include the following to your POM file to fetch the Mavan artifact.

```xml
<repositories>
    <repository>
        <id>arcus-java-client-repo</id>
        <url>https://raw.github.com/naver/arcus-java-client-repo/master/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
```

