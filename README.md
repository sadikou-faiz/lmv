 #Documentation2

[![Code Quality](https://img.shields.io/badge/Code%20Quality-A-brightgreen)](https://app.codacy.com/gh/sadikou-faiz/lmv/dashboard?branch=Developpement)

[![build](https://github.com/sadikou-faiz/lmv/actions/workflows/maven.yml/badge.svg?branch=Developpement)](https://github.com/sadikou-faiz/lmv/actions/workflows/maven.yml)

[![Download Latest Artifact](https://img.shields.io/badge/Download-Latest%20Artifact-blue.svg)](https://github.com/sadikou-faiz/lmv/actions/workflows/maven.yml/artifacts)


## Introduction

LoveMyPet is an initiative born out of a profound ambition: to simplify the process of pet adoption while ensuring their well-being. Through our web application, we aim to connect those who wish to give their pets with those who desire to adopt a faithful companion.

Upon completion of the adoption process, LoveMyPet is dedicated to educating future pet owners. We aspire to promote the best care practices. Join us on this journey to give every animal the opportunity to find a loving home.

## Prerequisites 

**Java:** LoveMyPet is developed using Java. Make sure to have Java installed on your machine.

**Maven:** We use Maven as a dependency and build manager. Ensure that Maven is installed.

**Spring Boot:** LoveMyPet is built on the Spring Boot framework. Make sure to have Spring Boot installed.

**JaCoCo:** JaCoCo is utilized for code coverage analysis. Ensure that JaCoCo is integrated into your development environment.

**MySQL:** LoveMyPet relies on MySQL for data storage. Ensure MySQL is installed and configured.

## Installation 

To install LoveMyPet, you have two options:

1. **Install from the Source Code using Git:**
   - Clone the repository: `git clone https://github.com/malek62-info/LoveMyPet.git`
   - Compile the project with Maven: Use the command `mvn clean install` in the cloned project directory.

Or,

2. **Download the Zip File:**
   1. Go to [https://github.com/malek62-info/LoveMyPet](https://github.com/malek62-info/LoveMyPet)
   2. Click on the latest workflow run.
   3. Scroll down the page and click on **my-artifact**.

## Configuration

In the project directory, navigate to **classes**, then open **application.properties**, and change the following two lines:

```
spring.datasource.username=username
spring.datasource.password=password
```
Update them using your MySQL username and password.

## Launch 

After successfully installing LoveMyPet, launch the application:

1. **Execute the JAR file:**
   - Run the JAR file with the command: `java -jar file.jar`, replacing `file.jar` with the actual name of the JAR file.

2. **In your browser, go to:**
   - Open your browser and visit [http://localhost:8081/Calcule](http://localhost:8081/Calcule) to display our homepage.
