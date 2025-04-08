# 🧪 Nanox Automation Task

This project is an automated test suite developed using Java, Selenium WebDriver, and Cucumber. It simulates user interaction on [Demoblaze](https://www.demoblaze.com/index.html), covering key functionalities of the site.

---

### 📦 Setup Instructions
1. **Download the ZIP** of the project or clone the repository:
https://github.com/Tamer-Masarwe/NanoxAutomationTask


## ✅ Test Scenarios

The project includes **5 test scenarios** organized into **4 feature files**. These tests verify:

- User registration
- Login functionality
- Adding products to the cart
- Deleting items from the cart
- Placing an order


## ▶️ Running Specific Tests

By default, the `TestRunner` class runs **all features** located at:
features = "src/test/resources/features"

To run a specific feature, modify the line to:
features = "src/test/resources/features/featureName.feature"


## 📄 Logging and Reporting
After each test run, a log file is generated to track execution steps.

If any test fails, a screenshot will be automatically taken and saved to the /screenshots directory in the project root.


## 📌 Notes
Tests are written following the Page Object Model (POM) and OOP principles.

Alert handling, waits, and pop-ups are managed using Selenium best practices.

Screenshots and logs improve debugging and reporting.


