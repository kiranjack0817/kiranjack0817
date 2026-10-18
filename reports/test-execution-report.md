
# Test Execution Report — Authentication Smoke Test

| Document Field | Details |
|---|---|
| Project | Manual QA Portfolio |
| Document ID | QA-TR-001 |
| Application | https://www.saucedemo.com/ |
| Prepared By | Kiran Naik |
| Execution Date | 2026-10-17 |
| OS | Windows 11 Pro |
| Browser | Google Chrome 155.0.8059.80 (64-bit) |
| Reported Screen/Viewport | 711 × 551 pixels |
| Test Scope | TC-001 to TC-006 |
| Report Status | Initial execution summary |

## 1. Objective

Record the observed outcomes of the initial authentication smoke test, including successful login, invalid login handling, required-field validation, locked-out account behaviour, and logout.

## 2. Execution Summary

| Metric | Result |
|---|---:|
| Planned Test Cases | 6 |
| Executed Test Cases | 5 |
| Passed | 5 |
| Failed | 0 |
| Blocked | 0 |
| Not Run | 1 |
| Pass Rate Among Executed Tests | 100% |

The pass rate is calculated from the five test cases reported as executed and passed. One planned test remains unexecuted and is excluded from the calculation.

These results reflect the tester's recorded observations. This summary is not evidence that the full application or all 24 planned test cases have passed.

## 3. Detailed Execution Results

| Test Case | Scenario | Status | Actual Result / Notes |
|---|---|---|---|
| TC-001 | Successful login | Pass | Tester reported successful login. Inventory page details and screenshot reference were not recorded. |
| TC-002 | Invalid password | Pass | Tester reported an error message and rejected login. Exact message and supporting evidence were not recorded. |
| TC-003 | Empty username | Pass | Reported message: `Epic sadface: Username is required` |
| TC-004 | Empty password | Pass | Reported message: `Epic sadface: Password is required` |
| TC-005 | Locked-out account | Not Run | Tester indicated the scenario was unavailable. Reattempt with the designated locked-out demo account is pending. |
| TC-006 | Logout | Pass | Tester reported successful logout. Exact destination and screenshot reference were not recorded. |

## 4. Defect Summary

No confirmed defects were reported during this execution session.

The login validation messages reported for TC-003 and TC-004 matched the expected outcomes defined in the test cases.

The exact error message and detailed evidence for TC-002 require improvement before treating the result as fully evidenced.

TC-005 has not been assessed because it was not executed with the designated test account.

## 5. Environment and Evidence Limitations

- The operating system and Chrome version were supplied by the tester.
- The reported dimensions were 711 × 551 pixels; whether these refer to the browser viewport or display resolution has not been confirmed.
- Screenshot and video evidence references were not provided for this initial run.
- Browser, OS, and viewport compatibility have not been established from this authentication-only session.
- The remaining test cases in the 24-case suite have not been assessed in this report.

## 6. Follow-up Actions

1. Re-run TC-005 using the designated locked-out demo account and record the observed message.
2. Capture the exact error message for TC-002 and verify the login remains rejected.
3. Record the inventory page and post-logout destination for TC-001 and TC-006.
4. Save screenshots using consistent filenames and reference them in the execution records.
5. Continue execution with product inventory, sorting, and cart test cases.
6. Update the execution metrics only when additional test cases have actually been executed.

## 7. Conclusion

The initial authentication smoke test has five reported passes, zero reported failures, and one test case not run.

The session provides an initial record of login validation behaviour. Additional test execution and supporting evidence are required before drawing broader conclusions about application quality.

## 8. Revision History

| Version | Change |
|---|---|
| 1.0 | Initial authentication execution summary |
