# Cucumber Practice Project

This project demonstrates a full-featured automation testing framework using **Cucumber**, **Selenium**, and the **Page Object Model (POM)** design pattern. It includes scenarios such as user registration, login, and contact form submissions, supported by parallel and smoke testing configurations.

---

## 📁 Project Structure

- **PageObjectModel/**  
  - `AbstractClass.java` – Base class for common methods  
  - `contactUs_Page.java` – Page class for contact form  
  - `register_Page.java` – Page class for registration flow

- **Runners/**  
  - `paraleltest.java`, `smoketest.java`, `regressiontest.java`, `runnergenel.java` – Various test run configurations

- **XMLFiles/**  
  - `extendReportSet.xml`, `paraleltest.xml` – TestNG XML configurations for test execution and reporting

- **StepDefinition/**  
  - Step definitions for `Register`, `Login`, and `Contact Us` features

- **Utilities/**  
  - `Driver.java` – WebDriver configuration and management

- **test/java/**  
  - Feature files: `Register.feature`, `Register_Background.feature`, `logintest1.feature`, `contactUs1.feature`

---

## 🛠️ Technologies Used

- Java  
- Selenium WebDriver  
- Cucumber  
- JUnit / TestNG  
- IntelliJ IDEA  

---

## ▶️ How to Run

1. Clone the repository  
2. Open it with IntelliJ or your preferred IDE  
3. Run feature files via runner classes in `Runners/`  
4. Ensure WebDriver and dependencies are properly configured  

---

## 🎯 Purpose

This project was built to practice Behavior Driven Development (BDD) with Cucumber and improve test structure using Page Object Model and utility layers.

---

