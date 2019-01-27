# Project 1: Realtional Algebra Operators

This project contains various operators of relational algebra implemented in Java 8. Completed vor CSCIX370 Database Management at the Univsersity of Georgia.

In the project the relational algebra operators are demonstrated on a database of movie details. Therefore the code was given by the instructor except the operators select, project, union, minus, equijoin and natural join were left to code. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

This project uses Java 8. You will need to have the JDK 1.8 installed.


### Installing

The Java JDK 1.8 has to be downloaded from the Oracle homepage and installed.

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

The program can be tested by running the main class 'MovieDB'. If the operators work the output table show the correct result. 

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [IntelliJ](https://www.jetbrains.com/idea/) - IDE

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Caleb Crumley** - *Equijoin and natural join*
* **Max Aaron Strauss** - *Select and project* 
* **Alexander Stein** - *Union and minus* 

## Annotations

* The operators union and minus assume that the columns of the tables are in the same order
* The project operator uses the remaining attributes as new primary key and removes duplicates.
* etc

## Acknowledgments

* The code framework was distributed by John Miller
* The class ArrayList was made by Oracle 