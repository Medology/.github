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

## Announcement Message
dev-important: < If engineering requires notification instead of (or in addition to) the end user or if there is different information, then put the text here. Otherwise, indicate "N/A" >
< LINK TO PR GOES HERE >
