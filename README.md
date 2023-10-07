# java-cli-maven-postgresql-data-type-json

## Description
Creates a small table `dog` that uses
a json data type.

A java maven build, that connects to postgresql database.

## Tech stack
- java
- maven
  - log4j
  - postgresql drivers

## Docker stack
- postgresql:alpine
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[JSON data type info](https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-json/)
