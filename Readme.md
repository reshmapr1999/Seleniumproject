SauceDemo Automation Test

This repository contains an automated test for the SauceDemo application using Selenium IDE. The test case includes searching for a product, adding it to the cart, and completing the checkout process.

Table of Contents
Prerequisites
Installation
Running the Tests
Additional Information
Future Improvements

Prerequisites

Ensure you have the following installed on your local machine:

Node.js: Download and install Node.js.
npm: Comes with Node.js for managing dependencies.
Selenium IDE

Running the Tests
Run the Test: Execute the automated test script using the following command:


npm test
This command runs the test file swag.spec.js, which performs the following actions:

Logs into the SauceDemo application.
Searches for the "Sauce Labs Fleece Jacket".
Adds the product to the cart.
Proceeds to the checkout and completes the purchase.
Viewing Results: The test results will be displayed in the terminal, including any test failures or successes.