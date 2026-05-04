# IT23219052 – Sarah Md – IT3040 Assignment 1

## Project Title
Automated Testing for Singlish to Sinhala Transliteration System

## Repository
https://github.com/SarahMd/IT3040-Assignment1_new.git

---

## Project Structure

IT3040_Assignment_1/
├── test_automation.py                  → Playwright automation script
├── Assignment 1 - Test cases.xlsx     → Excel file with test cases & results
├── README.md                           → Project documentation

---

## Technologies Used

- Python
- Playwright (UI Automation)
- OpenPyXL (Excel handling)

---

## How to Run the Project

1. Open terminal inside the project folder

2. Install dependencies
   pip install playwright openpyxl
   playwright install chromium

3. Run the automation script
   python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"

---

## Output

- Results are automatically written to the Excel file
- Columns updated:
  - Actual output
  - Status (FAIL)

---

## Test Case Details

- Total Test Cases: 50
- Test Type: Negative Testing
- All test cases represent scenarios where the system fails to correctly convert Singlish to Sinhala

### Covered Input Types (24 Categories):
- Question forms
- Command forms
- Greetings
- Requests
- Responses
- Repeated words
- Inputs with punctuation marks
- Romanization / Spelling variants
- Isolated English word insertions
- Multi-word English phrases
- English digital terms
- Platform/App names
- English abbreviations/acronyms
- English clipped forms
- Place names embedded in Singlish
- Person names embedded in Singlish
- Inputs with numbers and numeric suffixes
- Inputs with currency
- Inputs with time formats
- Inputs with dates
- Inputs with units of measurement
- Inputs with slang and casual phrasing
- Online identifiers in Singlish
- Inputs containing emojis

---

## Important Notes

- This script uses strict comparison between expected and actual output
- All 50 test cases are negative — the system is expected to fail on all of them
- Some failures occur due to:
  - Transliteration inconsistencies
  - Mixed language complexity
  - UI timing delays

---

## Student Information

- Student ID: IT23219052
- Name: Sarah Md
- Module: IT3040 – IT Project Management
- Assignment: Assignment 1 (Option 1)
- Semester: year 3 Semester 2

---

## Final Status

✔️ Automation script working
✔️ Excel-based test cases completed
✔️ All 24 input type categories covered
✔️ Git repository publicly accessible

---

## Submission Notes

- Virtual environment (venv) is excluded
- All required files are included
- Project is fully runnable following the steps above

---
