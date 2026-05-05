# ITPM Assignment 1 - Transliteration Automation Testing

**Student Name:** Yasintha W K M  
**Registration Number:** IT23715110  
**Module:** IT3040 - Information Technology Project Management (ITPM)  
**Task:** Assignment 1 (Option 1) - Transliteration Accuracy Testing

---

## 📌 1. What is this Project?
This project is an automated software testing assignment designed to evaluate the transliteration accuracy of a live web application: [Chat Sinhala Translator](https://www.pixelssuite.com/chat-translator). 

The primary objective is to test how accurately the system converts informal, chat-style **Singlish** (Sinhala typed in English characters) into standard **Sinhala** text. The project aims to identify the weaknesses, boundary conditions, and algorithmic failures of the current transliteration engine using automated UI testing techniques.

## 🛠️ 2. What I Have Done
To thoroughly test the application's limits, I have successfully completed the following tasks as per the university guidelines:
* **Designed 50 Negative Test Cases:** Formulated exactly 50 test cases where the transliteration system completely fails to produce the expected Sinhala output.
* **Covered 24 Singlish Input Categories:** Ensured that all 24 specific Singlish typing behaviors are covered, with at least 2 test cases per category as per Appendix 1.
* **Length Constraints Analyzed:** Distributed the test cases across three string length constraints: Short (<=30 chars), Medium (31-299 chars), and Long (>=300 chars).
* **Automated Execution:** Used Playwright and Python to automate the data entry and result collection process into an Excel report.

## 🚀 3. Installation and Setup
To run this automation project locally, please follow these steps carefully:

### Step 1: Install Prerequisites
* Install **Python 3.11 or 3.12** on your computer. *(Make sure to check the "Add Python to PATH" box during installation).*
* Install **Google Chrome** (recommended).

### Step 2: Install Dependencies
Open your terminal (Command Prompt) and run the following commands:
```bash
pip install pandas openpyxl playwright
playwright install
