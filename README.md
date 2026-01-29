# Thanglish → Tamil Transliteration (Playwright Tests)

## Project Overview
This project contains **Playwright automated test cases** to validate the Thanglish → Tamil transliteration website:

https://tamil.changathi.com/

The test suite checks:
- Correct transliteration for common Thanglish inputs
- Handling of different sentence types (simple/compound/tense/negation)
- Mixed Thanglish + English words (email, WiFi, etc.)
- Robustness for invalid/edge inputs (typos, joined words, symbols, punctuation)
- UI behavior (real-time update after typing a space)

---

## Test Coverage
- **Positive Functional Tests:** 24  
- **Negative Functional Tests:** 10  
- **UI Behavior Tests:** 1  
- **Total Test Cases:** 35

---

## Tech Stack
- Node.js
- Playwright
- JavaScript
- Browsers: Chromium, Firefox, WebKit

---

## Folder Structure
