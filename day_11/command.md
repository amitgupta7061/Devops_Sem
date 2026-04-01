# Maven Build Automation Concepts and Commands

## 1. Creating a new Maven Project using Archetypes
```bash
# Generate a simple Java project
mvn archetype:generate -DgroupId=com.example -DartifactId=demo-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```

## 2. Standard Directory Setup created by Maven
- `src/main/java` - Application/Library sources
- `src/test/java` - Test sources
- `pom.xml` - Configuration, build instructions, and dependency management

## 3. Core Maven Commands

```bash
# Clean the project (removes the target folder)
mvn clean

# Compile the source code
mvn compile

# Compile the test source code
mvn test-compile

# Run unit tests
mvn test

# Package the compiled code in its distributable format (e.g., JAR)
mvn package

# Install the package into the local repository for use as a dependency in other projects
mvn install
```

## 4. Useful Utility Commands
```bash
# Validate the project is correct and all necessary information is available
mvn validate

# Print the resolved dependencies tree
mvn dependency:tree
```