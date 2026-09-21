<div align="center">

# ☕ Advanced Java — Learning Notes

<p>A structured, hands-on documentation of my Advanced Java learning journey.<br/>
Notes · Code Snippets · Examples — organized topic by topic.</p>

![Java](https://img.shields.io/badge/Java-Advanced-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Progress-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---

## 🎬 Primary Reference

<a href="https://youtu.be/q6z_UCBM5Ek?si=MEJxOh5OvBUOcfYb">
  <img src="https://img.shields.io/badge/Watch%20on-YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
</a>

> 📺 **[Advanced Java Full Course — Telusko (Navin Reddy)](https://youtu.be/q6z_UCBM5Ek?si=MEJxOh5OvBUOcfYb)**
>
> This is the primary video I followed for this entire repository.  
> Every topic, folder, and note here maps directly to this course.

---

## 📚 Topics Covered

| # | Topic | Description | Status |
|:--|:------|:------------|:------:|
| 01 | [Maven](./01-maven/README.md) | Build automation & dependency management | 🔲 |
| 02 | [Gradle](./02-gradle/README.md) | Modern build system with Groovy/Kotlin DSL | 🔲 |
| 03 | [JDBC](./03-jdbc/README.md) | Java Database Connectivity API | 🔲 |
| 04 | [JUnit](./04-junit/README.md) | Unit testing with JUnit 5 / Jupiter | 🔲 |
| 05 | [Servlets](./05-servlets/README.md) | Java server-side web components | 🔲 |
| 06 | [JSP](./06-jsp/README.md) | JavaServer Pages & Expression Language | 🔲 |
| 07 | [REST API](./07-rest-api/README.md) | RESTful web service design & implementation | 🔲 |
| 08 | [WebSocket](./08-websocket/README.md) | Full-duplex real-time communication | 🔲 |
| 09 | [Hibernate](./09-hibernate/README.md) | ORM with Hibernate & JPA | 🔲 |

> **Progress Legend:** &nbsp; 🔲 Not Started &nbsp;·&nbsp; 🔄 In Progress &nbsp;·&nbsp; ✅ Completed

---

## 🗂️ Repository Structure

```
advanced-java/
│
├── 01-maven/
│   ├── basics/             # What is Maven, setup, first project
│   ├── project-structure/  # Standard layout, pom.xml overview
│   ├── dependencies/       # Adding deps, scopes, versioning
│   ├── lifecycle/          # Build phases explained
│   └── plugins/            # Compiler, Surefire, Jar plugins
│
├── 02-gradle/
│   ├── basics/             # Intro, installation, first build
│   ├── build-scripts/      # build.gradle, settings.gradle
│   ├── dependencies/       # Configs: implementation, testImpl
│   └── tasks/              # Built-in & custom tasks
│
├── 03-jdbc/
│   ├── connection/         # DriverManager, Connection, URL
│   ├── statements/         # Statement, executeQuery/Update
│   ├── prepared-statements/# Parameterized queries
│   ├── result-set/         # Iterating ResultSet
│   ├── crud/               # Full CRUD example
│   └── transactions/       # Commit, rollback, savepoints
│
├── 04-junit/
│   ├── basics/             # @Test, test classes
│   ├── assertions/         # assertEquals, assertThrows, etc.
│   ├── lifecycle/          # @BeforeEach, @AfterAll, etc.
│   ├── parameterized-tests/# @ParameterizedTest, @CsvSource
│   └── exception-testing/  # Expected exceptions
│
├── 05-servlets/
│   ├── basics/             # HttpServlet, doGet, doPost
│   ├── request-response/   # Request & Response objects
│   ├── request-parameters/ # getParameter, getParameterMap
│   ├── sessions/           # HttpSession management
│   ├── cookies/            # Create, read, delete cookies
│   ├── filters/            # Filter interface, FilterChain
│   └── listeners/          # Context & Session listeners
│
├── 06-jsp/
│   ├── basics/             # JSP lifecycle, first .jsp file
│   ├── expressions/        # Expression Language (EL)
│   ├── directives/         # page, include, taglib
│   ├── actions/            # jsp:include, jsp:forward
│   └── servlet-integration/# MVC: Servlet + JSP pattern
│
├── 07-rest-api/
│   ├── http/               # Methods, headers, status codes
│   ├── json/               # JSON format, Jackson/Gson
│   ├── endpoints/          # RESTful endpoint design
│   ├── request-response/   # Request/response body & headers
│   └── crud/               # Full REST CRUD example
│
├── 08-websocket/
│   ├── basics/             # WebSocket vs HTTP
│   ├── client-server/      # Java server, JS client
│   ├── messaging/          # Send & receive messages
│   └── chat/               # Real-time chat app
│
└── 09-hibernate/
    ├── configuration/      # hibernate.cfg.xml, SessionFactory
    ├── entities/           # @Entity, @Id, @Column
    ├── mappings/           # One-to-One, One-to-Many, etc.
    ├── crud/               # Session CRUD operations
    ├── relationships/      # Fetch & cascade types
    ├── hql/                # Hibernate Query Language
    └── transactions/       # Transaction management
```

---

## 🌐 Official Documentation

| Technology | Link |
|:-----------|:-----|
| ☕ Java SE (Oracle) | https://docs.oracle.com/en/java/ |
| 🏛️ Jakarta EE | https://jakarta.ee/specifications/ |
| 🔨 Apache Maven | https://maven.apache.org/guides/ |
| 🐘 Gradle | https://docs.gradle.org/ |
| 🗄️ JDBC Tutorial | https://docs.oracle.com/javase/tutorial/jdbc/ |
| 🧪 JUnit 5 | https://junit.org/junit5/docs/current/user-guide/ |
| 🏗️ Hibernate ORM | https://hibernate.org/orm/documentation/ |

---

## 🎥 Recommended YouTube Channels

| Channel | Best For |
|:--------|:---------|
| [Telusko](https://www.youtube.com/@Telusko) | Core & Advanced Java — clear and beginner-friendly |
| [Amigoscode](https://www.youtube.com/@amigoscode) | Spring Boot, REST APIs, Hibernate in depth |
| [Java Brains](https://www.youtube.com/@JavaBrainsChannel) | JEE, Spring framework deep dives |
| [Daily Code Buffer](https://www.youtube.com/@DailyCodeBuffer) | Spring Boot + Microservices projects |
| [in28minutes](https://www.youtube.com/@in28minutes) | Full Java + Spring ecosystem tutorials |

---

## 📖 Recommended Books

| Book | Author | Why Read It |
|:-----|:-------|:------------|
| *Effective Java* | Joshua Bloch | Best practices — a must-read for every Java dev |
| *Java: The Complete Reference* | Herbert Schildt | Comprehensive reference for the entire Java API |
| *Java Persistence with Hibernate* | Bauer & King | Deep dive into Hibernate & JPA internals |
| *RESTful Web Services* | Leonard Richardson | REST design principles done right |
| *Clean Code* | Robert C. Martin | Writing readable, maintainable Java code |

---

## 🏋️ Practice Platforms

| Platform | Focus |
|:---------|:------|
| [HackerRank — Java](https://www.hackerrank.com/domains/java) | Java-specific challenges, great for beginners |
| [LeetCode](https://leetcode.com) | DSA problems — Java solutions |
| [Exercism — Java Track](https://exercism.org/tracks/java) | Mentored exercises with community feedback |
| [Codewars](https://www.codewars.com/?language=java) | Fun kata-style Java challenges |

---

<div align="center">

*Personal learning log — notes and code are added progressively as I go through each topic.*

</div>
