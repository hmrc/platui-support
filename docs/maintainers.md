## Background
[platui-support](https://github.com/hmrc/platui-support) is a Github repository that exists to allow users of PlatUI 
libraries, services, and other tools, to raise both bug tickets and feature requests via Github. The issues raised are 
visible here: https://github.com/hmrc/platui-support/issues

## Issue types
When an issue is created, it will be created using one of two templates defined as YAML in the repo: 
1. [bug report](https://github.com/hmrc/platui-support/blob/main/.github/ISSUE_TEMPLATE/bug-report.md)
2. [feature request](https://github.com/hmrc/platui-support/blob/main/.github/ISSUE_TEMPLATE/feature-request.md) 
      
The documentation for creating new templates for issues in Github is [here](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository).

## What should happen once a ticket is raised?
1. PlatUI Developer on support rota checks board daily for new issues raised.
2. PlatUI Developer adds one of the following labels:
   1. `platform testing`, or 
   2. `triage`
3. If the label is `platform testing`, alert the `@testleads` group in the Slack channel `#int-team-plat-ui` 
4. If the label is `triage`:
   1. Reply to the original ticket with the [standard copy](https://github.com/hmrc/platui-support/blob/main/docs/template-responses.md)
     for `triage`
   2. Read through the ticket, and see if it clearly falls into one of the following categories:
      1. `accepted: bug` (if this is clearly a bug)
         1. Create a bug ticket in Jira 
         2. If the ticket seems like BAU, apply the `BAU` label to the **Jira ticket** 
         3. Add a link in the Jira ticket to the **Github issue** (for closing once complete)
         4. Apply the label `accepted: bug` to the **Github Issue** 
         5. Reply to the original ticket with the [standard copy](https://github.com/hmrc/platui-support/blob/main/docs/template-responses.md)
            for `accepted: bug` including the Jira ticket number 
         6. Alert the @hobbit group in the Slack channel `#int-team-plat-ui`
      2. `invalid`
         1. Apply the label `invalid` 
         2. Reply to the original ticket with the [standard copy](https://github.com/hmrc/platui-support/blob/main/docs/template-responses.md)
            for `invalid` 
      3. `cantfix` 
         1. Apply the label `cantfix` 
         2. Reply to the original ticket with the [standard copy](https://github.com/hmrc/platui-support/blob/main/docs/template-responses.md)
            for `cantfix`
      4. `wontfix`
         1. Apply the label `wontfix`
         2. Reply to the original ticket with the [standard copy](https://github.com/hmrc/platui-support/blob/main/docs/template-responses.md)
            for `wontfix`
   3. If the ticket looks as though it could be a valid candidate for development, discuss in Slack whether one of the
      following two labels should be used:
      1. `accepted: task`
         1. Create a `task` ticket in Jira 
         2. Add a link in the Jira ticket to the Github issue (for closing once complete)
         3. Apply the label `accepted: task` to the Github Issue
         4. Reply to the original ticket with the [standard copy](https://github.com/hmrc/platui-support/blob/main/docs/template-responses.md)
            for `accepted: task` including the Jira ticket number 
         5. Alert the `@hobbit` group in the Slack channel `#int-team-plat-ui`. It can then be added to the backlog as 
            per usual process.
         6. Once the Jira ticket is complete, close the Github issue
      2. `accepted: spike`
         1. Create a spike ticket in Jira
         2. Add a link in the Jira ticket to the Github issue (for closing once complete)
         3. Apply the label `accepted: spike` to the Github Issue
         4. Reply to the original ticket with the [standard copy](https://github.com/hmrc/platui-support/blob/main/docs/template-responses.md)  
            for `accepted: spike` including the Jira ticket number
         5. Alert the `@hobbit` group in the Slack channel `#int-team-plat-ui`. It can then be added to the backlog as 
            per usual process.
         6. Once the Jira ticket is complete, close the Github issue
