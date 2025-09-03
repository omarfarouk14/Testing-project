# Testing-project
# QA Projects Package

This repository contains a collection of **Quality Assurance (QA)** projects demonstrating different testing techniques, including **manual testing**, **API testing**, and **automation testing**.

---

## 📂 Project Structure

- **Manual_Testing/**
  - `Test_Plan.txt` → Detailed test plan outlining scope, strategy, and objectives.
  - `Test_Cases.txt` → List of designed test cases.
  - `Bug_Report.txt` → Documented bugs with steps to reproduce and expected results.

- **API_Testing/**
  - `Reqres.postman_collection.json` → Postman collection for testing the Reqres API.
  - `README.md` → Instructions for running the API tests.

- **Selenium_Automation/**
  - `test_login.py` → Selenium test script for login functionality.
  - `test_checkout.py` → Selenium test script for checkout process.
  - `requirements.txt` → Python dependencies for running the Selenium tests.
  - `README.md` → Instructions for setting up and executing automation tests.

---

## 🚀 Getting Started

### 1. Manual Testing
Simply open the `.txt` files in the **Manual_Testing/** folder to review test plans, test cases, and bug reports.

### 2. API Testing
1. Install [Postman](https://www.postman.com/).
2. Import the collection from `API_Testing/Reqres.postman_collection.json`.
3. Run the API requests and verify responses.

### 3. Selenium Automation
1. Install Python 3.x
2. Install required dependencies:
   ```bash
   pip install -r Selenium_Automation/requirements.txt
python Selenium_Automation/test_login.py
python Selenium_Automation/test_checkout.py
