GitHub Actions CI/CD Setup
--------------------------

Description
-----------
This project is designed to integrate a Continuous Integration (CI) and Continuous Deployment (CD) pipeline using GitHub Actions. The pipeline runs Cypress component tests whenever a Pull Request (PR) is made to the develop branch. When the code is merged from develop to main, the application is automatically deployed to Render. This setup ensures that all code integrations are clean, pass the necessary tests, and that the application is always up to date when major releases are made to the main branch.

Motivation
The motivation behind this project is to automate the testing and deployment processes to ensure code quality and streamline deployments. By using GitHub Actions for CI/CD, we reduce manual steps, mitigate errors, and ensure that the application is always deployed and functioning as expected after every merge to the main branch.

User Story
-----------
AS A software engineer looking to integrate a CI/CD pipeline in a codebase
I WANT a full-stack application that runs test cases when a Pull Request is made to the develop branch and automatically deploys to Render when the code is merged to the main branch
SO THAT I can ensure that all code integrations are clean and pass the proper requirements and that the application is constantly updated when major releases are made to the main branch.

Acceptance Criteria
--------------------

GIVEN a full-stack application,
WHEN I upload new features to the application,
THEN I should be making Pull Requests to a develop branch first.
WHEN I create a Pull Request to a develop branch,
THEN I should be executing a GitHub Action that checks the Cypress component tests.
WHEN I see that the tests pass on GitHub Action,
THEN I should see those test results on GitHub Action and merge the code.
WHEN I push the code from the develop branch to the main branch,
THEN I should see that another GitHub Action triggers and should automatically deploy to Render.

Technologies Used
------------------

GitHub Actions
Cypress (for component tests)
Render (for deployment)
MongoDB
Node.js
React
Getting Started
Upload Starter Code:



