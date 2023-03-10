
# FinOps Open Cost and Usage Specification (FOCUS) - Technical Steering Committee (TSC)

The FOCUS TSC will be responsible for all technical oversight of the open source projects. In particular, the TSC is responsible for approving official FOCUS specification releases and coordinating between projects.

## Technical Charter and Code of Conduct

The FOCUS TSC is governed by the [Charter](FOCUS_-_Membership_Agreement_Package_for_use.pdf): confirm URL **, which establishes the Committee and its basic principles and procedures.  The charter is designed to provide the TSC the freedom to govern itself in an efficient manner. This document establishes TSC policies and procedures.

In addition, as provided under the Technical Charter, FOCUS will align with the FinOps Foundation [Code of Conduct](code_of_conduct.md) that applies to all FOCUS activities and spaces. If you believe there has been a violation of the Code of Conduct, please contact [hello@finops.org](mailto:hello@finops.org).

## About the FOCUS project

### What problem are we trying to solve?

There’s no standard way to normalize key cloud cost and usage measures across multiple Cloud Service Providers (CSPs), Software as a Service (SaaS) products, or license sellers. This creates challenges for stakeholders when making decisions and quantifying the business value of cloud. This project will define a consistent set of measures, describe their origins, and prescribe and approach for surfacing the corresponding billing data via a shared data schema that is serviceable across all billing sources.

This open specification will be critical for the FinOps community, especially as more and more service providers continue to enter the market with their own billing data formats and measures.

### Why are we building this as a specification?

The FinOps Foundation is the Sponsoring Project of FOCUS, but FOCUS will be a standalone specification Project to better protect and manage the intellectual property rights that will be necessary for users of the FOCUS Project outputs. In order for organizations to trust the specifications and reference implementations that result from the FOCUS Project, they must be able to rely upon the right to use these work products under the terms of license agreements.

Establishing a technical Project allows contributions, contributors, license rights, and any intellectual property rights to be clearly and precisely tracked over time. This ensures that those contributing to and relying upon the specification are protected.

### How to get started with FOCUS?

FOCUS will be developed using a hybrid contribution model, meaning that changes and additions may be proposed either via Github issues and pull requests or at FOCUS Working Group meetings. Github will be the official system of record for the Specifications and any other work products. The contribution model will be officially defined in the FOCUS repository.

The Project will have multiple tiers of membership once established, but will work toward consensus approval of changes in every case possible. If you have a technical contribution to make to the Project, please contact us using the link below. If you would like to review or license the specification, reference implementations or other work products, please continue to check back here in Feburary 2023 to review the details available at that time.

Also, please review the [Code of Conduct](code_of_conduct.md), [Scope](scope.md) files. Instructions for contributors are included in the [Contributing](contributing.md) file.

### Who develops and maintains FOCUS?

The specification is being developed by the [FinOps Foundation](https://www.finops.org) community with inspiration, guidance and resources from [Joint Development Foundation](https://www.jointdevelopment.org), the [Open Web Foundation agreements](https://openwebfoundation.org), the [Alliance for Open Media Patent License 1.0](https://aomedia.org/license/patent-license/), and the [Linux Foundation](https://www.linuxfoundation.org/).

### Contributions

Development of the FinOps Open Cost and Usage Specification (FOCUS) is managed by the [FOCUS Working Group](TBD). This is the primary place where work is done on the FinOps Open Cost and Usage Specification (FOCUS).

Developers who are covered under a signed spec membership agreement are able to contribute to any FOCUS spec or project.

## TSC meetings

The FOCUS TSC will meet monthly, at a time yet to be determined. Our goal is to meet regularly to address any agenda items quickly and openly.

To attend a FOCUS TSC meeting, you must follow the same process as other FOCUS meetings and open a PR to add your name to the list of attendees in the meeting agenda. If you have not signed the Membership Agreement you will be prompted to do so. You cannot attend until you have completed this document.

### Scope

The TSC provides technical oversight for all FOCUS development efforts within the scope of the project. This includes:

* Approving formal releases of the FinOps Open Cost and Usage Specification (FOCUS).
* Approving new projects and working groups.
* Creating, transferring, organizing, and renaming GitHub repos under the [FOCUS GitHub org](https://github.com/FinOps-Open-Cost-and-Usage-Spec).
* Resolving technical or community issues that span multiple projects, or are deadlocked within a project.
* Delegating decisions on publishing releases.

The scope of the TSC should not include decisions that can be made within one of the projects, unless there is a specific issue that cannot be resolved and requires mediation. In general, the TSC prefers that decisions be made at the lowest possible level.

#### Decision-making authority

The following table is a rough outline of who is responsible for decisions. In keeping with the principle that decisions should be made at the lowest possible level and as efficiently as possible, unless there is a specific escalation to the TSC.

| Decision | Who decides | Can it be delegated? |
|---|---|---|
| Create a new project or working group | TSC | No |
| Approve a Specification release | TSC | No |
| Release a reference implementation | TSC or maintainers | Yes |
| Adding a new repo in the FOCUS organization | TSC | No |
| Changes to this document | TSC | No |


## Who can participate on the TSC

TSC meeting are open to anybody who wishes to participate. Aside from items which require a formal vote (such as approving specification verions or elections), anyone who has signed a Specification Membership Agreement may participate in discussions and decisions. As defined in the charter, the TSC will use the consensus decision-making process as often as possible.

The TSC will also include a number of individuals who have been elected as members. These individuals are expected to be active participants on the TSC, and to be engaged and responsive on matters that require a formal vote.

You must add yourself to the meeting agenda via PR in order to be able to join a FOCUS meeting.

### TSC Members

The current members of the FOCUS TSC are:

| Name                                               | Affiliation           | Term begins | Term ends    |
| -------------------------------------------------- | --------------------- | ----------- | ------------ |
| TBD | TBD | TBD | TBD |

#### Emeriti

We thank all our prior TSC members for their contribution:

| Name                                               | Affiliation           | Term began  | Term ended   |
| -------------------------------------------------- | --------------------- | ----------- | ------------ |


### Becoming a TSC Member

The [Technical Charter](FOCUS_-_Membership_Agreement_Package_for_use.pdf) describes the composition of the TSC. The TSC memberships are managed by the FinOps Foundation Governing Board.

## Policies and procedures

The FOCUS TSC is governed by the [Technical Charter](FOCUS_-_Membership_Agreement_Package_for_use.pdf). The Charter provides a foundational structure for the TSC on topics such as its scope, how to make decisions, and how to make changes to itself.  At the same time, it grants the TSC a high degree of freedom when determining how to implement the policies of FOCUS.

The following policies and procedures have been adopted by the TSC.

### Making changes to this document

Pull requests against this document that do not conflict with the [Technical Charter](FOCUS_-_Membership_Agreement_Package_for_use.pdf) can be merged provided the following conditions have been met:

* There are no outstanding objections
* There are two approvals by TSC members (not including the author)
* The PR has been open for at least 72 hours
* The changes have been sent to the FinOps Foundation Governing Board for feedback.

Pull requests that change governance of the TSC (excluding the charter) must be open for at least 14 days.

An exception is made for errata or to update meeting logistics. These may be landed immediately, provided all EasyCLA checks have passed.

### Security policy

Security concerns that impact repos under the [FOCUS GitHub org](https://github.com/FinOps-Open-Cost-and-Usage-Spec) (including reference implementations and official tools) may be responsibly disclosed to the TSC via any current TSC member, with the expectation that they will be discussed and triaged by the TSC as a whole. You may reach a subset of current TSC members via [hello@finops.org](mailto:hello@finops.org).
 
Our goal is to provide complete, accurate, and actionable disclosures once a reported issue has been sufficiently understood and there has been a reasonable opportunity to deploy fixes responsibly. At no time should a TSC member release information on a pre-disclosed vulnerability to anyone besides other TSC members, Foundation staff, legal counsel, or required authorities unless there is consensus to do so. A TSC member may call for a formal vote to determine an appropriate path forward at any time in the process, if needed.

In the case of responsible disclosures, the TSC is expected to work in good faith toward a resolution that is in the best interest of the community, including coordinating with maintainers on pre-disclosure patches and the CVE process. As responsible and knowledgable stewards of the FOCUS ecosystem, the TSC is empowered to negotiate the priority level and timelines for announcements and fixes.

In the case of irresponsible disclosure, regardless of the circumstances, the TSC is expected to make themselves available to convene urgently and to decide upon a communications and action plan.

### Adding and archiving projects under the FinOps Open Cost and Usage Specification (FOCUS)

The TSC may add and archive specifications, projects, and their corresponding repositories by a majority vote.

The TSC is responsible for defining a policy and a naming convention for any repositories created or transferred into the [FOCUS Github org](https://github.com/FinOps-Open-Cost-and-Usage-Spec).

Each repository will be managed by the EasyCLA signature tool, ensuring that all contributors have agreed to the FOCUS Membership Agreement.

### Speaking on behalf of the FOCUS Project

FOCUS Contributors as individuals are welcome to express opinions and messages of political advocacy in any of their personal spaces (e.g. personal Twitter, blog) as well as within GitHub issues and PR discussions, provided it adheres to our [Code of Conduct](code_of_conduct.md). We require approval via FOCUS TSC vote prior to posting opinions or messages of political advocacy using the voice of the FOCUS project (e.g. within technical docs, project websites, project Twitter, READMEs, or anything merged into a git repository under the FOCUS organization).
