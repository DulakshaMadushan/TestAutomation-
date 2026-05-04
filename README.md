# Assignment 1 - Playwright Test Automation

##  Overview

This repository contains the automated test script and test cases for **Assignment 1: Transliteration Accuracy Testing** for the Chat Sinhala Translator.

---

##  Prerequisites

Before running the tests, ensure you have the following installed:

* Python 3.11 or 3.12
* Google Chrome (recommended)

---

##  Installation Instructions

1. Clone the repository or extract the ZIP file.

2. Open Command Prompt and navigate to the project directory:

```bash
cd path/to/test_automation
```

3. Upgrade pip:

```bash
pip install -U pip
```

4. Install required dependencies:

```bash
pip install playwright openpyxl
```

5. Install Playwright browsers:

```bash
playwright install
```

---

##  Running the Tests

To execute the automated Playwright tests, run the following command:

```bash
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1
```

>  Note: If your system uses `py` instead of `python`, use:

```bash
py test_automation.py ...
```

---

##  Test Results

After execution:

* The **"Actual output"** column will be populated automatically
* The **"Status"** column will indicate pass/fail results

All results will be updated in:

```
Assignment 1 - Test cases.xlsx
```

---

##  Files Included

* `test_automation.py` – Playwright automation script
* `Assignment 1 - Test cases.xlsx` – Test inputs, expected outputs, and results
* `Assignment 1 - Option 1 - For students familiar with Sinhala.pdf` – Assignment guidelines
* `Automation Steps - Option 1.pdf` – Test automation instructions

---
