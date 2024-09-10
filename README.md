CI/CD Pipeline Setup for GitHub Repository
Overview
This project demonstrates how to set up a CI/CD pipeline using GitHub Actions for a repository. The pipeline includes stages for linting, code quality checks, and unit testing. Additionally, it automates the merging of feature branches into the dev branch upon successful CI validation.

Repository Setup
Create a New Repository:

Created a new repository named <assignment-04> on GitHub.
Branch Structure:

dev Branch: This is the primary development branch.
Feature Branches: Multiple feature branches prefixed with feature/ are created for development.
GitHub Actions Workflow:

Added a GitHub Actions workflow file located at .github/workflows/ci.yml.
CI/CD Pipeline Configuration:

Linter: Ensures that code adheres to the specified linting rules.
Code Quality Check: Performs static analysis to check for code quality issues.
Unit Test: Runs unit tests to ensure that the code behaves as expected.
Automated Merging:

If all CI stages pass successfully, the code from the feature branch is automatically merged into the dev branch.
