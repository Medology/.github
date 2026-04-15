---
name:  Feature Issue
about: Use this template for all features
labels: Feature
---

# Story
**As a < Agent, Admin, or Patient> of <STDcheck, Healthlabs, UTITreatment and/or Manage >**, I need < some functionality expressed as the user of the app would express the need > so that < why do you need this >.

## Business Value  
< Complete description of the business value - why do we need to make this change - for the requested item. >

## Notes
< list of special notes or suggestions to the development team on the implementation of the changes. >  

## Acceptance Criteria
< list of behaviors that must be present in order to satisfy the required functionality described above. >

## Announcement Message
releasenotes:
< if the Issue is something that could affect the end user, then put the text for the releasenotes Slack channel here. Otherwise. indicate "N/A" >

dev-updates:
< If engineering requires notification instead of (or in addition to) the end user or if there is different information, then put the text here. Otherwise, indicate "N/A" >
< LINK TO PR GOES HERE >

# Proposed Solution  
< Narrative describing how the solution will be implemented including screen shots, data samples, API specification, architectural changes, etc. as appropriate for the type and scope of Issue. This solution must be reviewed with the requester before beginning implementation. Include any special instructions to QA for testing. > 

## Subject Matter Experts
< list of subject matter experts for this domain. If the SME from the end-user perspective is not the author, an end-user expert should be listed here. The Design, Dev, and QA teams should add experts here as appropriate. >



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

