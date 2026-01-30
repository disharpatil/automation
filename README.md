# QA Automation Case Study – Automation Engineering Intern (Bynry)

## Overview
This repository contains my solution for the QA Automation Engineering Intern case study provided by Bynry.  
The goal of this assignment is to demonstrate my testing mindset, automation approach, and framework design thinking for a multi-tenant B2B SaaS platform.

The focus is on **reliability, scalability, and clarity of approach** rather than full production-ready implementation.

---

## Tech Stack & Tools
- **Language:** Python  
- **Test Framework:** Pytest  
- **UI Automation:** Playwright  
- **API Testing:** Pytest (requests-based approach)  
- **Cross-Platform Testing:** BrowserStack (conceptual integration)  
- **Version Control:** Git & GitHub  

---

## Project Structure
```

qa-automation-case-study/
│
├── README.md                # Project overview and setup
├── test-plan.md             # Test strategy and scope
├── approach.md              # Detailed testing approach and assumptions
│
├── tests/
│   ├── ui/                  # UI automation tests
│   │   └── test_login.py
│   ├── api/                 # API tests
│   │   └── test_create_project.py
│   └── integration/         # API + UI integration tests
│       └── test_project_flow.py
│
├── test-data/
│   └── sample_projects.json # Sample test data
│
└── reports/
└── sample-test-report.txt

```

---

## Test Coverage
- UI testing for login and dashboard validation  
- API testing for project creation  
- API + UI integration testing  
- Multi-tenant data isolation validation  
- Cross-browser and mobile testing approach (conceptual)  

---

## How to Run the Tests
> Note: This project focuses on test design and structure. Some integrations are conceptual.

1. Install dependencies:
```

pip install pytest playwright

```

2. Install Playwright browsers:
```

playwright install

```

3. Run tests:
```

pytest

```

---

## Assumptions
- Test users exist for each tenant and role
- Authentication tokens are pre-generated
- 2FA is disabled for test users or handled via mocks
- BrowserStack credentials and devices are preconfigured
- Test data cleanup is handled via API or scheduled jobs

---

## Key Design Decisions
- Used **API-based setup** for faster and reliable test data creation  
- Applied **Page Object Model** concepts for UI tests  
- Focused on **explicit waits and auto-waiting assertions** to reduce flakiness  
- Designed tests to be **CI/CD friendly and scalable**

---

## Notes
This repository emphasizes **testing strategy, framework design, and problem-solving ability**.  
The implementations are intentionally lightweight to highlight clarity of thought and real-world testing considerations.

---

## Author
Disha Patil  
QA Automation Engineering Intern – Case Study Submission
