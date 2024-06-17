FinOps Open Cost and Usage (FOCUS) Contributing Policy
-------------------------------------------------------

This document provides the default contribution policy for datasets, software, specifications and other documents developed using the Community Specification process in a repository (each a “Working Group”) as part of the FOCUS Project. Additional or alternate contribution policies may be adopted and documented by each Working Group in the Working Group Charter if necessary.

Contributions will largely follow the [Community Specification Contribution Policy 1.0](https://github.com/CommunitySpecification/Community_Specification/blob/main/6._Contributing.md)

## 1.	Contribution Guidelines

This Working Group accepts contributions via pull requests (previously linked to an Issue agreed by the group). The following section outlines the process for merging contributions to the specification.

**1.1.	Issues**  Issues are used as the primary method for tracking anything to do with this specification Working Group.

**1.1.1.	Issue Types**  There are four types of issues (each with their own corresponding label):

**1.1.1.1.	Discussion Topic:** These are support or functionality inquiries that we want to have a record of for future reference. These can turn into "Spec Change" issues depending on the outcome of a discussion.

**1.1.1.2.	Proposal:** Used for items that propose a new ideas or functionality that require a larger discussion. This allows for feedback from others before a specification change is actually written. 

**1.1.1.3.	Spec Change:** These track specific spec changes until they are completed. Each spec change will be placed into a milestone once triaged.

**1.1.1.4. FinOps Use Case Feedback:** Processes for introducing, discussing, and implementing new ideas or changes in specifications, including feedback on FinOps use cases not supported by the current specification.

## 2.	Issue Lifecycle

The issue lifecycle is mainly driven by people assigned to the Issue. All issue types follow the same general lifecycle. Differences are noted below.

**2.1.	Issue Creation**

The submitter must select one of the issue templates (Discussion Topic, Proposal, Spec Change, or FinOps Use Case Feedback, etc) when submitting an issue and fill out the details in the template.

**2.2.	Triage**

The Maintainers will triage the issue and apply additional necessary fields and labels. This includes fields for target release, category, and metadata.

(If needed) Clean up the title to succinctly and clearly state the issue.

**2.3.	Discussion**

Feedback from the signed member community is expected and needed to ensure proposals and spec changes are sufficiently discussed prior to actioning. These can be brought up for discussion at the weekly member meetings at the appropriate time.

* Whoever is working on an issue should add his/her name to the issue. Issues MUST be linked to related Pull Requests. Use GitHub (Development) feature to link an Issue to a PR.

**2.4.	Issue Closure**

Issues can be closed by Editors or Maintainers. Issues linked to a merged PR will closed automatically.

**2.5. Minor corrections**

Minor corrections which do not materially change the document (such as the items listed below) can skip the issue creation process OR create a single running issue for a given version / milestone and reference it in pull requests.

Examples of minor corrections include:
* Spelling mistakes
* Miss labeled figures
* Spacing issues

## 3.	How to Contribute a Patch

The Working Group uses pull requests to track changes. To submit a change to the specification:

**3.1.** Create a topic branch prefixed with the issue-id included in the name (e.g. 4-resource-name-dimension). Ensure that the group has agreed to create a PR based on a particular Issue.

**3.2.** Modify the Specification to Address the Issue. This work can happen outside of the GitHub flow, as you and your team may want to collaborate live on the spec content before converting to GitHub and Markdown. Once you are mostly aligned within your group, you can convert the content to Markdown and submit the change to the topic branch created above.

**3.3.** Submit a Pull Request to merge the change from the topic branch to the 'working_draft' branch (see details below)

**3.4.** Notify the focus members about your pull request and ask for feedback. Address comments on your topic branch until reviewers have approved.

## 4.	Pull Request Workflow

The next section contains more information on the workflow followed for Pull Requests.

**4.1.	Pull Request Creation**

Pull requests must reference the issue they're working on in the title. The description can describe the changes and indicate whether a particular issue will have multiple pull requests or if this is for the complete scope.

The Maintainers and Group Members will decide how to move forward the PR. See below [Monitoring Porject Status](monitoring-project-status)

Creating an issue for a minor correction might be overkill. In this case, the details provided in the pull request description would suffice. See section [Minor corrections](#2.5.-minor-corrections) for details

**4.2. Triage:** 

* During triage, the assigned Maintainers will apply the proper fields and labels to the PR. Once all housekeeping tasks are done, this should include a milestone, category, and an 'awaiting review' label.

**4.3. Work in Progress:** 

* At this stage, the Working Group critically evaluates the pull request to understand the issue and explore potential solutions thoroughly.
* Contributors should actively engage in discussions and revisions. 
    >Labels indicating the approval criteria will be assigned to guide evaluation.

**4.4. Review & Approval:** 

* All reviews will be completed using the Review and Approval process:

* **COMMENTS**: 
    * `COMMENT`: It should be used when there are questions about the change that should be answered, but that don't involve spec changes. This type of `COMMENT` does not count as approval.
    * `CHANGES REQUESTED`: This comment indicates that changes to the spec need to be made before they will be merged.
    * `OBJECTION`: This comment SHOULD be used sporadically as convey a strong disagrement with the proposal and it cannot be merged as it is. If a pull request receives an `OBJECTION` the submitter MUST provide written details about the nature of this `OBJECTION`.

* **APPROVAL CRITERIA:**
    * During the Work in Progress phase, the group should establish and agree on the approval criteria for each pull request, denoted by a specific label. The criteria are as follows:

        * **Editorial & Bug:** These can be merged by the Editor(s), Maintainers directly, without needing full group consensus.

        * **Review Process:** A pull request can be merged if, after being reviewed for a specified number of days (X), it secures enough approvals from Members (Y) and Maintainers (Z), with no objections raised.

        >Final merging requires the designated Maintainer's approval, with Editors incorporating feedback from all reviews into the final decision.

**4.5. Merge or Close:** 
* An Approved pull request should stay open until the designated Maintainer merges the pull request.
* Pull requests can be closed by the author without merging.
* Pull requests may be closed by a Maintainer if the decision is made that they are not going to be merged.


## 5. Monitoring Project Status

Access the project board at [FOCUS WG](https://github.com/orgs/FinOps-Open-Cost-and-Usage-Spec/projects/5) to view the overall status, contributions, and pending tasks. The project contains the following stages:

* **Creation & Triage:** WG members submit issues and PRs for evaluation, with Maintainers triaging them to determine their impact, urgency, and whether to assign them to a Task Force or the Parking Lot.
* **Parking Lot:** Items deemed valuable but not immediately actionable are placed here, awaiting further engagement and eventual processing.
* **Work In Progress:** Task Forces actively discuss and refine Issues and PRs, focusing on problem-solving and solution exploration, with contributors encouraged to participate in discussions.
* **Review & Approval:** Items undergo a thorough review to ensure they meet the group's standards, with contributors expected to address comments and make necessary revisions promptly.
* **Merged or Closed:** Contributions that meet approval criteria are merged, marking their successful addition, while those that don't are closed, providing learning opportunities for future submissions.

## 6. Release Planning
For a detailed roadmap of the specification's development, please see the [RELEASE PLANNING](https://github.com/FinOps-Open-Cost-and-Usage-Spec/FOCUS_Spec/blob/working_draft/RELEASE-PLANNING.md) document in the repository. 

## 7. Questions?

If you have any questions or need further guidance, feel free to open an issue for discussion or contact the project maintainers directly.

## 8. Final Notes

- **Patience is Key:** The specification development process is thorough and can take time. Please be patient as the WG and community work through the stages.
- **Feedback is a Gift:** Whether positive or negative, feedback is an opportunity to improve. Embrace it.

Thank you for contributing to the FOCUS Group projects. Your efforts help us to develop robust and effective specifications for the community.