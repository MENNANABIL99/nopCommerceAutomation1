# nopCommerce Test Automation

UI test automation in Java with Selenium WebDriver and TestNG, using the Page Object Model. It tests the [nopCommerce demo store](https://demo.nopcommerce.com).

## Tech stack
Java | Selenium WebDriver 4.34.0 | TestNG 7.9.0 | WebDriverManager 5.7.0 | Maven

## Structure
```
src/main/java/Pages
  LoginPage.java           login page object
  RegistrationPage.java    registration page object
src/test/java
  BaseTest/BaseTest.java   browser setup and teardown
  tests/RegistrationTest.java
  tests/LoginTest.java
```

## Scenarios
- **Registration:** valid registration (runs with TestNG)
- **Login:** valid and invalid login scenarios with a login page object. These are written but not enabled in the TestNG suite yet.

## Run the tests
Requirements: JDK, Maven and Google Chrome.
```
git clone https://github.com/MENNANABIL99/nopCommerceAutomation1.git
cd nopCommerceAutomation1
mvn test
```
