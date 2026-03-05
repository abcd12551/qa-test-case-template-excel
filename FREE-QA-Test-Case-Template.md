# Free QA Test Case Template

Use this simple template to document core functional test cases quickly.

## Template Fields

| Field | Description |
|---|---|
| Test Case ID | Unique ID (e.g., TC-001) |
| Module / Feature | Area under test |
| Test Scenario | High-level scenario |
| Preconditions | Required setup before execution |
| Test Data | Input data needed |
| Test Steps | Step-by-step actions |
| Expected Result | What should happen |
| Actual Result | What actually happened |
| Status | Pass / Fail / Blocked / Not Run |
| Severity (if Fail) | Low / Medium / High / Critical |
| Priority | Low / Medium / High |
| Environment | Browser/device/app version |
| Executed By | Tester name |
| Execution Date | Date of run |
| Notes / Defect ID | Extra notes or bug reference |

## Fillable Test Case Table

Copy this row block for each new test case.

| Test Case ID | Module / Feature | Test Scenario | Preconditions | Test Data | Test Steps | Expected Result | Actual Result | Status | Severity (if Fail) | Priority | Environment | Executed By | Execution Date | Notes / Defect ID |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| TC-001 | Login | Valid login | User is registered | email: user@example.com, password: ****** | 1. Open login page 2. Enter valid credentials 3. Click Login | User is redirected to dashboard |  | Not Run |  | High | Chrome 123 / macOS |  |  |  |
| TC-002 | Login | Invalid password | User is registered | email: user@example.com, password: wrong123 | 1. Open login page 2. Enter invalid password 3. Click Login | Error message is shown and login fails |  | Not Run |  | High | Chrome 123 / macOS |  |  |  |
| TC-003 | Password Reset | Reset request | User has access to email | email: user@example.com | 1. Open Forgot Password 2. Enter email 3. Submit request | Reset link is sent successfully |  | Not Run |  | Medium | Chrome 123 / macOS |  |  |  |

## Status Legend

- `Pass`: Behavior matches expected result.
- `Fail`: Behavior does not match expected result.
- `Blocked`: Test cannot continue due to dependency/issue.
- `Not Run`: Test not executed yet.

## Suggested Next Upgrade

For larger projects, add:

- Requirement traceability
- API and integration test cases
- Risk-based prioritization
- Test execution dashboard
- Defect workflow integration
