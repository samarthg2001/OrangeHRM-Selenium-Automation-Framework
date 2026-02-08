# OrangeHRM-Selenium-Automation-Framework
OrangeHRM Selenium Automation Framework

End-to-End Selenium Automation for OrangeHRM Web Application using Java, TestNG & Extent Reports

🔹 Project Overview

This project demonstrates a real-time, industry-level Selenium automation framework for the OrangeHRM Demo Site
. It covers end-to-end login, dashboard verification, and admin module functionalities, 
The framework is built using Java, Selenium WebDriver, TestNG, and Maven, and follows Page Object Model (POM) for maintainability and scalability.

🔹 Features

✅ Automated valid login and invalid login scenarios

✅ End-to-end dashboard verification and logout

✅ Page Object Model (POM) for clean and reusable code

✅ Explicit waits for dynamic element handling

✅ TestNG framework with XML suite configuration

✅ Extent Reports for detailed execution reports

✅ Screenshots captured for failed test cases

✅ Maven project structure with configurable properties


🔹 Project Structure
OrangeHRM-Automation/
│
├── pom.xml
├── src/test/java
│   ├── base           -> Browser setup/teardown
│   ├── pages          -> Page Object classes (Login, Dashboard, Admin)
│   ├── tests          -> Test classes (LoginTest, InvalidLoginTest)
│   ├── utils          -> ConfigReader, ScreenshotUtils, ExtentManager
│   └── listeners      -> TestNG listener for reports & screenshots
├── src/test/resources
│   ├── config.properties
│   ├── testng.xml
│   └── extent-config.xml
└── reports            -> Extent HTML reports and screenshots

🔹 Tech Stack

Java – Core language for automation

Selenium WebDriver – Web automation

TestNG – Test framework and test suite management

Maven – Dependency and build management

GitHub – Version control

🔹 How to Run

Clone the repository:

git clone https://github.com/yourusername/OrangeHRM-Automation.git


Navigate to the project folder:

cd OrangeHRM-Automation


Update config.properties if needed (username, password, browser)

Run tests via TestNG XML in your IDE or command line

mvn test


Open reports/ExtentReport.html to view the execution results

🔹 Future Enhancements

Add data-driven tests using Excel/CSV

Add parallel execution

Integrate with Jenkins CI/CD

Add Admin module automation and other OrangeHRM modules
