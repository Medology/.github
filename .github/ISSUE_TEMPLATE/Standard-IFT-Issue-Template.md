---
name:  IFT Issue
about: Use this template for creating manually detected Intermittent Failing Tests
labels: Intermittently Failing Test
---

# Failed Scenario:
< The title of the failed test. >

## Error Step:
< The error that is thrown on CircleCI for the failed step. >

## CircleCI link:
< The link to the failed build on CircleCI. >

# Acceptance Criteria
- [ ] The test should not fail again.
- [ ] Proper stress testing has been done.

or

- [ ] If IFT cannot be reproduced, add the investigation report as a comment to the issue.

# Progress
### Ready for Ready to Work
- [ ] Make sure the issue is not already created by IFT automation script.
- [ ] The person who will Approve story identified

### Ready for Review
- [ ] Code implemented and built
- [ ] Testing implemented and passed

### Ready for Pre-Production QA
- [ ] Peer Reviews complete with all changes tested
- [ ] Special testing instructions noted
- [ ] Issue scored

### Ready for Deploy and Test
- [ ] PreProduction QA Test Passed

or
 
- [ ] Nothing to test

### Ready for Production QA
- [ ] Software deployed in production with no errors

### Ready for SM Approval
- [ ] Production QA Test Passed
- [ ] Manual Acceptance Test Results included in Comment

or
 
- [ ] Nothing to test

### Ready for PO Approval
- [ ] Issue complete and correct in all required sections
- [ ] All checkboxes checked
