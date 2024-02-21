FinOps Open Cost and Usage (FOCUS) Contributing Policy
-------------------------------------------------------

This document provides the default contribution policy for datasets, software, specifications and other documents developed using the Community Specification process in a repository (each a “Working Group”) as part of the FOCUS Project. Additional or alternate contribution policies may be adopted and documented by each Working Group in the Working Group Charter if necessary.

Contributions will largely follow the [Community Specification Contribution Policy 1.0](https://github.com/CommunitySpecification/Community_Specification/blob/main/6._Contributing.md)

## Contribution Guidelines

This Working Group accepts contributions via issues and  pull requests. The following section outlines the process for merging contributions to the specification.

## How to Contribute with Issues 
Issues are used as the primary method for tracking anything to do with this specification Working Group.

**Issue Types:**  There are four types of issues (each with their own corresponding label):
* **Discussion Topic:** A category for tracking inquiries or functionality discussions for future reference, which may evolve into specification changes.
* **Proposal, Spec Change, FinOps Use Case Feedback:** Processes for introducing, discussing, and implementing new ideas or changes in specifications, including feedback on FinOps use cases not supported by the current specification.

### Issue Lifecycle

The issue lifecycle is mainly driven by the Maintainer. All issue types follow the same general lifecycle. Differences are noted below.

#### **1. Issue Creation:**
The submitter needs to select one of the issue templates (Discussion Topic, Proposal, or Spec Change) when submitting an issue and fill out the details in the template.

#### **2. Triage:**
The Maintainers will apply additional necessary fields and labels for the issue. This includes fields for target, category, and metadata.

(If needed) Clean up the title to succinctly and clearly state the issue. Also ensure that proposals are prefaced with "Proposal".

#### **3. Discussion:**
Feedback from the signed member community is expected and needed to ensure proposals and spec changes are sufficiently discussed prior to actioning. These can be brought up for discussion at the weekly member meetings at the appropriate time.

   * Whoever is working on a "Spec Change" issue should either assign the issue to themselves or make a comment in the issue saying that they are taking it.
   * "Spec Change" issues should be connected to the pull request that resolves it. The topic branch and the pull request title should include the GitHub issue id.
   * "Proposal" and "Discussion" issues should stay open until resolved.

#### **4.	Issue Closure:**
The Editor or the maintainer can close an issue once the work has merged into the working branch.

#### **5. Minor corrections:**
Minor corrections which do not materially change the document (such as the items listed below) can skip the issue creation process OR create a single running issue for a given version / milestone and reference it in pull requests.
Examples of minor corrections include:
  * Spelling mistakes
  * Miss labeled figures
  * Spacing issues

## How to Contribute with a Pull Request
The Working Group uses pull requests to track changes. 

### Pull Request Lifecyle
To submit a change to the specification:

#### **1. Create a topic branch:** 
Prefixed with the issue-id included in the name (e.g. `4-resource-name-dimension`)

#### **2. Modify the Specification to Address the Issue:** 
This work can happen outside of the GitHub flow as you and your team may want to do live collaboration on the spec content before converting to GitHub and Markdown. Once mostly aligned within your group, you can convert the content to markdown and submit the change to the topic branch created above.

#### **3. Submit a Pull Request:** 
To merge the change from the `topic branch` to the `working_draft` branch (see details below).

#### **4. Notify the focus members:** 
About your pull request and ask for feedback. Address comments on your topic branch until reviewers have approved.

### Pull Request Workflow

The next section contains more information on the workflow followed for Pull Requests.

#### **1. Pull Request Creation:** 
Pull requests must reference the issue they're working on in the title. Description can be used to describe the changes and reference if a particular issue will have multiple pull requests or if this is for the complete scope.

    We welcome pull requests that are currently in progress. They are a great way to keep track of important work that is in-flight, but useful for others to see. 

    Creating an issue for a minor correction might be overkill. The details provided in the pull request description would suffice in this case. See bullet point *5 Minor corrections* in [How to Contribute with Issues](#how-to-contribute-with-issues) for details.

#### **2.	Triage:** 
The Maintainer in charge of triaging will apply the proper fields and labels for the issue. This should include a milestone, category, and an 'awaiting review' label once all housekeeping tasks are done.

#### **3. Work in Progress:** 
At this stage, the Working Group critically evaluates the pull request to thoroughly understand the issue and explore potential solutions.
    * Contributors should actively engage in discussions and revisions. 
    >Labels indicating the approval criteria will be assigned to guide evaluation.

#### **4.	Review & Approval:** 
All reviews will be completed using the Review and Approval process:

    * **COMMENTS**: 
        * `COMMENT`: It should be used when there are questions about the change that should be answered, but that don't involve spec changes. This type of `COMMENT` does not count as approval.
        * `CHANGES REQUESTED`: This comment indicates that changes to the spec need to be made before they will be merged.
        * `OBJECTION`: This comment SHOULD be used sporadically as convey a strong disagrement with the proposal and it cannot be merged as it is. If a pull request receives an `OBJECTION` the submitter MUST provide written details about the nature of this `OBJECTION`.

    * **APPROVAL CRITERIA:**
        * During the Work in Progress phase, the group should establish and agree on the approval criteria for each pull request, denoted by a specific label. The criteria are as follows:

            * **Editorial & Bug:** These can be merged by the Editor(s) directly, without needing full group consensus.

            * **Review Process:** A pull request can be merged if, after being reviewed for a specified number of days (X), it secures enough approvals from Members (Y) and Maintainers (Z), with no objections raised.

        >Final merging requires the designated Maintainer's approval, with Editors incorporating feedback from all reviews into the final decision.


#### **5.	Merge or Close:** 
An Approved pull request should stay open until the designated  Maintainer merge the pull request.
    * Pull requests can be closed by the author without merging.
    * Pull requests may be closed by a Maintainer if the decision is made that it is not going to be merged.
