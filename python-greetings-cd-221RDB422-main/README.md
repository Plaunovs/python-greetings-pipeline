### python-greetings-cd-221RDB422

# Python Greetings CI/CD Pipeline

This repository defines a GitHub Actions-based delivery pipeline for a Python microservice.

## Structure

- `.github/workflows/python-greetings.yml` – Main CI/CD pipeline definition.
- `.github/actions/install-deps/` – Installs Python and JS dependencies.
- `.github/actions/deploy/` – Deploys the microservice via PM2.
- `.github/actions/test/` – Runs JavaScript API tests.

## Requirements

- Self-hosted runner with:
  - Python 3.8+
  - PM2 installed (`npm install -g pm2`)
  - Node.js


##  Related Repositories

- Python microservice: [`mtararujs/python-greetings`](https://github.com/mtararujs/python-greetings)
- JS API tests: [`mtararujs/course-js-api-framework`](https://github.com/mtararujs/course-js-api-framework)


