# JavaUpSkill Course — Learning Java Programming Language

This repository contains source code and exercises from the **JavaUpSkill Course**, focused on learning the fundamentals and core concepts of Java programming.

## Course Overview

- **Course Name:** JavaUpSkill Course
- **Subject:** Java Programming Language
- **Level:** Beginner to Intermediate
- **Objective:**
  To develop a strong foundation in Java programming, including syntax, OOP principles, data structures, and basic algorithms.

## Object-Oriented Programming (OOP)

This course emphasizes the four core principles of OOP in Java:

- **Encapsulation:** Bundling data and methods that operate on the data within classes, restricting direct access to some of an object's components.
- **Inheritance:** Creating new classes from existing ones, promoting code reuse and establishing hierarchical relationships.
- **Polymorphism:** The ability of different classes to be treated as instances of the same class through interfaces or inheritance, allowing methods to behave differently based on the object.
- **Abstraction:** Hiding complex implementation details and showing only the necessary features of an object.

These concepts are practiced throughout the course with examples and assignments.

## Tools & Environment

- **Java JDK** (version 8 or higher)
- **IDE:** Visual Studio Code with Java Extensions

## Run locally

Use JDK 8+ and optionally VS Code with the Java Extension Pack. The runnable sources are in `project1/src/`; each test/demo class has its own entry point.

```bash
git clone https://github.com/NiraphatK/java-upskill-course.git
cd java-upskill-course/project1
mkdir -p out
javac -d out src/*.java
java -cp out Main
```

On Windows, create the output directory with `mkdir out`; use VS Code's Java project view if your shell does not expand `src/*.java`.

For individual exercises, run a compiled demo such as `java -cp out TestDate` or `java -cp out TestInvoice`. `Main` and demo/test classes are executable examples, not a JUnit test suite. Open `project1/` in VS Code to run them from the editor.

The source includes customer/invoice/discount examples, student lists, and both traditional and modern date/time classes. No Maven or Gradle wrapper is included.
