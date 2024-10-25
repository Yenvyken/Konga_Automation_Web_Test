# KongaWebTest

# Konga Order Flow Automation Project
## Overview
This project automates the order flow for an e-commerce platform, Konga, from login to checkout. It covers key scenarios like logging in, adding products to the cart, and handling payment failures.

## Project Objectives
- Automate end-to-end ordering flow
- Validate different user interactions and error handling

## Technologies Used
- **Selenium WebDriver** - For browser automation
- **Java** - Programming language
- **Maven** - Project management
- **Allure** - Reporting

## Setup Instructions
1. Clone this repository: `git clone [https://github.com/Yenvyken/KongaWebSignupTest.git]`
2. Install dependencies via Maven: `mvn install`
3. Run tests: `mvn test`

## Results and Reports
- Reports are generated using Allure. Run `allure serve` to view the report locally.

## Sample Code
```java
// Example login test
public void loginTest() {
    driver.findElement(By.id("username")).sendKeys("testuser");
    driver.findElement(By.id("password")).sendKeys("password");
    driver.findElement(By.id("loginButton")).click();
}
