# appium-cucumberbdd-testng
Appium mobile test automation framework with Page Object Model design using Java + Cucumber + Maven + TestNG.
Framework follows many of the industry best practices and supports Android and iOS in a single code base.

Directory Structure

=================================================

AppiumCucumberFramework/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.qa.utils/
│   │   │       ├── CapabilitiesManager.java
│   │   │       ├── DriverManager.java
│   │   │       ├── GlobalParams.java
│   │   │       ├── PropertyManager.java
│   │   │       ├── ServerManager.java
│   │   │       ├── TestUtils.java
│   │   │       └── VideoManager.java
│   │   └── resources/
│   │       ├── config.properties
│   │       └── log4j2.xml
│   ├── test/
│   │   ├── java/
│   │   │   ├── com.qa.pages/
│   │   │   │   ├── BasePage.java
│   │   │   │   ├── LoginPage.java
│   │   │   │   ├── MenuPage.java
│   │   │   │   ├── ProductDetailsPage.java
│   │   │   │   ├── ProductsPage.java
│   │   │   │   └── SettingsPage.java
│   │   │   ├── com.qa.runners/
│   │   │   │   ├── MyPixel2XLTestNGRunnerTest.java
│   │   │   │   ├── MyPixel3TestNGRunnerTest.java
│   │   │   │   ├── MyPixel4TestNGRunnerTest.java
│   │   │   │   └── RunnerBase.java
│   │   │   └── com.qa.stepdef/
│   │   │       ├── Hooks.java
│   │   │       ├── LoginStepDef.java
│   │   │       └── ProductStepDef.java
│   │   └── resources/
│   │       ├── apps/
│   │       ├── Login.feature
│   │       ├── Products.feature
│   │       └── testng.xml
├── JRE System Library [JavaSE-21]
└── Maven Dependencies



Technologies/Tools used in building the framework
=================================================
- Eclipse - IDE
- Appium - Mobile Automation library
- Maven - Build automation tool
- Java - Programming language
- Cucumber - BDD
- Gherkin - DSL
- TestNG - Test Management library
- Log4J - Logging framework
- Extent Reports - Reporting framework
- JSON - Test Data
- XML - Static text
- GitHub - Version control
- Jenkins - CI/CD

Framework implements below best practices
=========================================
- Code reusability
- Code readability
- Scalable automation (demonstrated using multiple test classes)
- Uses explicit waits
- Abstraction layer for UI commands like click, sendkeys, etc.
- Parameterization using TestNG XML and config.properties
- Abstraction layer for test data
- Abstraction layer for static text
- Supports iOS and Android
- Demonstrates how to define UI elements that are common across pages (e.g. menu bar, side bar, etc.)
- How to recover from test failure/ how to write fail safe test cases
- Scrolling for both Android and iOS (using touchaction, uiScrollable, mobile:scroll)
- Demonstrates how to effectively capture Screenshots/Videos
- Supports parallel execution using TestNG
- Supports parallel execution on multiple real Android and iOS devices
- Start Appium server propgrammatically
- Supports Cucumber-HTML-Reporter plugin
- Integrated with Log4J2 Logging framework
