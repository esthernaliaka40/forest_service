## App-Name

Forest-Service

## Project Description

Forest-Service App is an App that allows Rangers to track Animal sightings in the area.
Each time an animal species of either category is seen, a Sighting must be reported.

When wildlife is spotted, a Ranger submits a form to record a Sighting containing the following:id, Animal, Endangered Species, Location and Ranger name.

## Author's Information

This project was developed by Esther Naliaka.

## Set Up Instructions-Data Base Setup Instructions

- Run psql in the project terminal.
- Type the command: CREATE DATABASE wildlife_tracker;
- Navigate into the database by typing the command: \c wildlife_tracker;
  Create tables by running following commands:
- 1.CREATE TABLE RangerAnimal (id serial PRIMARY KEY, name VARC
  HAR, tag INT, phone INT, email VARCHAR);
- 2.CREATE TABLE Wildlife (id serial PRIMARY KEY, name VARCHAR,health VARCHAR, age VARCHAR);
- 3.CREATE TABLE EndangeredAnimal(id serial PRIMARY KEY, name VARCHAR, health VARCHAR, age VARCHAR);
- 4.CREATE TABLE AnimalLocation (id serial PRIMARY KEY, name VARCHAR);
- 5.CREATE TABLE AnimalSighting (id SERIAL PRIMARY KEY, animalId INT, rangerId INT, locationId INT, time TIMESTAMP);
- Create a test database by typing the command: CREATE DATABASE wildlife_tracker_test WITH TEMPLATE wildlife_tracker;

### To set up this project:
- Clone the repository by executing the following command in your terminal in the directory of your choice - git clone https://github.com/esthernaliaka40/forest_service.git
- Navigate into the Forest-Service directory - cd Forest-Service
- Build project
- Build
- Run gradle build to build the project.

## Live Link
https://esthernaliaka40.github.io/forest_service

## Technologies Used:
- Java.
- Spark.
- Gradle.
- Maven.
- Bootstrap.
- JUnit.

## Contact Information
- Email : esthernaliaka40@gmail.com
- Phone : +254 720543896

## Copy Right and License Information
Copyright (c) 2022 Esther Naliaka