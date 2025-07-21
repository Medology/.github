---
name:  Technical Issue
about: Resolves a technical deficiency with the system or improves the system for engineering in some way
---

# Story

## Short Summary
`Short summary of the technical debt that makes this issue necessary`

You should include three sentences, each covering the following points:
* Succinct contextual explanation of the big-picture goal.
* Succinct description of the specific problem we are addressing.
* Succinct description of the goal of this issue.

For Example:

* We want to remove the CloudFlare workers, which rewrite URLs and response content.
* We need to make the pages accessible via the same URLs even without the Cloudflare workers.
* This issue is to modify WordPress' [CPTs](https://developer.wordpress.org/plugins/post-types/) so they are not prefixed with `/blog`.

## Acceptance Criteria
`A list of tasks required to consider this issue complete`

- [ ] Task 1
- [ ] etc

## Rationale: Pros vs. Cons
`What is the rationale for the change? What are the pros and cons of the acceptance criteria?`

### Pros
* Pro 1
* etc

### Cons
* Con 1
* etc

## Subject Matter Experts
`List of developers that would be considered to have in-depth info in or around the issue`

## Notes
`A list of resources or caveats that would be applicable to the issue`

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
releasenotes:
< if the Issue is something that could affect the end user, then put the text for the releasenotes Slack channel here. Otherwise. indicate "N/A" >

dev-important:
< If engineering requires notification instead of (or in addition to) the end user or if there is different information, then put the text here. Otherwise, indicate "N/A" >
< LINK TO PR GOES HERE >
