# ITPM Assignment 1 - Transliteration Accuracy Testing

## Description
This project tests the accuracy of the chat-style Singlish 
to Sinhala transliteration function available at 
https://www.pixelssuite.com/chat-translator

## Student Details
Registration Number: IT23734616

## Prerequisites
- Python 3.11 or 3.12
- Google Chrome browser

## How to install dependencies
pip install -U pip
pip install playwright openpyxl
playwright install

## How to run tests
python test_automation.py --excel "IT23734616_Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

## Project Structure
- test_automation.py — Main Playwright automation script
- IT23734616_Assignment 1 - Test cases.xlsx — Excel file with test cases
- README.md — Project documentation

## Results
- Total test cases: 50
- All test cases are negative (system fails to convert correctly)
- TC IDs begin with Neg_