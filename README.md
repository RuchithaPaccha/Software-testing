# 🧪 Software Testing Project – CGI Visa Scheduling Application

This is a comprehensive software testing project for the **CGI Visa Scheduling Application**, a globally-used web-based platform for managing visa appointment scheduling. The project includes manual and automated testing across various techniques such as boundary value analysis, equivalence partitioning, exploratory, and unit testing.

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
     

## 👩‍💻 Author

**Ruchitha Paccha**  
University of South Florida  
📧 ruchitha1904@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/ruchitha-chowdary-paccha/)

---

## 📑 License

This project is for academic purposes only.
