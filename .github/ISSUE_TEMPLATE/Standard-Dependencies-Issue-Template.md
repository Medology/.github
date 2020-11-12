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
releasenotes: Changes have been made that affect < some portion of the system >. Please let us know if you have any difficulties < doing whatever they do with that part of the system  >

devchat: < Dependency name > has been updated to <dependency target version> See <link to new features or this Issue > for available features and fixes
