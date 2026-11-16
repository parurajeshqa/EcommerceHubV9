EcommerceHubV9
🚀 Selenium Automation Testing Framework | Java | TestNG | Maven
<p align="center">
<img src="https://img.shields.io/badge/Java-Automation-orange?style=for-the-badge&logo=openjdk" />
<img src="https://img.shields.io/badge/Selenium-4.51.0-green?style=for-the-badge&logo=selenium" />
<img src="https://img.shields.io/badge/TestNG-7.12.0-red?style=for-the-badge" />
<img src="https://img.shields.io/badge/Maven-Build-blue?style=for-the-badge&logo=apachemaven" />
</p>

<p align="center">
<b>A Java-based Selenium automation testing framework designed to support structured, maintainable, and efficient e-commerce application testing.</b>
</p>

📌 Project Overview
EcommerceHubV9 is a Selenium-based test automation framework developed using Java, TestNG, and Maven.

The framework is designed to organize and execute automated test cases for e-commerce application workflows while supporting test data management, execution logging, and detailed test reporting.

It brings together commonly used automation testing tools and libraries into a Maven-based project structure.

🎯 Project Objectives
Automate web application testing using Selenium WebDriver.
Organize and manage test execution using TestNG.
Simplify dependency management using Maven.
Support data-driven testing using Apache POI.
Generate test execution reports using ExtentReports.
Maintain execution logs using Log4j.
Store test data, screenshots, logs, and reports in dedicated directories.
🛠️ Technology Stack

Technology	Version	Purpose
Java	JDK compatible with dependencies	Programming language
Selenium	4.51.0	Browser automation
TestNG	7.12.0	Test execution
Maven	Compatible version	Build and dependency management
ExtentReports	5.1.2	Test reporting
Apache POI	6.0.0	Excel operations
Log4j	2.26.1	Logging
Commons Email	1.6.0	Email functionality
✨ Framework Capabilities
Browser Automation: Automates web application interactions using Selenium WebDriver.
Test Management: Uses TestNG for organizing and executing test cases.
Maven Integration: Manages project dependencies and build configuration.
Test Data Management: Includes Apache POI for Excel-based data handling.
Execution Reporting: Uses ExtentReports for generating test execution reports.
Logging: Uses Log4j for application and test execution logs.
Screenshot Management: Maintains a dedicated directory for screenshots.
Test Results: Organizes test reports and execution output.
📂 Project Structure

text
EcommerceHubV9/
│
├── .settings/
│
├── src/
│   └── test/
│       └── java/
│
├── testData/
│
├── screenshots/
│
├── reports/
│
├── logs/
│
├── test-output/
│
├── target/
│
├── pom.xml
│
├── testng.xml
│
├── .classpath
│
└── .project
Note: The structure above highlights the directories and configuration files currently visible in the repository. Additional package-level details can be added as the framework evolves.

⚙️ Prerequisites
Before running the project, ensure you have:

Java Development Kit (JDK).
Eclipse IDE or another Java IDE.
Apache Maven.
Git.
A supported web browser for Selenium execution.
🚀 Getting Started
1. Clone the Repository

bash
git clone https://github.com/parurajeshqa/EcommerceHubV9.git
2. Navigate to the Project Directory

bash
cd EcommerceHubV9
3. Import into Eclipse
Open Eclipse IDE.
Select File → Import.
Choose Maven → Existing Maven Projects.
Browse to the cloned EcommerceHubV9 folder.
Select the pom.xml file.
Click Finish.
Allow Maven to download the required dependencies.
4. Execute the Automation Tests
Run the following command from the project root directory:


bash
mvn clean test
The project includes a TestNG suite configuration through testng.xml.

You can also execute the suite from Eclipse using TestNG if the TestNG plugin is configured.

📊 Reports & Execution Results
The framework repository includes dedicated directories for:


Directory	Description
reports/	Test execution reports
screenshots/	Captured screenshots
logs/	Execution logs
test-output/	TestNG execution output
testData/	Test data resources
ExtentReports is included in the project dependencies for test reporting.

🔧 Maven Commands

Command	Description
mvn clean	Cleans previous build output
mvn compile	Compiles the project
mvn test	Executes configured tests
mvn clean test	Cleans and executes tests
mvn dependency:tree	Displays project dependencies
🔄 Framework Workflow

text
       TestNG Suite
            |
            ▼
      Test Execution
            |
            ▼
     Selenium WebDriver
            |
            ▼
   E-commerce Application
            |
            ▼
    Test Result Collection
            |
       ┌────┴─────┐
       ▼          ▼
   ExtentReports  Log4j
       |          |
       ▼          ▼
    Reports      Logs
📸 Screenshots
Project screenshots and execution evidence are maintained in the screenshots/ directory.

You can add selected screenshots here to showcase the framework execution and reporting.

🌟 Future Enhancements
Potential areas for further improvement include:

Page Object Model (POM) implementation.
Cross-browser testing.
Parallel test execution.
CI/CD integration using Jenkins or GitHub Actions.
Enhanced test data management.
Automated report publishing.
Improved exception handling and retry mechanisms.
👨‍💻 Author
Rajesh

GitHub: @parurajeshqa

Project: EcommerceHubV9

🤝 Contributions
Suggestions, feedback, and contributions are welcome.

Feel free to fork this repository and submit a pull request.

📄 License
License information can be added here when a license is selected for the project.

<p align="center">
⭐ If you find this project useful, consider giving it a star!
</p>

<p align="center">
<b>Built with Java, Selenium, TestNG & Maven ❤️</b>
</p>
