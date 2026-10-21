# Introduction to Maven

## What is Maven?
Apache Maven is a build automation tool mainly used for Java projects. It helps manage dependencies, compile code, run tests, and package applications.

Maven uses `pom.xml` (Project Object Model) to define project details, dependencies, plugins, and build settings.

## Why use Maven?
- **Build automation:** Compile, test, and package projects with commands.
- **Dependency management:** Download and manage required libraries.
- **Standard structure:** Keeps source code, resources, and tests organized.
- **Consistent builds:** Lets developers use the same project configuration and commands.

## Common Maven commands

```bash
mvn compile
mvn test
mvn package
```

- `mvn compile` — compiles the application source code.
- `mvn test` — runs configured tests.
- `mvn package` — packages the project, usually as a JAR or WAR.

## How Maven works
1. Reads the `pom.xml`.
2. Resolves required dependencies and plugins.
3. Runs the requested build lifecycle phases.
4. Compiles code, runs configured tests, and packages the application.
5. Places generated output in the `target/` directory.

## Important terms

| Term | Meaning |
|---|---|
| POM | Maven project configuration file (`pom.xml`) |
| Dependency | A library the project needs |
| Repository | A place Maven stores or downloads artifacts |
| Plugin | A tool that performs a build task |
| Goal | A specific task provided by a plugin |
| Lifecycle phase | A stage in the build process |
| Artifact | A packaged output, such as a JAR or WAR |

## Maven vs JDK
The **JDK** provides Java development tools, including the compiler (`javac`). **Maven** organizes the build process and can use those tools through plugins. Maven does not replace the JDK.

## Quick practice
Try these commands in a valid Maven project:

```bash
mvn compile
mvn test
mvn package
```

Check the `target/` folder for generated files. Note that packaging an application does not automatically run its `main` method.

## Key takeaway
Maven makes Java projects easier to build and maintain by handling dependencies and coordinating compilation, testing, and packaging through a shared configuration.
