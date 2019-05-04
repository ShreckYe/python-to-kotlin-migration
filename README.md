# Python-to-Kotlin Migration
A guide on migration from Python to Kotlin (for JVM) mainly for data processing tasks
## Introduction
### Why I wrote this guide
Python is the most widely used tool for data processing and analysis tasks, but it is born with the disadvantages in speed and memory efficiency. As data grows larger, Python becomes more and more incapable of handling it efficiently and within the specified amount of memory. Therefore, it's necessary to migrate to another language or platform to solve this problem. This journey from experimentation to practice, from academia to industry, is not easy for those without a CS background. C++ is indeed too difficult for most Python users (nevermind if you are a C++ profossional) and Java is too redundant compared to Python's simplicity. The new programming language [Kotlin](https://kotlinlang.org/) is a perfect choice, with its concise syntax being similar to Python's and its efficiency being almost identical to Java. By migrating to Kotlin, one can also enjoy the huge number of libraries in Java, and it's also easy to take a further step to true industrial frameworks like Java, Hadoop, and Spark, etc.
## Basic conceptual differences
### Types, classes, and objects
## Migration guide
### IDE migration
PyCharm to IntelliJ IDEA
### Syntax migration
#### Delcaring variables
##### `val` and `var`
##### Naming conventions
#### Control
##### Branches (if, else if, and else)
##### Loops
###### for
###### while and do-while
#### Functional programming
### Environment migration
#### Files
#### Network
### Library migration
#### NumPy to primitive arrays
#### NumPy linear algebra to ND4J (or LA4J, or Apache Commons Math, or EJML)
#### pandas to Apache Commons CSV
#### SymPy to Apache Commons Math
#### OkHttp
#### Efficient primitive collections
Eclipse Collections and GNU Trove
