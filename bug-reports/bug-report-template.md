
# Bug Report Template — Manual QA Portfolio

Use this template to report one reproducible defect at a time.

## Defect Information

| Field | Details |
|---|---|
| Bug ID | BUG-YYYY-NNN |
| Title | [Component] Concise description of the issue |
| Application | Swag Labs / SauceDemo |
| Related Test Case | TC-XXX |
| Environment | OS, browser/version, viewport |
| Reported By | Kiran Naik |
| Date Reported | YYYY-MM-DD |
| Status | New |
| Severity | To be assessed |
| Priority | To be assessed |

## Summary

Describe the observed problem in one or two clear sentences.

## Preconditions

List the conditions required before reproducing the issue, including login state, test data, and relevant application state.

## Steps to Reproduce

1. Navigate to the relevant page.
2. Perform the required action.
3. Enter the specified test data, if applicable.
4. Observe the result.

Add or remove steps as needed. The sequence must be sufficient for another tester to reproduce the issue.

## Expected Result

Describe the behaviour required by the application's documented or otherwise established requirements.

## Actual Result

Describe the behaviour observed during execution. Include the exact error message where applicable.

## Reproducibility

- Attempts: [Number]
- Successful reproductions: [Number]
- Intermittent or consistently reproducible: [Observed result]

## Impact Assessment

**Severity**
- Critical: Severe system failure or major critical capability loss.
- High: Major functional failure affecting an important workflow.
- Medium: Meaningful defect with limited impact or a reasonable workaround.
- Low: Minor usability, visual, or non-critical functional issue.

**Priority**
Assign based on business urgency, user impact, and release requirements.

Severity and priority must be evaluated separately.

## Supporting Evidence

- Screenshot/video: [Evidence filename or link]
- Test data: [Non-sensitive values only]
- Related logs: [If available]
- Execution environment: [Details]

## Related Information

- Related test case: [ID]
- Related issue or requirement: [If available]
- Workaround: [If verified, otherwise N/A]

## Retest Information

| Field | Details |
|---|---|
| Retest Date | Not yet retested |
| Retest Result | Not Run |
| Verified Build/Version | Not recorded |
| Notes | Pending a relevant fix |

## Reporting Rules

- Confirm the discrepancy is reproducible before reporting it as a verified defect.
- Do not invent requirements, results, or screenshots.
- Avoid including passwords, tokens, personal data, or confidential information.
- Use a concise, specific title.
- Describe the actual impact and attach evidence.
- Do not report expected application behaviour as a defect.
