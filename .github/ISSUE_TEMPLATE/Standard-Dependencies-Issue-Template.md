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

## Announcement Message
releasenotes:
< if the Issue is something that could affect the end user, then put the text for the releasenotes Slack channel here. Otherwise. indicate "N/A" >

dev-important:
< If engineering requires notification instead of (or in addition to) the end user or if there is different information, then put the text here. Otherwise, indicate "N/A" >
< LINK TO PR GOES HERE >
