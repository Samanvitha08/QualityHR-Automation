Project: QualityHR-Automation

Type: Selenium Test Automation Framework
Language: Java
Framework: TestNG
Design Pattern: Page Object Model (POM)



Core Layer (src/main/java):
- base        : Common reusable methods (BasePage)
- driver      : WebDriver setup and management (DriverFactory)
- pages       : Page classes for UI interaction (Login, Admin, Employee, Leave)
- utils       : Helper classes (ConfigReader, WaitHelper, ExtentReportManager)



Resources (src/main/resources):
- config.properties : Application configuration
- testdata.xlsx     : Test data input


Test Layer (src/test/java):
- tests     : Test cases (LoginTest, AdminTest, etc.)
- listeners : Test execution tracking and reporting



Output:
- reports : Stores execution results and reports
