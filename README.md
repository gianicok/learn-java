# Learning Java

Notes taken while learning Java. I used these tutorials;

- https://docs.oracle.com/javase/tutorial/getStarted/application/index.html

## Running a Java Program
```bash
java -cp . .\filename.java
```
## Automatic Documentation in Java
```bash
javadoc .\filename.java
```
## Class Names

To define a public class in Java, you need to ensure the classname matches the filename. For example,
```Java
/** Filename: helloworld.java */

public class helloworld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```