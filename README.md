# E-Commerce Selenium Automation Framework

## Overview
A robust, scalable test automation framework for e-commerce web applications 
built with Selenium WebDriver, TestNG, and Java following Page Object Model design.

## Tech Stack
- Java | Selenium WebDriver | TestNG | Maven
- Apache POI (Data-driven testing)
- Selenium Grid + Docker (Parallel execution)
- Jenkins (CI/CD)
- Extent Reports + Log4j2

## Framework Architecture
- Page Object Model (POM)
- Data-driven testing via Excel
- Config-driven setup (local + remote)
- Parallel cross-browser execution

## How to Run
```bash
mvn test -Dbrowser=chrome
mvn test -Dsuite=regression
```

## Reports
Extent Reports generated at `/reports/index.html` after each run.
