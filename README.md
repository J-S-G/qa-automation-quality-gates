# QA Automation Quality Gates

Production-oriented QA automation framework demonstrating structured API and
functional testing, CI/CD quality gates, risk-based test planning, and
positive/negative test coverage.

This repository is designed to showcase professional QA and SDET practices,
including test organization, automation readiness, and continuous integration
validation.

## Key Capabilities
- Smoke, positive, negative, and regression testing
- Risk-based test planning and documentation
- CI/CD integration with automated test execution
- Structured test categorization aligned to enterprise QA practices

## Tech Stack
- Python
- PyTest
- GitHub Actions
- Linux (Pop!_OS)

## Test Structure
Tests are organized by category to reflect real-world QA strategies:
- Smoke
- Functional (positive, negative, boundary)
- Regression
- Performance / response validation
- Security and compliance (scaffolded)

## Running Tests Locally
```bash
pip install -r requirements.txt
pytest

