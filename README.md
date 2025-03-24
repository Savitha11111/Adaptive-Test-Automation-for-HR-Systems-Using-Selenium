# Adaptive Test Automation for HR Systems Using Selenium

## Introduction
This Selenium test script automates the login functionality testing of a web application using Python's Selenium library.

## Test Scenario
- The test suite verifies the login process using both valid and invalid credentials.
- It checks if the appropriate error message appears for incorrect login attempts and ensures successful redirection to the dashboard upon valid authentication.

## Technologies Used
- Python
- Selenium WebDriver
- HTMLTestRunner

## Software Requirements
To run this project, ensure you have the following software installed:

1. **Python** (Download: [https://www.python.org/downloads/](https://www.python.org/downloads/))
2. **Google Chrome or Firefox** (for browser-based testing)
   - Chrome: [https://www.google.com/chrome/](https://www.google.com/chrome/)
   - Firefox: [https://www.mozilla.org/en-US/firefox/new/](https://www.mozilla.org/en-US/firefox/new/)
3. **ChromeDriver / GeckoDriver** (based on the browser being used)
   - ChromeDriver: [https://sites.google.com/chromium.org/driver/](https://sites.google.com/chromium.org/driver/)
   - GeckoDriver: [https://github.com/mozilla/geckodriver/releases](https://github.com/mozilla/geckodriver/releases)
4. **Git** (to clone the repository) [https://git-scm.com/downloads](https://git-scm.com/downloads)

## Setup and Execution
### Installation
1. Install Python if not already installed.
2. Install the necessary dependencies:
    ```bash
    pip install selenium webdriver-manager html-testRunner
    ```

### Clone the Repository
3. Clone the repository from GitHub:
    ```bash
    git clone <repository_URL>
    ```
4. Navigate to the project directory:
    ```bash
    cd path/to/project
    ```

### Running the Tests
5. Execute the test script:
    ```bash
    python login_tests.py
    ```

## Test Cases
- **test_login_not_valid:** Ensures the system displays the correct error message when invalid credentials are used.
- **test_login_valid:** Confirms that a user can log in successfully and is redirected to the dashboard.

## Test Execution Reports
The test execution results generate HTML reports stored in the `Reports` directory after completion.

## Contributors
- [Massimiliano Visintainer](https://github.com/MassimilianoVisintainer)

## Acknowledgments
- Thanks to the Selenium community and contributors for maintaining a powerful testing framework.

