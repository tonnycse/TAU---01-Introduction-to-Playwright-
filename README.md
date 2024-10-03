**TAU - Playwright Introduction**

This repository contains the code developed as part of my self-practice while completing the Introduction to Playwright course by Test Automation University.

**Project Overview**

The project demonstrates basic Playwright concepts, including:

- Setting up Playwright
- Writing code for simple test on (https://playwright.dev/) page
- Learned about before all, before each, after all, after each and test.describe
- Learned about Page Object Model
  
**Prerequisites**

- Node.js
- npm
- VS Code
  
**Installation**

**1. Clone the repository:**

git clone https://github.com/tonnycse/TAU--Playwright-Introduction.git cd TAU--Playwright-Introduction

**2. Install dependencies:**

- npm install
- npm init playwright@latest

**Running Tests**

**1. All Tests:**

npx playwright test

**2. Specific Test:**

npx playwright test tests/homepage.spec.ts

**3. Headed Mode:**

npx playwright test --headed

**4. UI Mode:**

npx playwright test --ui

**5. Run Test on Different Browsers:**

npx playwright test --project webkit [Used Webkit As Example]

**Reporting**

To view a detailed HTML report:

npx playwright show-report
