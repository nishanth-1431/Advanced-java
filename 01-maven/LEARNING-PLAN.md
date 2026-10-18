# Maven Learning Plan

## Study method

Use the course videos as the primary sequence, but practise in the order below so that each topic builds on the previous one. Do not just copy definitions: run commands and write observations.

## Phase 1 — Foundations

- [ ] What Maven is
- [ ] Why build tools are useful
- [ ] What Maven automates: compiling, testing, packaging, dependency resolution
- [ ] Maven, JDK, and `JAVA_HOME`
- [ ] Install and verify Maven on Windows with `mvn -version`
- [ ] Record the installed Maven and Java versions

**Completion check:** Explain what happens when you run a Maven command and distinguish Maven from the JDK.

## Phase 2 — First project and terminology

- [ ] Create a simple Java Maven project on Windows
- [ ] Explore the standard directory layout
- [ ] Learn `groupId`, `artifactId`, `version`, and `packaging`
- [ ] Understand the `pom.xml`
- [ ] Run the application and inspect generated output
- [ ] Learn Maven terminology: project, artifact, coordinates, repository, dependency, plugin, goal, phase

**Completion check:** Create a project from scratch and explain its main files and directories.

## Phase 3 — POM, dependencies, and repositories

- [ ] Read the basic POM structure
- [ ] Learn Maven properties and Java compiler configuration
- [ ] Add one external dependency
- [ ] Understand local, central/remote, and project repositories
- [ ] Learn transitive dependencies and dependency scopes
- [ ] Inspect the effective POM

**Completion check:** Add a dependency, build successfully, and explain where Maven obtains the library.

## Phase 4 — Goals, lifecycle, and plugins

- [ ] Understand the difference between a goal and a lifecycle phase
- [ ] Practise `mvn validate`
- [ ] Practise `mvn compile`
- [ ] Practise `mvn test`
- [ ] Practise `mvn package`
- [ ] Practise `mvn clean`
- [ ] Practise `mvn install`
- [ ] Identify which plugins execute during common lifecycle phases

**Completion check:** Explain why `mvn package` runs earlier phases and identify the output artifact.

## Phase 5 — Testing

- [ ] Add a test dependency
- [ ] Write a small unit test
- [ ] Run tests with `mvn test`
- [ ] Intentionally make a test fail and read the report
- [ ] Understand the role of the Maven Surefire Plugin
- [ ] Review JUnit basics

**Completion check:** Run at least one passing test and explain how to find a failing test's report.

## Phase 6 — Applications and tools

- [ ] Create a simple web application and understand WAR packaging at a high level
- [ ] Create a Spring Boot project using Maven
- [ ] Open/build a Maven project in the chosen IDE
- [ ] Learn the basic purpose of Gradle and compare it with Maven
- [ ] Optional: repeat project creation on AWS EC2 after local Maven is comfortable

**Completion check:** Build a small Maven-based application and explain how its dependencies, tests, and packaging work.

## Definition of done

A phase is complete when I can:
1. Explain the concept without reading the notes.
2. Demonstrate it with a command, configuration, or small project.
3. Record the result and any troubleshooting.
4. Answer the review questions.
5. Commit the work with a descriptive Git message.
