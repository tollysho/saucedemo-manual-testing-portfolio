
# SauceDemo Login Manual Testing Project

## 📋 Project Overview
This manual testing project evaluates the **login functionality** of the [SauceDemo](https://www.saucedemo.com) web application. The purpose is to validate the login process for various user scenarios, ensuring functionality, usability, and resilience against negative inputs.

The project was executed using a combination of:
- 📄 Manual Test Cases (Excel)
- 🐞 Defect Tracking (Excel + Screenshots)
- 📸 Execution Evidence (Screenshots with timestamps)
- ✅ TestRail (for test case tracking, execution, and reporting)

---

## 🔍 Scope
This project covers the following login scenarios:
- Valid login for standard user
- Locked-out user
- Blank credentials
- Incorrect credentials
- Uppercase & special characters
- SQL injection attempts
- UI behavior and error message alignment
- Logout behavior and back button handling

A total of **15 test cases** were designed and executed.

---

## 📂 Folder Structure

```
Manual_Testing_SauceDemo_Login_Registration/
├── 1. SauceDemo_Test_Plan/
│   └── SauceDemo_Manual_TestPlan.docx
│
├── 2. SauceDemo_Test_Cases/
│   └── SauceDemo_Test_Cases.xlsx
│
├── 3. SauceDemo_Defect_Reports/
│   ├── SauceDemo_Defect_Report.xlsx
│   └── Defect_Screenshot/
│       ├── BUG001_TC005_error_msg_alignment.png
│       ├── BUG002_TC006_uppercase_issue.png
│       └── ...
│
├── 4. SauceDemo_Test_Execution_Evidence/
│   └── Test_Case_Execution_Screenshots/
│       ├── TC005_Login_with_correct_credentials.png
│       └── ...
│
├── 5. SauceDemo_Test_Summary/
│   └── SauceDemo_Test_Summary_Report.docx
│
├── 6. SauceDemo_TestRail_Summary/
│   ├── TestRail_Run_Details.pdf
│   └── TestRail_Run_Outline.pdf
│
└── 7. README_SauceDemo_Manual_Testing.md
```

---

## ✅ Test Execution Results

| Total Test Cases | Passed | Failed | Defects Logged |
|------------------|--------|--------|----------------|
| 15               | 15     | 0*     | 7 minor UI issues (BUG001–BUG007) |

> 💡 *Some test cases revealed minor UI misalignments but were functionally successful.

---

## 🛠️ Tools Used

- **TestRail** – For test case tracking and execution
- **Excel** – For test case and defect management
- **Word** – For Test Plan and Summary documentation
- **Screenshot tools** – Windows Snipping Tool, Snip & Sketch
- **Browser DevTools** – For performance timing and validation

---

## 📈 Project Highlights

- Authored and executed **15 manual test cases**
- Logged **7 UI-related defects** with screenshot evidence
- Simulated real QA workflow using **TestRail**
- Structured deliverables following **industry best practices**

---

## 🙋‍♀️ Author
**Tola Soyoye**  
Manual QA Analyst | Business Systems Analyst in training  
📧 YourEmail@example.com  
🔗 [LinkedIn Profile URL]
