# Cypress Cucumber Testing 

This is set up for End-to-End (E2E) testing with **Cypress** and the **Cypress Cucumber Preprocessor** to support BDD (Behavior-Driven Development) using feature files and step definitions.

## Installation Guide

Ensure you have Node.js and npm installed. Create a new project directory and initialize it:

Follow these steps to initialize and configure the project:

1. **Initialize the project**:
   - npm -i init
     
 2.**Install Cypress**:
  - npm install cypress --save-dev
    
3.**Open Cypress**
  - npx cypress open

4.**Install Cypress Cucumber Preprocessor**:
 -  npm install cypress-cucumber-preprocessor --save-dev

5.**Run Cypress with the Cucumber Preprocessor**:
  - After completing the setup, use this command to open Cypress:
    - npm run cypress:open
     
**Project Structure**

Your project directory should be structured as follows:

project-root/

├── cypress/**

│   ├── e2e/

│   │   ├── feature_files/                       // Folder for feature files

│   │   │   └── simpleForm.feature              // Example feature file

│   ├── support/

│   │   ├── step_definitions/                  // Folder for step definitions

│   │   │   └── simpleFormSteps.js             // Example step definitions

│   │   └── commands.js

├── cypress.config.js                          // Cypress configuration file

└── package.json


**cypress/e2e/feature_files/**: Contains .feature files that define the tests in Gherkin syntax.

**cypress/support/step_definitions/**: Stores the JavaScript step definitions associated with each feature file.

**cypress.config.js**: The main configuration file for Cypress.

**Running the Tests**

-Once your setup is complete, you can open and run Cypress tests using:

  -npm run cypress:open
