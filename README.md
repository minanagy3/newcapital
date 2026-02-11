# NewCapital - E-commerce Test Automation

A comprehensive test automation framework for e-commerce applications, designed for educational purposes.

## 📋 Project Overview

This project demonstrates end-to-end test automation for e-commerce platforms, covering:
- User registration and authentication
- Product browsing and search
- Shopping cart functionality
- Checkout process
- Order management

## 🚀 Features

- **Page Object Model (POM)**: Maintainable and reusable page objects
- **Data-Driven Testing**: Excel/JSON data providers
- **Cross-Browser Testing**: Support for multiple browsers
- **API Testing**: REST API validation
- **Reporting**: Comprehensive test reports
- **CI/CD Ready**: Jenkins/GitHub Actions integration

## 📁 Project Structure

```
newcapital/
├── src/
│   ├── tests/
│   │   ├── e2e/
│   │   ├── api/
│   │   └── unit/
│   ├── pages/
│   │   ├── HomePage.js
│   │   ├── LoginPage.js
│   │   ├── ProductPage.js
│   │   └── CheckoutPage.js
│   └── utils/
│       ├── DataProvider.js
│       └── Helpers.js
├── data/
│   └── test-data.xlsx
├── config/
│   └── config.json
└── README.md
```

## 🧪 Test Coverage

### E2E Tests
- User registration flow
- Login and logout
- Product search and filtering
- Add to cart functionality
- Checkout process
- Order tracking

### API Tests
- Authentication endpoints
- Product catalog APIs
- Cart management APIs
- Order processing APIs

## 🏃 Running Tests

### Install Dependencies
```bash
npm install
```

### Run All Tests
```bash
npm test
```

### Run Specific Test Suite
```bash
npm run test:e2e
npm run test:api
```

## 📊 Test Reports

Test reports are generated in the `reports/` directory after test execution.

## 🔧 Configuration

Edit `config/config.json` to customize:
- Base URLs
- Test data paths
- Browser settings
- Timeout values

## 📝 Best Practices

1. **Page Object Model**: All page interactions are abstracted into page objects
2. **Data Separation**: Test data is kept separate from test code
3. **Reusable Utilities**: Common functions are in the utils folder
4. **Clear Naming**: Tests and files follow clear naming conventions
5. **Documentation**: Code is well-documented

## 🎯 Technologies Used

- Selenium WebDriver / Playwright
- TestNG / Jest
- JavaScript / TypeScript
- REST Assured (for API testing)
- ExcelJS (for data providers)

## 📚 Educational Purpose

This project is created for educational purposes to demonstrate:
- Test automation best practices
- Framework design patterns
- CI/CD integration
- Test reporting and analysis

## 📄 License

ISC

## 👤 Author

Mina Nagy QA Engineer

