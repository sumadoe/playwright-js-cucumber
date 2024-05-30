# Playwright-Cucumber-JS with Allure Reporter

This project demonstrates how to set up a testing environment using Playwright, Cucumber.js, and the Allure Reporter. It provides a robust framework for writing end-to-end tests in a Behavior-Driven Development (BDD) style with comprehensive reporting capabilities.

## Table of Contents

- Installation
- Configuration
- Cucumber.js Configuration
- Allure Reporter Configuration
- Writing Tests
- Running Tests
- Generating Allure Reports


## Installation

To get started, ensure you have Node.js installed. Then, follow these steps:

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Run the test:
    ```bash
    npm test
    ```

3. Generate Report:
    ```bash
    npm run report
    ```

## Configuration



### Cucumber.js Configuration

Cucumber.js configuration is set up in `cucumber.js`:
```json
{
  "default": {
    "require": [
      "features/step_definitions/*.js",
      "features/support/*.js"
    ],
    "format": [
      "node_modules/cucumber-pretty",
      "node_modules/@cucumber/pretty-formatter"
    ],
    "publishQuiet": true
  }
}
