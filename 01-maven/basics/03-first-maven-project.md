# Creating the First Maven Project

## 1. Goal

Create a simple Java application using Maven and understand how Maven generates the project, compiles the code, runs tests, and packages the application.

## 2. Project Coordinates

- **groupId:** `com.nishanth.maven`
- **artifactId:** `simple-java-maven`
- **version:** `1.0-SNAPSHOT`
- **packaging:** `jar`

These values identify the project and determine how Maven names and packages its output.

## 3. Creating the Project

Maven can generate a project from a template called an **archetype**. The Quickstart archetype creates a basic Java project with a `pom.xml`, source code, and test code.

Example command for Windows PowerShell:

```powershell
mvn archetype:generate "-DarchetypeGroupId=org.apache.maven.archetypes" "-DarchetypeArtifactId=maven-archetype-quickstart" "-DarchetypeVersion=1.5" "-DgroupId=com.nishanth.maven" "-DartifactId=simple-java-maven" "-DinteractiveMode=false"
```

Run the command from the directory where you want the project folder to be created.

## 4. Project Structure

- `pom.xml` — contains project configuration and dependencies.
- `src/main/java` — contains application source code.
- `src/test/java` — contains test source code.
- `target/` — contains generated build output.

Maven follows this standard structure so developers can work with projects consistently.

## 5. Building the Project

```powershell
mvn compile
mvn test
mvn package
```

- `mvn compile` compiles the application source code.
- `mvn test` runs the configured tests.
- `mvn package` builds the configured package, such as a JAR.

The generated artifact is normally available inside `target/`.

To remove generated build output, use:

```powershell
mvn clean
```

## 6. Running the Application

Packaging a JAR does not automatically make it executable with `java -jar`. That requires the appropriate manifest and application configuration.

For this first project, run the class containing the `main` method through your IDE, or configure a suitable Maven plugin to run it.

## 7. Observations

- Maven generates the initial project structure from the archetype.
- The application and test source files can be edited manually.
- Compilation errors prevent a successful build.
- The JAR is a build artifact.
- Generated files in `target/` should normally not be committed to Git.

## 8. Review Questions

1. What is the purpose of `src/main/java`?
2. What does the `target/` directory contain?
3. What is an artifact in Maven?
4. Why should generated build output normally be excluded from Git?
5. What is a Maven archetype?

## Key Takeaways

- [ ] I can generate a Maven project.
- [ ] I understand the basic Maven directory structure.
- [ ] I can compile, test, package, and clean a project.
- [ ] I can identify the generated JAR artifact.