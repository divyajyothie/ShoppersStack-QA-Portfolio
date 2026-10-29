# 🛒 ShoppersStack E-Commerce — Manual Testing & Defect Tracking Portfolio

## 📌 Project Overview
This repository demonstrates end-to-end Quality Assurance (QA) manual testing methodologies for the **Admin Sign-Up Module** of **ShoppersStack**, an e-commerce platform. It highlights rigorous functional testing, boundary value analysis, negative testing, and structured defect logging aligned with industry best practices.

* **Domain:** E-Commerce
* **Module:** Admin Sign-Up / Registration
* **Test Documentation Source:** `SHOPPERSTACK FT.xlsx`
* **Defect Tracking:** GitHub Issues (20-Point Structured Defect Template)
* **Target Role Level:** Mid to Senior QA Engineer (6–9+ LPA Standards)

---

## 📑 Test Scope & Methodology

The testing lifecycle follows strict traceability between business requirements, test design, and bug reporting:

1. **Requirement Analysis & Test Case Execution:** Executed comprehensive test scenarios covering field-level validations, boundary conditions, mandatory state checks, and workflow rules.
2. **Defect Lifecycle Management:** Identifies, logs, and classifies bugs based on Severity (Critical, Major) and Priority (P1, P2) using a standardized 20-point defect report format.
3. **Traceability:** Every issue in this repository maps directly to specific test cases and steps documented in `SHOPPERSTACK FT.xlsx`.

---

## 🐛 Summary of Logged Defects

| Defect ID | Title | Module / Field | Severity | Priority |
| :--- | :--- | :--- | :--- | :--- |
| **BUG-01** | Last Name field accepts numeric digits without validation error | Last Name | Major | P2 |
| **BUG-02** | Form submits without selecting a Gender radio button | Gender Selection | Major | P2 |
| **BUG-03** | Phone Number accepts invalid 9-digit input without length check | Phone Number | Major | P2 |
| **BUG-04** | Email ID accepts invalid format missing valid domain structure | Email ID | Critical | P1 |
| **BUG-05** | Password field accepts values under 6-character minimum limit | Password | Critical | P1 |
| **BUG-06** | Registration proceeds when Confirm Password does not match | Confirm Password | Critical | P1 |
| **BUG-07** | Registration completes without agreeing to Terms & Conditions | Terms & Conditions | High | P1 |
| **BUG-08** | Country dropdown allows submission on default placeholder | Country Dropdown | Major | P2 |
| **BUG-09** | State dropdown options fail to load upon selecting valid Country | State Dropdown | Major | P2 |
| **BUG-10** | Register button allows duplicate submissions on rapid clicks | Registration Action | Major | P2 |

---

## 🛠️ Defect Report Structure (20-Point Standard)

Every issue logged under the **Issues** tab follows a rigorous schema ensuring complete reproducability:
* **Identification:** Defect ID, Requirement No., Test Case Name
* **Context:** Project Name, Module, Tested URL, Test Environment (OS, Browser version)
* **Impact Rating:** Severity level & Priority ranking
* **Execution Details:** Step-by-step reproduction instructions, Expected Result vs. Actual Result

---

## 📂 Repository Contents
* `SHOPPERSTACK FT.xlsx` — Functional test cases and requirement trace matrix.
* `Issues Tab` — Live database of logged bugs with complete defect lifecycle details.

---
*Created as part of a Software Quality Assurance Portfolio.*
