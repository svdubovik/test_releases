<!--
First of all, thank you for your contribution! 😄

New feature please send a pull request to feature branch, and rest to master branch.
Pull requests will be merged after one of the collaborators approve.
Please makes sure that these forms are filled before submitting your pull request, thank you!
-->

## Related issue link

JIRA URL: <JIRA_URL>

## Background and solution

<!--
1. Describe the problem and the scenario.
2. GIF or snapshot should be provided if includes UI/interactive modification.
3. How to fix the problem, and list final API implementation and usage sample if that is a new feature.
-->

### Apply Labels based on Change classification

| Change Type     | Label           |
| --------------- | --------------- |
| New Feature     | New Feature     |
| Bug fix         | Bug             |
| Refactoring     | Refactoring     |
| Breaking Change | Breaking Change |

## Self Check before Merge

⚠️ Please check all items below before review. ⚠️

- [ ] Doc is updated/provided or not needed
- [ ] Demo is updated/provided or not needed
- [ ] TypeScript definition is updated/provided or not needed
- [ ] PR Title will be used as a ChangeLog (Make sure it is proper)
- [ ] Test cases are written and code is 80% covered


These Labels will be mapped to the releases in below format

| Label           | Version Change |
| --------------- | -------------- |
| Bug Fix         | Patch          |
| New Feature     | Minor          |
| Breaking Change | Major          |
