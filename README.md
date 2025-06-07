# 🧪 Software Testing Project – CGI Visa Scheduling Application

This is a comprehensive software testing project for the **CGI Visa Scheduling Application**, a globally-used web-based platform for managing visa appointment scheduling. The project includes manual and automated testing across various techniques such as boundary value analysis, equivalence partitioning, exploratory, and unit testing.
# 🧪 Software Testing Project – CGI Visa Scheduling Application

This repository documents a comprehensive software testing project performed on the **CGI Visa Scheduling Application**, a globally-used platform for managing visa appointment scheduling for U.S. embassies and consulates.

This project was part of a formal academic requirement, and it applies diverse testing methodologies to validate, analyze, and improve the functionality, usability, and security of a real-world web-based system.

---

## 📌 Project Overview

- **System Name**: CGI Visa Scheduling Application  
- **Platform**: Web-based visa appointment system  
- **Tested Modules**: Registration, Login, Appointment Scheduling, Payment, Profile Management  
- **Testing Approaches**: Manual Testing & Automation using Selenium IDE  
- **Tools Used**: Selenium IDE, Chrome/Firefox, Test Documentation Templates

---

## 🧠 Testing Strategies and Paradigms

The following software testing techniques were applied:

- **Unit Testing** – Focused on individual functions such as form validation.
- **Boundary Value Testing** – Validated field limits, such as minimum/maximum character lengths.
- **Equivalence Class Testing** – Divided input into classes and tested representative values.
- **Specification-Based Testing** – Verified functionality against documented requirements.
- **Exploratory Testing** – Manually tested scenarios without predefined scripts to discover hidden issues.

---

## 📊 Test Cases and Results Summary

- **Total Test Cases Executed**: 53  
  - ✅ Passed: 42  
  - ❌ Failed: 11

| Type of Testing        | No. of Test Cases |
|------------------------|-------------------|
| Boundary Value Testing | 10                |
| Equivalence Class      | 10                |
| Exploratory Testing    | 10                |
| Specification Testing  | 10                |
| Unit Testing           | 10                |
| Selenium Testing       | 3                 |

📸 *Visual summary:*

![Testing Summary](slides/testing-summary.png)

---

## 🐛 Defect Analysis

**Total Defects Found**: 11  
- 🔴 High Priority: 7  
- 🟠 Medium Priority: 3  
- 🟢 Low Priority: 1

### 🔍 Notable Defects
1. `"Limit Reached"` error on first appointment attempt
2. Login failure with correct credentials
3. Special characters allowed in username field without validation
4. Navigation buttons missing post-login
5. Calendar loading indefinitely for specific consular posts
6. CAPTCHA and 2FA inconsistencies
7. Payment validation errors with expired/invalid cards

Defect details and screenshots are provided in the `defects/` directory.

---

## 🤖 Automation with Selenium

Selenium IDE was used for browser-based automation of critical functions like:

- ✅ User Registration (Validations & Success Scenario)
- ❌ Login with Invalid Credentials
- ❌ CAPTCHA Failure Handling

Automation scripts (`.side` files) can be found in `/automation`.

---

## 📂 Folder Structure


---

## 📌 Project Highlights

- **System Under Test**: [CGI Visa Scheduling Portal](http://www.usvisascheduling.com/)
- **Modules Covered**: Registration, Login, Appointment Scheduling, Payment, Notifications
- **Testing Tools**: Selenium IDE, Manual Test Cases
- **Test Types**:  
  ✅ Unit Testing  
  ✅ Boundary Value Testing  
  ✅ Equivalence Class Testing  
  ✅ Exploratory Testing  
  ✅ Specification-Based Testing

---

## 🧠 Testing Objectives

- Identify functional and usability bugs
- Validate boundary and equivalence scenarios
- Evaluate the system’s behavior under edge conditions and exploratory workflows
- Assess security validations like CAPTCHA and 2FA
- Simulate user flows using automation (Selenium)

---

## 📂 Folder Structure

| Folder | Description |
|--------|-------------|
| `test-cases/` | Contains detailed test cases organized by type |
| `defects/` | Logged defects with summaries and screenshots |
| `automation/` | Selenium test scripts for registration, login, and form validation |
| `final_report.pdf` | Original PDF project submission |

---

## 🛠️ Tools & Environment

- **Selenium IDE** – for test automation
- **Browsers** – Chrome, Firefox
- **Manual Testing** – exploratory and functional validation
- **OS** – Windows 10
- **Testing Date** – October 2024

---

## 🐛 Sample Defects Identified

| Defect ID | Title | Component | Status |
|-----------|-------|-----------|--------|
| DEF-001 | Invalid Characters Allowed in Username Field | User Profile | 🟥 Open |
| DEF-002 | Login Fails Despite Correct Credentials | Authentication | 🟥 Open |
| DEF-005 | "Limit Reached" Error on First Scheduling | Appointment Scheduling | 🟥 Open |

> 📸 Screenshots available in `/defects/screenshots/`

---

## 🤖 Automation Test Cases

- ✅ User Registration (Pass)
- ❌ Invalid Login (Handled Correctly)
- ❌ Invalid CAPTCHA (Pass)
> Scripts available in the `/automation` folder as `.side` files for Selenium IDE.

---

## 📘 Example Test Case

**Test Case ID**: TC-BVT-001  
**Component**: Password Input  
**Type**: Boundary Value Test  
**Input**: Password with 7 characters  
**Expected Output**: Error message – “Password must be at least 8 characters”  
**Result**: ✅ Pass  
**Tester**: Ruchitha Paccha

---

## 👩‍💻 Author

**Ruchitha Paccha**  
University of South Florida  
📧 ruchitha1904@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/ruchitha-chowdary-paccha/)

---

## 📑 License

This project is for academic purposes only.
