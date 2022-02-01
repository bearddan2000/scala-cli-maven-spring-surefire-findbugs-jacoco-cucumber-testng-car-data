# scala-cli-maven-spring-surefire-findbugs-jacoco-cucumber-testng-car-data

## Description
A POC for spring app using testng
and cucumber framework with jacoco,
surefire, and findbugs plugins.

Analyze source code for potential bugs.

## Tech stack
- scala
- maven
	- findbugs
  - spring
  - testng
  - jacoco
  - surefire
  - cucumber

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
- [Parameter Type code base](https://thepracticaldeveloper.com/cucumber-guide-3-step-definitions-state/)
