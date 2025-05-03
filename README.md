# QLSV App Testing Repository

## Overview

This repository contains the test cases and documentation for testing the QLSV (Quản Lý Sinh Viên) Windows application, specifically the QLSV.exe executable. The test cases focus on verifying the functionality, UI, and behavior of the application's login and search features. The test cases are documented in the provided Excel file: Windows app testing - Kiểm thử windows app _ QLSV.exe.xlsx.

## Repository Structure

- **/docs:** Contains the test case documentation.

  - Windows app testing - Kiểm thử windows app _ QLSV.exe.xlsx: Excel file with detailed test cases for login and search functionalities.
- **/README.md:** This file, providing an overview and instructions for the repository.

## Test Case Summary

The test cases cover two main modules of the QLSV application:

1. **Login Module (LOG001 to LOG012):**

- Verifies the login UI, default values, font styles, alignment, and authentication behavior.
- Includes happy path scenarios (valid credentials) and negative cases (invalid or blank inputs).
- Example test data: Username: quanghoa, Password: 123456.

2. **Search Module (SE001 to SE013):**

- Verifies the search UI, default values, font styles, alignment, and grammar/spelling.
- Tests functional scenarios such as searching by student ID, full/partial names, and case-insensitive inputs.
- Includes negative cases like invalid inputs, special characters, and SQL injection attempts.
- Example test data: Student ID: 015, Student Name: Nguyen Nhat Anh.
  
## Key Details

- Platform: Tests are executed on Internet Explorer 11 (IE11).
- Test Types: UI, Functional (Happy Case and Negative).
- Notable Issues:
  - LOG004: Alignment test failed, indicating a UI issue that needs to be addressed.
