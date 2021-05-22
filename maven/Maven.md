## Maven
Maven is a powerful project management tool that is based on POM (project object model). It is used for projects build, dependency and documentation.
| **Name**          |**Description**                                                             |
|-------------------| ---------------------------------------------------------------------------|
| Build Life Cycles | Default, Clean and Site                                                    |
| Build Phases      | Validate, Compile, Test, Package, Install and Deploy                       |
| Build Goals       | A specific task that contributes to the building and managing of a project |

## Advantages
1. Generates source code and its documentation.
2. Compiles and package source code.
3. Installs the packaged code in local repository, server repository, or central repository.
4. It makes a project easy to build.
5. It provides uniform build process.
6. Isolation between project dependencies and plugins.

## Maven Repository
1. Local Repository
2. Central Repository
3. Remote Repository

## Maven Command
| **Command**                      |**Description**                                                |
|----------------------------------| --------------------------------------------------------------|
| mvn clean                        | Cleans by deleting the target directory                       |
| mvn compiler:compile/testCompile | Compiles the java source/test classes                         |
| mvn package                      | Builds and packages into a JAR, WAR, etc.                     |
| mvn install                      | Builds and installs the project files to the local repository |
| mvn deploy                       | Deploy artifact to the remote repository                      |
| mvn archetype:generate           | Generate a skeleton maven project of different types          |
| mvn site:site                    | Generates a site for the project                              |
| mvn test                         | To run the test cases                                         |
| mvn compile                      | To compile the source Java classes                            |
| mvn verify                       | Run check-ups to verify the package and meets criteria        |

## Maven Options
| **Option**            |**Description**                          |
|-----------------------| ----------------------------------------|
| mvn -help             | Prints all the available options to use |
| mvn -f                | Build from a different location         |
| mvn -o                | Run in offline mode                     |
| mvn -q                | Run in quiet mode                       |
| mvn -X package        | Run in debug mode                       |
| mvn -DskipTests       | Skip running tests                      |
| mvn -Dcheckstyle.skip | Skip checkstyle check                   |

## Sample XML
```xml
<project xmlns="http://maven.apache.org/POM/4.0.0"   
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"  
  xsi:schemaLocation="http://maven.apache.org/POM/4.0.0   
http://maven.apache.org/xsd/maven-4.0.0.xsd">
  <modelVersion>4.0.0</modelVersion>
  <groupId>com.maven.demo</groupId>  
  <artifactId>maven-demo</artifactId>  
  <version>1.0</version>  
  <packaging>jar</packaging>  
  <name>Maven Demo</name>  
  <url>http://maven.apache.org</url>  
  <dependencies>  
    <dependency>  
      <groupId>junit</groupId>  
      <artifactId>junit</artifactId>  
      <version>4.8.2</version>  
      <scope>test</scope>  
    </dependency>  
  </dependencies>  
</project>  
```
