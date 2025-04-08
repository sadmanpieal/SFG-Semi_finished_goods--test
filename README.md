# 🛡️ Bug Report - Semi-Finished Goods System

This repository documents a QA bug report for the **Semi-Finished Goods** module. The report highlights critical and minor issues discovered during testing and provides a structured summary for the development and QA teams to reference and act upon.

---

## 📋 Project Overview

The **Semi-Finished Goods System** is designed to manage barcode-wise stock verification, company ID registration, stock reconciliation, and report generation. This QA report compiles all known issues to assist developers in optimizing the system's accuracy, usability, and performance.

---

## ✅ Test Summary

| Category              | Count   |
|-----------------------|---------|
| Total Bugs Reported   | 20+     |
| Critical Bugs         | 12      |
| Minor Bugs            | 8       |
| Test Modules Covered  | 5       |
| Status                | Open / In Progress |
| Test Coverage         | ~85%    |

---

## 📁 File Details

- **File Name**: `Bug report of Semi-Finished-Goods.csv`
- **Format**: CSV (Comma-Separated Values)
- **Source**: Jira Export (March 2025)
- **Includes**:
  - Issue Key
  - Summary
  - Status
  - Comments
  - Custom fields
  - Reported & Updated Dates
  - Status Category

---

## 🔍 Sample Bug Entry

| Field               | Example Value                                                           |
|--------------------|--------------------------------------------------------------------------|
| **Bug ID**         | SFG-19                                                                   |
| **Summary**        | Lot number missing in Goods Return Note (confirmed by stock team)        |
| **Severity**       | Critical                                                                 |
| **Status**         | To Do                                                                    |
| **Steps to Reproduce** | 1. Navigate to Goods Return screen <br> 2. Select item and return reason <br> 3. Submit |
| **Expected Result**| System should log lot number for each item returned                      |
| **Actual Result**  | Lot number field is blank; item traceability compromised                 |
| **Reported Date**  | Mar 9, 2025                                                              |

---

## 🔧 Modules Tested

- Goods Return Workflow
- Barcode-wise Stock Verification
- Dropdown Functionality
- Stock Reconciliation Reports
- Company ID Handling in Verification

---

## 🎯 Purpose

This QA report aims to:

- Identify and document all reported bugs with reproducible steps
- Improve inventory traceability and stock accuracy
- Provide the development team with actionable feedback
- Enhance the overall quality and stability of the semi-finished goods management process

---

## 🙋‍♂️ Author

**Name**: Md. Sadman Shahrieal Pieal  
**Role**: QA Engineer  
**Email**: sadmanpieal@gmail.com  
**Date**: March 2025

---

## 🧭 Future Enhancements

- Implement automated regression test cases for dropdown and form behaviors
- Add validation for missing fields like lot number and company ID
- Perform performance testing under high barcode volume conditions
- Integrate Jira Issues with GitHub Projects for better tracking

---

## 📌 Disclaimer

This report is intended solely for use by QA, developers, and product stakeholders involved in the Semi-Finished Goods module. All findings are based on structured manual testing.
