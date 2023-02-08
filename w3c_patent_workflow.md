W3C Patent Workflow for Working Groups
======================================

Workflow Overview
-----------------

In order to meet our W3C Patent requirements the following workflow has been outlined. All working groups working under this process must strictly follow this workflow.

![Document Release Workflow](images/FOCUS_Document_Release_Workflow_v1.0.0.png?raw=true "Document Release Workflow")

GIT Repository Configuration
------------------

In order to work within the W3C Patent process the following workflow has been outlined for all repositories working under the W3C Patent process inside the FOCUS organization.

Working group repos will have the following standard branches:

* `working_draft` (Equal to the "Working Draft" document status)
* `candidate_recommendation` (Equal to the "Candidate Recommendation" document status)
* `main` (Equal to the "Recommendation" document status)

The W3C Patent document statuses of "Last Call Working Draft" and "Proposed Recommendation" are reflected by Pull Requests to be reviewed and approved by the relevant groups.

Git tags using [Semantic Versioning 2.0](https://semver.org/spec/v2.0.0.html) will be used to mark the official releases.

![Git Workflow](images/git_workflow_v1.0.0.png?raw=true "Git Workflow")

All development work will be completed in the `working_draft` branch or in topic branches that are strictly merged back into the `working_draft` branch. When the specification hits development milestones and is ready to released a pull request is raised from the `working_draft` branch into the `candidate_recommendation` branch. This pull request is reviewed by the working_group and FinOps Foundation Governing Board before it is approved and merged (**TBC**: who will perform the merge Working Group Chair?). 

Once a pull request is merged into the `candidate_recommendation` branch a notification period of 30 days is started. No content that has not been held in the `candidate_recommendation` branch can be progressed into the `main` branch. Any essential claims made against the release will be associcated with a GitHub Issue ticket and all tickets must be resolved before a pull request is able to be raised from the `candidate_recommendation` branch into the `main` branch.

Once a release has met the 30 day notification period the Steering Committee will review and confirm both the notification period and all essential claims have been resolved before the pull request is merged into `main`. Each merge into `main` will be tagged with a [Semantic Versioning 2.0](https://semver.org/spec/v2.0.0.html) tag. This will make it easily possible to switch to each previous version of the specification.

Minor corrections which do not materially change the document, such as:

* Spelling mistakes
* Miss labeled figures
* Spacing issues

Can be corrected via branch, pull request and merge. This is to avoid having to do the full 30 day release cycle to make these minor corrections.
