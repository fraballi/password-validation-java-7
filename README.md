# Password Validation [Passay / JDK 7]

### Dependencies
> - Java 7
> - Passay 1.1.0    
> - JUnit 4    


### Minimun password requirements
> - At least 8 chars length
> - At least 1 digit
> - At least one Upper Case char
> - At least one Lower Case char
> - At least one Special char
> - At least one symbol char


# Maven
``` xml
    <dependencies>
        <dependency>
            <groupId>org.passay</groupId>
            <artifactId>passay</artifactId>
            <version>1.1.0</version>
        </dependency>
        <dependency>
            <groupId>junit</groupId>
            <artifactId>junit</artifactId>
            <version>4.12</version>
            <scope>test</scope>
        </dependency>
    </dependencies>

```