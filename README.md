# QA Automation Framework (PyTest)

## Overview
This repository demonstrates a production-style QA automation framework
using PyTest, structured test categories, and CI quality gates.

## Test Coverage
- Functional (SDLC-stage aligned)
- UI/UX
- Security & Subdomain Enumeration
- Scalability & Load
- Privacy & Compliance
- Mobile OS Resilience
- Environment & Configuration
- Data Sync & Persistence

## Tech Stack
- Python 3.x
- PyTest
- GitHub Actions (CI)
- Linux (Pop!_OS)

## How to Run Tests
pip install -r requirements.txt
pytest

## CI / Quality Gates
All tests run automatically on push and pull requests.
Builds fail if tests do not pass.

## Limitations
Some test categories are scaffolding for demonstration purposes.
