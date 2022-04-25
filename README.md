
# platui-support
[platui-support](https://github.com/hmrc/platui-support) is a Github repository that exists to allow users of PlatUI 
libraries, services, and other tools, to raise both bug tickets and feature requests via Github.

If you would like to raise an issue for one of our libraries, services, or tools, you can do so via the [issues tab](https://github.com/hmrc/platui-support/issues).

## What is the process for raising a new issue?
1. Navigate to the **issues** tab: https://github.com/hmrc/platui-support/issues. You’ll need to be signed in to Github to 
   submit a new issue.
2. Check if there is an existing issue for the suggestion that you want to raise. You can comment on existing issues if 
   you have any additional ideas, or would like to be involved in the discussions. 
3. To create a new issue, click the green button **New issue**
4. Select one of the two types of issue, and click **Get started**:
   1. Bug report 
   2. Feature request
5. Fill in the requested information. Once you have filled out the template, click **Submit new issue** and your issue 
   will be saved to the board.You’ll be asked to provide information such as:
   1. Library or service name 
   2. Library version (where applicable)
   3. Description of the issue and steps to reproduce (for a bug)
   4. Related component (for a feature request)
   5. Additional information (if applicable)
6. Once you have submitted your issue, the following steps will happen:
   1. PlatUI will assign the label `triage` once we have seen it on the board (we try to check this board as part of our
      daily support tasks). 
   2. Once we have had time to investigate your issue, we will assign one of the following labels:
      1. `accepted: bug` (This has a linked Jira Bug ticket to fix)
      2. `accepted: spike` (This has a linked Jira Spike ticket to investigate)
      3. `accepted: task` (This has a linked Jira Task ticket to implement)
      4. `cantfix` (This is not something that can be fixed by PlatUI)
      5. `invalid` (This is not an issue with the library or service)
      6. `platform testing` (Related to Testing on the Platform)
      7. `wontfix` (This will not be worked on)
7. If your issue has been labelled as accepted, we will link to the Jira ticket on our backlog, where you can track. We 
   will leave your issue open on the Github issue board until we have finished work on it. 
8. If your issue has not been labelled as accepted, we will try to provide an explanation as to why we have not created 
   a Jira ticket in our backlog to work on it.

## Getting help
Please report any issues with this repo in Slack at `#team-plat-ui`.

## Useful Links
- [HMRC Design Patterns](https://design.tax.service.gov.uk/hmrc-design-patterns/) - documentation for the use of `hmrc-frontend` components
- [hmrc-frontend](https://github.com/hmrc/hmrc-frontend/) - reusable Nunjucks HTML components for HMRC design patterns
- [GOV.UK Design System](https://design-system.service.gov.uk/components/) - documentation for the use of `govuk-frontend` components
- [govuk-frontend](https://github.com/alphagov/govuk-frontend/) - reusable Nunjucks HTML components from GOV.UK

## Owning team documentation
Instructions for team members maintaining this repository can be found [here](https://github.com/hmrc/platui-support/blob/main/docs/maintainers.md).

