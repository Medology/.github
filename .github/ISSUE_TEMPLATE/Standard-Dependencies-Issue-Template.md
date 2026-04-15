---
name:  Dependencies Issue
about: Use this template for all Dependencies Issues, even those automatically generated
labels: dependencies
---

# Description
- Information about the dependency and its role in the project
- Current version - what are we running
- Target Version - what are we changing it to
- DependaBot PR link if available

## Features and fixes available
- List of important bug fixes, features or security patches
- List of the important changes in this version that could affect the workflow

## Additional information
- Additional information about the version update.
- Guideline that can be followed for the process

## QA Needs
< Indicate whether this item needs QA testing. For those that do, indicate any special setup or tool set the QA team might need. >

## Acceptance Criteria
< list of behaviors that must be present in order to satisfy the required functionality described above. >
- [ ] Dependency updated in the build
- [ ] Unit tests passing

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

dev-updates:
< If engineering requires notification instead of (or in addition to) the end user or if there is different information, then put the text here. Otherwise, indicate "N/A" >
< LINK TO PR GOES HERE >
