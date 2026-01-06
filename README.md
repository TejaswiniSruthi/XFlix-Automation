# XFlix Automation Test Suite

This project is a Selenium WebDriver automation suite written in Java to test core user flows of the XFlix web application using the Chrome browser.

## Tech Stack
- Java
- Selenium WebDriver
- ChromeDriver
- WebDriverManager

## Test Case Overview

### testCase01 – Application Launch Validation
Verifies that the XFlix application launches successfully by checking whether the URL contains the keyword `xflix`.

### testCase02 – Search Functionality Validation
Tests the search feature with valid and invalid inputs. Confirms that results appear for valid searches and a proper “no results” message is shown for invalid searches.

### testCase03 – Sorting Validation
Validates the sorting functionality by applying “Sort By: View Count” and confirming that the order of video titles changes accordingly.

### testCase04 – Video Upload Workflow
Tests the video upload flow including form validation, alert handling, dropdown selections, and successful submission of video details.

### testCase05 – Like Count Persistence
Validates that the video like count remains consistent when the same video is opened in a new browser tab.

## Key Features Covered
- Browser setup with logging enabled
- Search and filter validation
- Dropdown handling
- Alert handling
- Explicit and implicit waits
- Multi-tab validation
- End-to-end user flow testing

## Notes
- This project does not use TestNG or JUnit; test cases are executed via method calls.
- Designed to demonstrate core Selenium automation skills and real user scenario validation.
