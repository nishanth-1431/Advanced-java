# Maven Terminology

Write a short definition and one example for each term.

| Term | My explanation | Example / notes |
|---|---|---|
| Project | The application or software being developed using Maven. | `simple-java-maven` |
| Artifact | A file produced or shared by a Maven project. | `simple-java-maven-1.0-SNAPSHOT.jar` |
| Coordinates | Values used to identify a Maven artifact. | `com.nishanth.maven:simple-java-maven:1.0-SNAPSHOT` |
| `groupId` | Identifies the project's group or namespace. | `com.nishanth.maven` |
| `artifactId` | The name used to identify the project artifact. | `simple-java-maven` |
| `version` | Identifies a particular version of the artifact. | `1.0-SNAPSHOT` |
| Packaging | Defines the type of artifact Maven builds. | `jar` or `war` |
| POM | The `pom.xml` file that contains project configuration and dependencies. | `pom.xml` |
| Dependency | An external library required by the project. | JUnit |
| Repository | A location where Maven stores or downloads artifacts. | Maven Central |
| Plugin | An extension that performs build tasks. | Maven Compiler Plugin |
| Goal | A specific task provided by a plugin. | `compiler:compile` |
| Lifecycle phase | A stage in Maven's build process. | `compile`, `test`, `package` |
| Local repository | A directory on your computer where Maven caches downloaded artifacts. | Usually `.m2/repository` inside your user directory |
| Transitive dependency | A library required by another dependency used by your project. | Library A requires Library B |

## Review Questions

1. How do Maven coordinates identify an artifact?
2. How is a plugin different from a dependency?
3. How is a goal different from a lifecycle phase?
4. What is the purpose of a repository?

## Key Takeaways

- [ ] I understand the main Maven terms.
- [ ] I can identify a project's coordinates in `pom.xml`.
- [ ] I understand the difference between dependencies and plugins.
- [ ] I can distinguish a plugin goal from a lifecycle phase.