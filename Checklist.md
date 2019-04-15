# Check List

- [ ] Update the README.md file
  - [ ] New functionality has been appropriately documented in the README.md
  - [ ] Update Installation Steps in the README.md files. Ensure to call out explicit deletes that occurred, and remove any previous callouts which no longer apply
  - [ ] Test Plans should be filled out to capture a few use cases and acceptance criteria
- [ ] Update the VERSIONS.yml file
  - [ ] Include the set of dependencies on other services / toolsets / etc, and their version numbers
  - [ ] List main workflows which have changed, such as ones called by Workflow Dispatcher or configured as Day 2 actions
- [ ] vRO code changes
  - [ ] All content that has been modified in vRO has had the version bumped
  - [ ] All new/modified code has been formally reviewed during the team Code Review sessions
  - [ ] Code Review items are to be document in the PR by the code reviewer
- [ ] PR description states the Rally User Story this change is associated with.
- [ ] PR has a clear single-line description of the change.  Multiple changes should come in as multiple PRs.
- [ ] PR has been informally tested in Test and contains all required content, tested by someone else on the development team who did not do the development
- [ ] PR has Approvers assigned
- [ ] PR Approvers should indicate their role in the overall process.  Roles can include:
  - [ ] Code Reviewer
  - [ ] Informal tester
