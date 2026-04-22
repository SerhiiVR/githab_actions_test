# API Testing with Newman & GitHub Actions

Automated API testing pipeline using Postman collections, 
Newman CLI, and GitHub Actions.

## What's inside

- `postman/` — Postman collection with API test cases
- `.github/workflows/` — GitHub Actions workflow that runs 
  tests automatically on every push

## How it works

1. Postman collection defines API requests and assertions
2. Newman runs the collection from command line
3. GitHub Actions triggers Newman on every push to main
4. Test results appear directly in the Actions tab

## Tools used

- Postman — API test design
- Newman — CLI runner for Postman collections
- GitHub Actions — CI/CD pipeline

## Author

Serhii Vradii · QA Engineer  
[LinkedIn](https://linkedin.com/in/serhii-vradii)
