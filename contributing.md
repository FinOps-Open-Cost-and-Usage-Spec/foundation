FinOps Open Cost and Usage (FOCUS) Contributing Policy
-------------------------------------------------------

This document provides the default contribution policy for datasets, software, specifications and other documents developed using the Community Specification process in a repository (each a “Working Group”) as part of the FOCUS Project. Additional or alternate contribution policies may be adopted and documented by each Working Group in the Working Group Charter if necessary.

Contributions will largely follow the [Community Specification Contribution Policy 1.0](https://github.com/CommunitySpecification/Community_Specification/blob/main/6._Contributing.md)

## 1.	Contribution Guidelines

This Working Group accepts contributions via pull requests. The following section outlines the process for merging contributions to the specification.

**1.1.	Issues**  Issues are used as the primary method for tracking anything to do with this specification Working Group.

**1.1.1.	Issue Types**  There are three types of issues (each with their own corresponding label):

**1.1.1.1.	Discussion Topic:** These are support or functionality inquiries that we want to have a record of for future reference. Depending on the discussion, these can turn into "Spec Change" issues.

**1.1.1.2.	Proposal:** Used for items that propose a new ideas or functionality that require a larger discussion. This allows for feedback from others before a specification change is actually written. All issues that are proposals should both have a label and an issue title of "Proposal: [the rest of the title]." A proposal does not require a milestone and can become a "Spec Change" once triaged.

**1.1.1.3.	Spec Change:** These track specific spec changes until they are completed. They can evolve from "Proposal" and "Discussion" items, or can be submitted directly. Each spec change will be placed into a milestone once triaged.

## 2.	Issue Lifecycle

The issue lifecycle is mainly driven by the Maintainer. All issue types follow the same general lifecycle. Differences are noted below.

**2.1.	Issue Creation**
The submitter needs to select one of the issue templates (Discussion Topic, Proposal, or Spec Change) when submitting an issue and fill out the details in the template.

**2.2.	Triage**

The Editor in charge of triaging will apply additional necessary fields and labels for the issue. This includes fields for target, category, and metadata.

(If needed) Clean up the title to succinctly and clearly state the issue. Also ensure that proposals are prefaced with "Proposal".

**2.3.	Discussion**

Feedback from the signed member community is expected and needed to ensure proposals and spec changes are sufficiently discussed prior to actioning. These can be brought up for discussion at the weekly member meetings at the appropriate time.

o	Whoever is working on a "Spec Change" issue should either assign the issue to themselves or make a comment in the issue saying that they are taking it.

o	"Spec Change" issues should be connected to the pull request that resolves it. The topic branch and the pull request title should include the GitHub issue id.

o	"Proposal" and "Discussion" issues should stay open until resolved.

**2.4.	Issue Closure**

The Editor or the maintainer can close an issue once the work has merged into the working branch.

**2.5. Minor corrections**

Minor corrections which do not materially change the document (such as the items listed below) can skip the issue creation process OR create a single running issue for a given version / milestone and reference it in pull requests.
Examples of minor corrections include:
* Spelling mistakes
* Miss labeled figures
* Spacing issues

## 3.	How to Contribute a Patch

The Working Group uses pull requests to track changes. To submit a change to the specification:

**3.1.** Create a topic branch prefixed with the issue-id included in the name (e.g. 4-resource-name-dimension)

**3.2.** Modify the Specification to Address the Issue. This work can happen outside of the GitHub flow as you and your team may want to do live collaboration on the spec content before converting to GitHub and Markdown. Once mostly aligned within your group, you can convert the content to markdown and submit the change to the topic branch created above.

**3.3.** Submit a Pull Request to merge the change from the topic branch to the 'working_draft' branch (see details below)

**3.4.** Notify the focus members about your pull request and ask for feedback. Address comments on your topic branch until reviewers have approved.

## 4.	Pull Request Workflow

The next section contains more information on the workflow followed for Pull Requests.

**4.1.	Pull Request Creation**
Pull requests must reference the issue they're working on in the title. Description can be used to describe the changes and reference if a particular issue will have multiple pull requests or if this is for the complete scope.

We welcome pull requests that are currently in progress. They are a great way to keep track of important work that is in-flight, but useful for others to see. If a pull request is a work in progress, it should be prefaced with "WIP: [title]". You should also add the wip label Once the pull request is ready for review, remove "WIP" from the title and label.

Creating an issue for a minor correction might be overkill. The details provided in the pull request description would suffice in this case. See section [Minor corrections](#2.5.-minor-corrections) for details

**4.2.	Triage**

The Editor in charge of triaging will apply the proper fields and labels for the issue. This should include a milestone, category, and an 'awaiting review' label once all housekeeping tasks are done.

**4.3.	Reviewing/Discussion**

* All reviews will be completed using the review tool.
* A "Comment" review should be used when there are questions about the change that should be answered, but that don't involve spec changes. This type of review does not count as approval.
* A "Changes Requested" review indicates that changes to the spec need to be made before they will be merged.
* Reviewers should update labels as needed (such as needs rebase).
* When a review is approved, the reviewer should add LGTM as a comment.
* Final approval is required by a designated Editor. Merging is blocked without this final approval. Editors will factor reviews from all other reviewers into their approval process.

**4.4.	Responsiveness** 

Pull request owner should try to be responsive to comments by answering questions or changing text. Once all comments have been addressed, the pull request is ready to be merged.

**4.5.	Merge or Close**

* A pull request should stay open until a Maintainer has marked the pull request as approved.
* Pull requests can be closed by the author without merging.
* Pull requests may be closed by a Maintainer if the decision is made that it is not going to be merged.
