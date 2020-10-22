# JPMorganLogoVal
JPMorganLogoValidation


Pre-requisites:(software)
•	Java(1.8)
•	Eclipse(2020-09)
•	Eclipse Plugins
•	Maven(3.8.1)
•	Cucumber(1.2.5)
•	Junit(4.12)

Setting up selenium cucumber java:
•	Install Java and set path.
•	Install Maven and set path
Automation Testing Using Java
selenium-cucumber

Framework Architecture:
•	src/test/resources/features - all the cucumber features files (files.feature ext) present here
•	src/test/java/stepdefinitions - define step defintion under this package for feature steps.
•	src/test/java/utility - all utility and helper class for the framework present here
•	src/test/java/runner - define runner class for cucumber project
•	src/test/java/pageobject- all the page object methods will be defined under this package
•	target/HtmlReport/index.html -Result report gets generate here.
•	target/logs – Logs file gets generate here.

Running features:
•	Goto project directory.
•	Use "mvn test" command to run features.
