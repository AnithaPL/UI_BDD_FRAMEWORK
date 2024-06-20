# BDDFRAMEWORK_UI
# Overview
UI_BDD_FRAMEWORK is a Java-based test automation framework designed for UI testing using Behavior Driven Development (BDD). The framework leverages popular tools such as Selenium, Cucumber, TestNG, and various logging libraries to facilitate robust and maintainable test automation.

# Features
**Selenium**: For browser automation.
**Cucumber**: For BDD-style test cases.
**TestNG**: For test execution and reporting.
**Lombok**: For reducing boilerplate code.
**Log4j & SLF4J**: For logging and debugging.
**WebDriverManager**: For managing WebDriver binaries.
**Profiles for Parallel and Sequential Test Execution**: Maven profiles for running tests in parallel or sequentially.

# Project Structure
UI_BDD_FRAMEWORK/
├── src/
│   ├── main/
│   └── test/
├── .classpath
├── .gitignore
├── .project
├── pom.xml
└── README.md

# Getting Started
# Prerequisites
Java 8 or higher
Maven 3.6.0 or higher

# Installation
Clone the repository:
git clone https://github.com/your-username/UI_BDD_FRAMEWORK.git
Navigate to the project directory:
cd UI_BDD_FRAMEWORK
Install dependencies:
mvn clean install

# Usage:  Running Tests
# Parallel Execution 
**To run tests in parallel:**
mvn verify -PParallel-cucumber-runner
# Sequential Execution
**To run tests sequentially:**
mvn verify -PSequential-cucumber-runner
# Maven Profiles
The project includes two Maven profiles for running tests:
**Parallel-cucumber-runner**: Runs tests in parallel.
**Sequential-cucumber-runner:** Runs tests sequentially.
Dependencies
The main dependencies used in this project are:

**Selenium: 4.14.1
Cucumber: 7.3.4
Lombok: 1.18.30
Log4j: 2.21.0
SLF4J: 2.0.9
WebDriverManager: 5.5.3
json-smart: 2.4.10**

For a full list of dependencies, refer to the **pom.xml** file.

