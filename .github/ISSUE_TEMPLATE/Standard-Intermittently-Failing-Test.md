---
name: Flaky Test Issue
about: Use this template for tests that fail intermittently
labels: Intermittently Failing Test
---

## Description
< Include the name, scenario, path, etc of the failing test >

## Acceptance Criteria
- [ ] The cause of the failing test has been determined and fixed

or

- [ ] The flaky test could not be reproduced, but additional logging has been added

## Examples from CI
* Include links to failing builds

## Artifacts
< Upload artifacts from CI here so that when they are pruned in CI, the dev who takes this issue still has access to them >

## Subject Matter Experts
< list of subject matter experts for the domain of the flaky test and the tools it uses. e.g. if the test is on the Phone Order Page, written in Angular, and tested with Cypress, you should list SMEs for each of those here>

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
< If engineering requires notification instead of (or in addition to) the end user or if there is different information, then put the text here. Otherwise, indicate "N/A" >
< LINK TO PR GOES HERE >
