# IT3040 Assignment 1 – Singlish Transliteration Testing

## Prerequisites
- Python 3.12
- Google Chrome browser

## Installation

1. Download all files from this repository

2. Install dependencies:
   pip install playwright openpyxl
   playwright install

## Running the Tests

python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

## Test Cases
- 50 negative test cases covering all 24 Singlish input types
- Results are saved automatically to the Excel file
