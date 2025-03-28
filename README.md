# Cypress Test Automation for Customer Support Center

## 📌 Overview
This project contains automated tests using [Cypress](https://www.cypress.io/) to validate the functionalities of a Customer Support Center web application. The test suite covers form validation, input interactions, file uploads, and privacy policy redirections.

## 🚀 Technologies Used
- [Cypress](https://www.cypress.io/) - End-to-end testing framework
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - Programming language

## 📂 Project Structure
```
📂 cypress-automation-project
│--📂 cypress
│   │--📂 fixtures    # Test data
│   │--📂 integration # Test cases
│   │--📂 support     # Custom commands and utilities
│--📂 cypress/videos  # Test execution recordings (optional)
│--📂 cypress/screenshots # Failure screenshots (optional)
│-- cypress.json      # Cypress configuration file
│-- package.json      # Dependencies and scripts
```

## 🔧 Setup and Installation
### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (Version 14 or later recommended)
- [npm](https://www.npmjs.com/) (or [Yarn](https://yarnpkg.com/))

### Installation Steps
1. Clone this repository:
   ```sh
   git clone https://github.com/your-user/your-repository.git
   cd your-repository
   ```
2. Install dependencies:
   ```sh
   npm install
   ```

## 🧪 Running Tests
To run Cypress in headless mode:
```sh
npx cypress run
```

To open Cypress Test Runner:
```sh
npx cypress open
```

## 📜 Test Cases
### ✅ Form Validation
- **Verify application title**: Ensures the page title is correct.
- **Submit form with required fields**: Ensures a success message is displayed.
- **Submit form with invalid email**: Ensures an error message is displayed.
- **Ensure phone field does not accept non-numeric values**.
- **Ensure phone is required if the checkbox is selected**.
- **Clear form fields and verify they reset**.

### 📌 Dropdown and Checkbox Tests
- **Select product from dropdown by text, value, and index**.
- **Mark different service types (radio buttons and checkboxes)**.

### 📁 File Upload Tests
- **Upload a file using different methods (direct selection, drag-and-drop, fixture aliasing)**.

### 🔗 Privacy Policy Tests
- **Ensure the privacy policy opens in a new tab**.
- **Remove target attribute and navigate to privacy policy page**.

## 📋 Contribution
Feel free to contribute with improvements and new tests!

1. Fork the project
2. Create a branch for your feature (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the repository (`git push origin feature/new-feature`)
5. Open a Pull Request

## 📄 License
This project is licensed under the MIT License. Feel free to use and improve it!

---
🔹 _Developed with Cypress to ensure quality and reliability in automated testing._

