# Debugging a Java Web App using Tomcat and Visual Studio Code

[![Debugging Video Tutorial](https://img.youtube.com/vi/xxxx/0.jpg)](https://www.youtube.com/watch?v=xxxx)


## Project Configuration 
| Setting | Value |
| --- | --- |
| Purpose | Debug a Java web app using Tomcat and VS Code |
| Server | Java |
| Server Language | Java |
| Architecture | Maven |
| IDE | Visual Studio Code |
| License | GPL v3 |
| Tutorial | [Youtube Tutorial](https://www.youtube.com/watch?v=xxxxx |


## Visual Studio Code Extensions
This project uses Java, Tomcat and Maven. Install the Java Extension pack to get the Java features needed. And Install the Tomcat for Java extension too.

1. Install [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=adashen.vscode-tomcat)
2. Install [Tomcat for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)


## Init Reference

### Generate a Web App
I created a Maven architecture web app project. It's much easier to manage the dependencies and build instructions for the IDE and CI systems with something like Maven. 

1. Run this to generate a maven web app project. 
```
mvn org.apache.maven.plugins:maven-archetype-plugin:3.1.2:generate -DarchetypeArtifactId="maven-archetype-webapp" -DarchetypeGroupId="org.apache.maven.archetypes" -DarchetypeVersion="1.4"
```

2. Add the default Java source directory ./src/main/java
3. Add the initial package directory. For example com.brandondonnelson would become ./src/main/java/com/brandondonnelson



