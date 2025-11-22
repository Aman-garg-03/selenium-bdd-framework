# 🚀 Flight Booking Automation Framework

## 📋 Project Overview
Enterprise-grade **Selenium WebDriver + Cucumber BDD** automation framework for end-to-end testing of a Flight Booking web application. Built using **Page Object Model (POM)** design pattern. 
## 🛠️ Tech Stack
| Category | Technology |
|----------|-----------|
| **Language** | Java |
| **Automation Tool** | Selenium WebDriver 4.11.0 |
| **BDD Framework** | Cucumber 7.13.0 |
| **Test Framework** | TestNG 6.11 |
| **Build Tool** | Maven |
| **Reporting** | Extent Reports 5.0.9 |
| **Logging** | SLF4J + Log4j2 |
| **Data-Driven** | Apache POI (Excel), XML Parser |
| **Browser** | Firefox (GeckoDriver) |

## 🏗️ Framework Architecture
```
├── Page Object Model (POM) - Separation of test logic and page interactions
├── BDD with Cucumber - Business-readable Gherkin scenarios
├── Data-Driven Testing - Excel & XML test data
├── Reusable Utilities - Screenshot, Excel, XML handlers
├── Centralized Configuration - Properties-based setup
└── Hooks - WebDriver lifecycle management
```

## ✅ Test Coverage
| Module | Scenarios | Key Validations |
|--------|-----------|-----------------|
| **Login** | 5 | Authentication, Captcha, Remember Me, Password Reset, Authorization |
| **Booking** | 6 | Form validation, Date validation, Calculation, Logout |
| **Flight Search** | 3 | Search by Number/Name/Type |
| **Enquiry** | 5 | Field validations (Subject, Email, Phone, Message) |

## 📊 Reporting
- **Extent Reports**: `target/extent-reports/index.html`
- **Screenshots**: `screenshots/` folder (organized by module)
- **Logs**: Console output with SLF4J

## 📈 Achievements
- ✅ **100% automation** of Sprint 1 manual test cases
- ✅ **POM architecture** for maintainability
- ✅ **BDD scenarios** for business alignment
- ✅ **Data-driven approach** for scalability
- ✅ **Comprehensive reporting** with screenshots
