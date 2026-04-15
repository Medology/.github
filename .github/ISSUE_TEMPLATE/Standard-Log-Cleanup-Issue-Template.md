---
name:  Log Cleanup Issue
about: Investigate and resolve the log errors.
labels: Log Cleanup
---

## Short Summary

`Short summary of the error recorded in the logs.`
E.g. The route `/api/v1/order` is returning too many 404 lab not found errors.

### Link to Sentry error log or issue

https://healthlabs-tx.sentry.io/issues/XYZ

## Stats

### Severity:

`Critical, High, Medium, Low, Unknown`

### Frequency:

X occurrences in the last 30 days.

## Possible cause

`Please write the possible cause of this issue based on the analysis during the issue creation.`

## Acceptance Criteria

- [ ] A solution has been discovered and documented under this issue.
- [ ] The fix is made based on the solution discovered.

or

- [ ] This is an expected error log. No code changes needed.
- [ ] Documented the findings under this issue.

## Exploratory Testing
`A comprehensive list of the areas of this project that are affected by this PR`

The following API endpoints are affected by this change: (if this issue is for an API project)

* `API ROUTE`
* `API ROUTE`
* `etc`

The following features/pages are affected by this change: (If applicable)

* `PROJECT NAME - FEATURE NAME`
* `PROJECT NAME - FEATURE NAME`
* `etc`

Note: You should include all projects that are affected by this, not just the project that the PR was submitted to. For example, if you make a change that affects an AnalyteCare API endpoint, then you'll want to use our observability tools such as Google Cloud Logging to determine which clients are using that endpoint, and then coordinate with the SMEs (if necessary) to determine which features that project is using the API endpoint to facilitate, and list those here for QA to test.


## Announcement Message

dev-updates:
`<If engineering requires notification instead of (or in addition to) the end user or if there is different information, then put the text here. Otherwise, indicate "N/A">`
< LINK TO PR GOES HERE >
