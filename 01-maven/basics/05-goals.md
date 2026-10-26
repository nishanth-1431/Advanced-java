# Maven Goals

## Definition

A **Maven goal** is a specific task performed by a Maven plugin. Plugins provide goals for tasks such as compiling Java code, running tests, and creating JAR files.

For example, `compiler:compile` invokes the `compile` goal of the Maven Compiler Plugin.

## Goals to Investigate

| Command / Goal | What it does | What I observed |
|---|---|---|
| `help:effective-pom` | Displays the effective POM after Maven combines project configuration, parent POMs, and applicable defaults. | Shows the final POM configuration Maven uses. |
| `compiler:compile` | Compiles the main Java source files. | Compiled `.class` files appear under `target/classes`. |
| `surefire:test` | Runs tests using the Maven Surefire Plugin. | Test results are displayed in the terminal and reports are generated under `target/surefire-reports`. |
| `clean:clean` | Removes generated build output. | The `target` directory is normally deleted. |

*Note: The observations above describe typical results. Run each command in your project to verify them.*

## Goal vs Lifecycle Phase

A **goal** is a specific task provided by a plugin, while a **lifecycle phase** is a named stage in Maven's build process that can coordinate one or more goals.

Examples:

- **Goal:** `compiler:compile` compiles the main Java source code.
- **Lifecycle phase:** `package` runs the preceding phases in the default lifecycle before packaging the project into its artifact.

A goal can be invoked directly, while running a lifecycle phase executes the goals bound to that phase and the earlier phases in its lifecycle.

## Practical Activity

- [ ] Run one goal directly: `mvn compiler:compile`
- [ ] Run one lifecycle phase: `mvn package`
- [ ] Compare the output and explain the difference.

## Review Questions

1. What is a Maven goal?
2. Which component provides goals?
3. Can a goal be invoked directly?
4. How is a goal different from `package`?

## Key Takeaways

- [ ] I understand what a Maven goal is.
- [ ] I can identify the plugin that provides a goal.
- [ ] I understand the difference between a goal and a lifecycle phase.
- [ ] I have executed a goal and a lifecycle phase in my project.