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
`How is the end-user experience affected by this (if at all)? Any special setup or tools required?`

## Announcement Message
releasenotes: < if the Issue is something that could affect the end user, then put the text for the releasenotes Slack channel here. Otherwise. indicate "N/A" >

dev-important: < If engineering requires notification instead of (or in addition to) the end user or if there is different information, then put the text here. Otherwise, indicate "N/A" >
