# Project 1: Realtional Algebra Operators

This project contains various operators of relational algebra implemented in Java 8. Completed for CSCIX370 Database Management at the Univsersity of Georgia.

In the project the relational algebra operators are demonstrated on a database of movie details. Therefore the code was given by the instructor except the operators select, project, union, minus, equijoin and natural join were left to code. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

This project uses Java 8. You will need to have the JDK 1.8 installed.


### Installing

The Java [JDK 1.8](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) has to be downloaded from the Oracle homepage and installed.

To confirm that it is installed run 'java -version'. It should out put:

```
java version "1.8.0_201"
```

## Compilation 

To compile the program the following classes are needed: 
* ArrayUtil
* KeyType
* MovieDB
* Table

On a Unix bash shell, the command to compile is as follows:
"$ javac MovieBD.java Table.java" or simply "$ javac *.java" when in the project directory.

The class MovieDB is the main class.


## Running the tests

The program can be tested by running the main class 'MovieDB'. If the operators work the output table show the correct result.
To run the program run the following command:
"$ java MovieDB"

## Built With

* [IntelliJ](https://www.jetbrains.com/idea/) - IDE


## Versioning

We use [Git](https://git-scm.com/) for versioning.

## Authors

* **Caleb Crumley** - *Equijoin and natural join*
* **Max Aaron Strauss** - *Select and project* 
* **Alexander Stein** - *Union and minus* 

## Annotations

* The operators union and minus assume that the columns of the tables are in the same order
* The project operator uses the remaining attributes as new primary key and removes duplicates.
* The select operator returns AT MOST one tuple.

## Acknowledgments

* The code framework was distributed by John Miller
