# 🚕 Urban Routes - Sprint #3: Cross-Browser & UI Testing

## 📝 Project Overview

In this sprint, I focused on testing the Car Sharing features of the Urban Routes app. My goal was to make sure the app looks and works perfectly on different browsers and screen sizes. I performed a full audit to find visual bugs and functional errors that only appear in specific environments.

## 🧪 Where I Tested

I used two different setups to check how the app adapts to different screens:

- Environment 1 (Chrome): Small screen (800x600) to check how elements move and resize.
- Environment 2 (Firefox): Large screen (1920x1080) to check full-page functionality.

## 🎯 What I Learned

- **Web Elements**: How to inspect and test buttons, forms, and maps.
- **Responsive Design**: How to find bugs when a website changes size.
- **Browser Engines**: Learning that an app might work in Chrome but fail in Firefox.
- **Technical Test Design**: Writing detailed test cases specifically for web interfaces.

## 🛠️ Tools & QA Techniques

Tools Used:
- Google Sheets – Test case design, execution tracking, and checklists
- Jira – Defect reporting and lifecycle management
- Figma – UI and design validation
- Google Chrome & Mozilla Firefox – Test execution

## 📁 Testing Documents

I organized my work into four main areas to ensure 100% coverage:

* **UI & Layout Checklist**: Checking the design and visual elements. (https://docs.google.com/spreadsheets/d/1K75Ku75wPVc5dTUCSazlnF4x5Wz5ncbe/edit?usp=sharing&ouid=110641800876252641675&rtpof=true&sd=true)
* **Payment Method Tests**: Testing the flow for adding and using credit cards. (https://docs.google.com/spreadsheets/d/1K75Ku75wPVc5dTUCSazlnF4x5Wz5ncbe/edit?usp=sharing&ouid=110641800876252641675&rtpof=true&sd=true)
* **Reservation Logic**: Testing the main "Reserve" button and user flow. (https://docs.google.com/spreadsheets/d/1K75Ku75wPVc5dTUCSazlnF4x5Wz5ncbe/edit?usp=sharing&ouid=110641800876252641675&rtpof=true&sd=true)
* **Car Rental Suite**: Testing the specific rules for renting a vehicle. (https://docs.google.com/spreadsheets/d/1K75Ku75wPVc5dTUCSazlnF4x5Wz5ncbe/edit?usp=sharing&ouid=110641800876252641675&rtpof=true&sd=true)

## 🔍 Key Bug Findings & Observations

Since the original Jira environment for this sprint is no longer active, here is a summary of the most critical issues identified during the audit:

* **UI Overlap (Chrome 800x600)**: Identified that the "Payment Method" modal window was not scaling correctly on smaller resolutions, causing buttons to overlap and become unclickable.
* **Browser Compatibility (Firefox)**: Found a specific issue where the "Reserve" button animation would hang in Firefox, preventing the user from completing the rental flow.
* **Data Validation**: Discovered that the credit card expiration date field allowed past dates, which could lead to failed transactions at the API level.
* **Adaptive Layout**: Found that several product images lost their aspect ratio when switching from 1920x1080 to 800x600, affecting the overall visual quality of the app.

## 🌍 Language Notice
[!NOTE] Documentation Language

All test cases and bug reports in the linked documents were written in Spanish, following the original project requirements. I have kept them in their original language to show the authentic work I delivered. This README provides the summary in English for international visitors.
