# Technical Test: QA Manual Engineer

## 📌 Introduction
This test is designed to evaluate your analytical thinking, testing logic, and documentation quality. The object of this test is the **"Sign Up, Login and Post"** feature on the Twitter (X) application.

---

## 🛠 Tasks
You are required to perform a quality analysis on these features. The task is divided into three sections and must be submitted within **2 Days** after receiving this email.

### 1. Test Case Creation
Create a minimum of **10 Test Cases** covering:
* **Positive Tests:** Standard scenarios where the feature works as intended.
* **Negative Tests:** Scenarios where the system is given invalid/incorrect input.
* **UI/UX Tests:** Validation of visual elements, icon consistency, and navigation flow.

### 2. Edge Case Analysis
Identify at least **3 Edge Cases** (extreme or boundary conditions).
*Example: Unstable network conditions, unique character limits, or simultaneous system interruptions.*

### 3. Bug Reporting
Create **2 Bug Reports** based on your findings (or simulated scenarios if no real bugs are found). Reports must be written clearly so that a Developer can reproduce the issue without further clarification.

---

## 📝 Submission Format (Template)

### A. Test Case Table
| ID | Scenario Description | Steps to Execute | Expected Result | Type (Pos/Neg/UI) |
|:---|:---|:---|:---|:---|
| TC-001 | Post tweet with < 280 characters | 1. Open composer<br>2. Input text "Hello"<br>3. Click 'Post' | Tweet appears on the timeline | Positive |

### B. Bug Report Template
* **Bug ID:** [e.g., BUG-001]
* **Title:** [Short and descriptive title]
* **Severity:** [Blocker / High / Medium / Low]
* **Steps to Reproduce:**
    1. ...
    2. ...
* **Actual Result:** [What actually happened?]
* **Expected Result:** [What should have happened?]
* **Environment:** [e.g., iOS 17.2 / Website]

| ID | Title | Steps to Reproduce | Actual Result | Expected Result |Environment|
|:---|:---|:---|:---|:---|:---|
| BUG-001 | input text more 280 characters | 1. Open composer<br>2. Input text more 280 characters  | Can still input characters when exceeding 280 characters. | If input text more than 280 characters, we cannot input more characters.| Website |

---

## 🎯 Evaluation Criteria
1.  **Logical Analysis:** How well you think beyond standard functional paths.
2.  **Documentation Quality:** Use of technical, effective, and unambiguous language.
3.  **Attention to Detail:** Ability to detect anomalies in visual elements or functional flows.

---

## 📬 How to Submit
1. Complete this task in **Google Sheets** link. Separate the Test Case and Bug sheet.
2. Send the file via email to `alif.m@lif.id and stanley.y@lif.id` with the subject line:
   `QA_Engineer_Test_FullName`
