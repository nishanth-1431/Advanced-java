# Installing Maven on Windows

## 1. Prerequisites

Before installing Maven, make sure the JDK is installed and working. Download the Maven binary distribution from the official [Apache Maven website](https://maven.apache.org/download.cgi).

## 2. Installation Steps

1. Run `java -version` to check Java.
2. Run `javac -version` to check the Java compiler.
3. Download and extract the Maven binary ZIP file.
4. Set `JAVA_HOME` to your JDK installation directory.
5. Optionally set `MAVEN_HOME` to your Maven installation directory.
6. Add Maven's `bin` folder to the Windows `Path` variable.
7. Open a new terminal and run:

   ```bash
   mvn -version
   ```

If Maven is installed correctly, the command displays the Maven version, Java version, and Maven home directory.

## 3. Troubleshooting

- **`mvn` is not recognized:** Check that Maven's `bin` folder is added to `Path`.
- **Invalid `JAVA_HOME`:** Make sure it points to the JDK folder, not its `bin` folder.
- **Old environment variables:** Close and reopen the terminal after making changes.

## 4. Review Questions

1. Why does Maven need Java?
2. What is the purpose of `PATH`?
3. What information does `mvn -version` display?

## Key Takeaways

- [ ] Java and Maven are installed.
- [ ] `JAVA_HOME` and `Path` are configured correctly.
- [ ] `mvn -version` runs successfully.