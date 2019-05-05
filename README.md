# Python-to-Kotlin Migration
A guide on migration from Python to Kotlin (for JVM) mainly for data processing tasks
## Introduction
### Why I wrote this guide
Python is the most widely used tool for data processing and analysis tasks, but it is born with the disadvantages in speed and memory efficiency. As data grows larger, Python becomes more and more incapable of handling it efficiently and within the specified amount of memory. Therefore, it's necessary to migrate to another language or platform to solve this problem. This journey from experimentation to practice, from academia to industry, from small data to big data, is not easy for those without a CS background. C++ is indeed too difficult for most Python users (nevermind if you are a C++ profossional) and the Java syntax is too redundant compared to Python's simplicity. The new programming language [Kotlin](https://kotlinlang.org/) is a perfect choice, with its concise syntax being similar to Python's and its efficiency being almost identical to Java. By migrating to Kotlin, one can also enjoy the huge number of libraries in Java, and it's also easy to take a further step onto true industrial frameworks like Java, Hadoop, Spark, and MapReduce, etc.

## Basic conceptual differences
### Types, classes, and objects

## Migration guide
### IDE migration
PyCharm to IntelliJ IDEA

### Syntax migration
#### Delcaring variables
##### `val` and `var`
##### Naming conventions

#### Code blocks (add braces)

#### Control
##### Branches (if, else if, and else)
##### Loops
###### for
###### while and do-while

#### Basic data structures
##### Lists
##### Tuples to pairs, triples, data classes, or arrays/lists
##### Dictionaries to maps

#### Functional programming
##### filter
##### map and list comprehension
##### Other functional programming extension functions

### Environment migration
#### Files
#### Network

### Library migration
#### NumPy to primitive arrays
#### NumPy linear algebra to ND4J (or LA4J, or Apache Commons Math, or EJML)
#### pandas to Apache Commons CSV and Apache POI
#### SymPy to Apache Commons Math
#### OkHttp
#### Efficient primitive collections
Eclipse Collections and GNU Trove
