FOCUS Operating Procedures
==========================

# 1\. Introduction

  This document provides the working procedures used by the Joint Development Foundation Projects, LLC, FinOps Open Cost and Usage Specification (FOCUS) Project. The [project charter](https://github.com/FinOps-Open-Cost-and-Usage-Spec/foundation/blob/main/FOCUS_-_Membership_Agreement_Package_for_use.pdf) establishes the terms upon which this project operates. This operational proceedure document outlines how the members of the project adhere to these terms. Terms in this document do not override the Project Charter, if there is any ambiguity between this document and the [project charter](https://github.com/FinOps-Open-Cost-and-Usage-Spec/foundation/blob/main/FOCUS_-_Membership_Agreement_Package_for_use.pdf).

# 2\. Governance

## 2.0 Membership

  All contributors to the FOCUS work products MUST sign the [FOCUS Series Membership Agreement](https://github.com/FinOps-Open-Cost-and-Usage-Spec/foundation/blob/main/FOCUS_-_Membership_Agreement_Package_for_use.pdf).

  Membership is between FOCUS Project and the Employer of any contributing person.

## 2.1 Organization Structure

![Org Structure](images/org_structure.png?raw=true "Org Structure")

### 2.1.1 Steering Committee
  
  The Steering Committee roles, responsibilities, and processes are covered in [steering_committee.md](steering_committee.md).

### 2.1.2 Marketing Committee Team

  There will be no Marketing Committee within the FOCUS Project.
  The FinOps Foundation will provide marketing and other Shared Services as the project’s funding sponsor.

### 2.1.3 FOCUS Working Groups (FG)

  FOCUS Working Groups are chartered by the SC to handle one or more Work Packages. 
  Each FOCUS Group may extend this operational procedures with their own procedures as long as they do not conflict or overrule any of the processes in this document or the [project charter](https://github.com/FinOps-Open-Cost-and-Usage-Spec/foundation/blob/main/FOCUS_-_Membership_Agreement_Package_for_use.pdf). Typically each FOCUS Group will work in its own GitHub repository or a previously established GitHub repository within the FOCUS Project's GitHub Organization depending on the FOCUS Group's scope and deliverables. 

  A list of current and previous FOCUS Groups will be maintained in GitHub [focus_groups.md](focus_groups.md).
  We use the term FOCUS Working Group or FOCUS Group, or the abbreviation FG to refer to the FOCUS working groups in non-legal documentation. In CLAs, licenses and governance documents the term "Working Group". 

## 2.2 Organization Roles

  Organizational Roles involved in performing work within the Project or as a member of a FOCUS Working Group are:

  * FOCUS Group Contributor (Members)
  * FOCUS Group Editor
  * FOCUS Group Task Force Convener
  * FOCUS Group Maintainers
  * FOCUS Working Group Chair
  * FOCUS Group Support Staff


### 2.2.1 Contributor

FOCUS Group Member or Contributor is any individual creating content or commenting on an issue or pull request.

A FOCUS Contributor MUST read the Project documentation (e.g.: this operational document, contribution guidelines, [README](https://github.com/FinOps-Open-Cost-and-Usage-Spec/FOCUS_Spec/blob/working_draft/README.md), [CONTRIBUTING](https://github.com/FinOps-Open-Cost-and-Usage-Spec/FOCUS_Spec/blob/working_draft/CONTRIBUTING.md), and [RELEASE-PLANNING](https://github.com/FinOps-Open-Cost-and-Usage-Spec/FOCUS_Spec/blob/working_draft/RELEASE-PLANNING.md) documents) before attempting to submit an issue or pull request.

Contributors of the FOCUS project play a fundamental role in maintaining the collaborative and dynamic nature of the project by contributing to a variety of tasks. Their responsibilities encompass actively participating in members' and task force meetings, as well as engaging on GitHub. Contributors are crucial in labeling issues and pull requests, ensuring that these accurately reflect the content's nature and urgency. They are also involved in reviewing and providing constructive feedback on pull requests and issues, thus directly contributing to the refinement of project specifications and adherence to editorial guidelines.

In collaboration with Editors and Maintainers, Contributors help drive the evolution of project standards and participate in decision-making processes. Their engagement extends to the wider community through participation in discussions, staying informed about project updates and continuously enhancing their understanding of the evolving standards. Additionally, they provide essential input on project documentation, advocating for clarity, accuracy, and accessibility to ensure the documentation serves as a reliable resource.

### 2.2.2 Editor

Editors within the FOCUS project are tasked with the crucial role of overseeing the quality and accuracy of documentation. Editor responsibilities include incorporating and notifying Members of the incorporation of editorial pull requests, managing document updates, and maintaining standards across all project materials. Editors collaborate closely with team members and task force conveners to refine project specifications and integrate new findings effectively. Additionally, they are responsible for enforcing editorial guidelines to ensure all contributions meet the project's quality expectations and are in line with established practices. This role is pivotal in sustaining the integrity and progression of the FOCUS project's documentation efforts.

Editors are designated by the WG Chair and ratified by the Working Group Members.

### 2.2.3 Task Force Convener

Task Force Conveners are dedicated Maintainers within the FinOps FOCUS project who take on the responsibility of leading specific technical workstreams or topics within Task Forces. This leadership role involves guiding the development and implementation of specialized areas of the project, ensuring that all activities align with the project's broader objectives. Conveners are essential in driving detailed technical work, fostering collaboration, and maintaining high standards within their respective domains.


### 2.2.4 FOCUS Group Maintainer
  
  FOCUS Group (FG) Maintainers are a subset of the FG members who have been given write access to one or more FOCUS Working Group repositories within the FOCUS Project's Github organization. They will advance the day-to-day evolution of the specification and related work products.

  FG Maintainers are responsible for ensuring that the contents of documents and work products accurately reflect the decisions that have been made by the group, and that the specification adheres to formatting and content guidelines. 

  FG Chair(s) designates any FG Maintainer(s) for the FG. FG Maintainers are overseen by the FG Chair(s). Maintainer designations will be revisited at the discretion of the FG chair, typically at the conclusion of a release cycle.  

  To be designated as a Maintainer, individuals MUST:

   * Be involved as a Contributor consistently over at least one release cycle
   * Lead or significantly contribute technical content to a major Issue or PR 
   * Regularly participate in the Review & Approval process, including meeting discussions, issue/PR comments, asynchronous discourse (e.g. Slack), and PR approvals
   * Continue these activities through each release cycle

The FG Maintainer(s) MUST keep the project documentation up to date (e.g.: CONTRIBUTING, README and RELEASE PLANNING documents), and MUST have a good working knowledge of GitHub and other Project tools in use.

The FG Maintainer(s) MUST apply the [Review & Approval](/workflow-procedures.md#review--approval-process) process — covered in this document — to contributions submitted by the Working Group members.

  The FG Maintainer(s) SHOULD use GitHub Labels to indicate the type of “Review & Approval” assigned to each Pull Request.

  The FG Maintainer(s) SHOULD keep FOCUS project related communications with members  within GitHub using GitHub Issues or GitHub Pull Requests and corresponding GitHub comment functionality rather than one-to-one communications.

  The FG Maintainer(s) MAY suggest to close contributions that do not follow the rules, fail to meet the required quality standards, or are unrelated to the features in the scope of the Release Version under development.
Each Github Issue in the scope of the Release Version under development SHOULD be sponsored by at least one FG Maintainer.  At least one of the Maintainer sponsors of an Issue MUST:

- Assemble a team to consider and development the Issue
- Provide technical guidance and oversight for development
- Consistently attend the recurring Task Force meetings to which the Issue has been assigned
- Provide progress updates in recurring Task Force meetings
- Help unblock technical hurdles encountered during development
- Ensure the timely resolution of the Issue, based on the release planning timeline
  If an FG is working in Hybrid Contribution mode where some edits are being made outside of GitHub, the FG Maintainer will be responsible for exporting Github content into a FG working document format, and the subsequent porting of that updated working document content back into GitHub content. All access to exported working documents will be limited to the members of the FOCUS group only, no external contributions are allowed.

### 2.2.5 FOCUS Group Chair(s)

  Chair(s) are a subset of the FOCUS Group members and are responsible for organizing activities around work product(s) developed by the FG, including:
  
  * Developing
  * Maintaining
  * Updating

  In performing their tasks, FG Chair(s) SHALL maintain strict impartiality and act in the interest of the Project. 

  Chair(s) MAY limit the amount of time allocated to a particular agenda item or discussion point. 

  Chair(s) SHALL, after a reasonable period of discussion time, use means to quickly reach a decision including (but not limited to):

  * a statement of the Chair’s view of group consensus, which shall be accepted by the group if there are no objections
  * assignment of action items to progress the issue in as short a time period as possible
  * invite single or few objectors to no longer sustain their objections
  * informal voting
  * formal voting

  Chair(s) MAY require that new information be provided about an issue before earlier decisions can be reopened/revisited.

  The work and progress of the group is appropriately communicated through regular status reports to the SC. The Chair(s) MAY delegate tasks to other Chair(s).

### 2.2.6 Support Staff

  Where possible the FinOps Foundation staff will support the operations of the FOCUS Project. This may include:

  * Program Management
  * Project Management
  * Contractor time for dedicated contributions
  * Review and feedback on operational and technical content

  > Note: The following section outlines the responsibilities and tasks specific to the Program Manager role.

### FinOps FOCUS Project Task Organization
The FinOps FOCUS Project is structured to ensure efficient collaboration and coordination among various roles, each contributing to the overall success and continuous improvement of the project. The key tasks include creating, reviewing, and providing feedback on pull requests, managing labeling and triage, fostering community engagement, and maintaining comprehensive documentation. The project also emphasizes collaboration across teams, monitoring and maintaining project quality, and continuous learning. Stakeholder management is central to aligning the project with external needs and expectations. Each role, from Contributors to the Program Manager, plays a vital part in driving the project's mission forward, ensuring technical standards are met and fostering a supportive and inclusive community.

The table below outlines the key roles and responsibilities across eight critical areas of our project, designed to enhance collaboration, uphold standards, and promote community engagement.

<table border="1">
  <thead>
    <tr>
      <th>Grouped Tasks</th>
      <th>Contributors</th>
      <th>Editors</th>
      <th>Task Force Conveners</th>
      <th>Working Group Chair</th>
      <th>Maintainers</th>
      <th>Program Manager</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Create, Review & Feedback</td>
      <td>Create, review and comment on PRs and issues; Provide constructive feedback</td>
      <td>Approve editorial PRs; Enforce documentation standards</td>
      <td>Lead task force meetings to review technical contributions; Approve or reject contributions</td>
      <td>Lead working group meetings; Oversee comprehensive review processes; Address escalated issues</td>
      <td>Final review and merge of PRs; Ensure compliance with technical standards; Support Editors</td>
      <td>Oversee the overall review process; Ensure that project goals are met; Resolve conflicts</td>
    </tr>
    <tr>
      <td>Labeling & Triage</td>
      <td>Suggest labels for PRs and issues; Participate in labeling discussions</td>
      <td>Validate and refine labels for editorial consistency</td>
      <td>Oversee labeling specific to their task force; Ensure technical relevance of labels</td>
      <td>Monitor overall labeling practices across task forces; Ensure consistency</td>
      <td>Final approval of labels; Ensure proper categorization; Maintain label definitions</td>
      <td>Oversee labeling strategy; Ensure alignment with project milestones and objectives</td>
    </tr>
    <tr>
      <td>Collaboration & Coordination</td>
      <td>Collaborate with Editors and Maintainers; Engage in task force meetings</td>
      <td>Coordinate with Task Force Conveners; Support cross-team communication</td>
      <td>Facilitate collaboration within the task force; Coordinate with other conveners and the Working Group Chair</td>
      <td>Coordinate all task forces; Ensure alignment with project goals; Facilitate inter-task force collaboration</td>
      <td>Coordinate technical work across teams; Manage integration of contributions; Support cross-functional communication</td>
      <td>Ensure cohesive collaboration among all teams; Address process issues; Align team efforts with strategic goals</td>
    </tr>
    <tr>
      <td>Community & Engagement</td>
      <td>Engage with the community; Provide support to new contributors</td>
      <td>Encourage community participation; Facilitate discussions on editorial improvements</td>
      <td>Engage with stakeholders; Promote task force activities; Gather feedback</td>
      <td>Facilitate community discussions; Engage with external stakeholders; Promote the project's mission</td>
      <td>Foster community engagement; Support new contributors; Mentor community members</td>
      <td>Primary contact for stakeholders; Maintain stakeholder engagement; Promote project visibility and community involvement</td>
    </tr>
    <tr>
      <td>Documentation & Reporting</td>
      <td>Contribute to documentation; Advocate for clarity and accessibility</td>
      <td>Oversee document updates; Ensure accuracy and adherence to editorial standards</td>
      <td>Document task force activities; Ensure documentation reflects technical accuracy and completeness</td>
      <td>Ensure comprehensive documentation; Report task force activities to stakeholders; Address documentation gaps</td>
      <td>Maintain overall documentation; Keep communication channels updated; Ensure repository accuracy</td>
      <td>Comprehensive documentation; Prepare detailed status reports; Communicate project progress and challenges</td>
    </tr>
    <tr>
      <td>Monitoring & Maintenance</td>
      <td>Participate in monitoring discussions; Report issues</td>
      <td>Oversee editorial quality and consistency in documentation</td>
      <td>Monitor task force-specific contributions; Ensure ongoing relevance and accuracy</td>
      <td>Monitor overall project quality; Ensure task forces are meeting their objectives; Address quality issues</td>
      <td>Regular monitoring of repositories; Ensure technical accuracy and compliance; Implement best practices</td>
      <td>Monitor overall project health and adherence to timelines; Ensure milestones are met</td>
    </tr>
    <tr>
      <td>Learning & Improvement</td>
      <td>Stay informed and updated; Participate in training sessions</td>
      <td>Conduct editorial reviews; Recommend improvements based on best practices</td>
      <td>Facilitate technical learning within the task force; Implement improvements based on feedback</td>
      <td>Lead continuous improvement initiatives; Encourage innovation and the adoption of best practices</td>
      <td>Continuous learning and implementation of new technologies; Mentor team members</td>
      <td>Lead and promote a culture of continuous improvement; Facilitate training and professional development</td>
    </tr>
    <tr>
      <td>Stakeholder Management</td>
      <td>Provide feedback from the community; Participate in stakeholder discussions</td>
      <td>N/A</td>
      <td>Engage with stakeholders for feedback on task force outputs; Ensure stakeholder needs are addressed</td>
      <td>Serve as the primary liaison for stakeholders; Integrate stakeholder feedback into the project</td>
      <td>Engage with stakeholders on technical matters; Ensure stakeholder expectations are met</td>
      <td>Primary liaison for all stakeholder communication; Integrate feedback into strategic planning; Manage stakeholder relationships</td>
    </tr>
  </tbody>
</table>



# 3\. Membership Benefits

Table 3.0-1: Membership Benefits
| Benefit Area           | Benefit                                                                  | Steering | General | Contributor |
|------------------------|--------------------------------------------------------------------------|----------|---------|-------------|
| **Leadership**                                                                                                                       |
|                        | Eligible to participate in the Steering Committee                        |    Yes   |   N/A   |      No     |
|                        | Eligible for a Steering Committee Chair position                         |    Yes   |   N/A   |      No     |
|                        | Eligible for a FOCUS (Working) Group Chair position                      |    Yes*  |   N/A   |     Yes*    |
|                        | Eligible for a FOCUS (Working) Group Co-Chair position                   |    Yes*  |   N/A   |     Yes*    |
|                        | Eligible for a FOCUS (Working) Maintainer position                       |    Yes** |   N/A   |     Yes**   |
| **Participation**                                                                                                                    |
|                        | Eligible to join a Working Group                                         |    Yes   |   N/A   |     Yes     |
|                        | Eligible to join the Steering Committee Meetings                         |    Yes   |   N/A   |     No  |
| **Contribution**                                                                                                                     |
|                        | Contribute to Working Groups                                             |    Yes   |   N/A   |     Yes     |
|                        | Propose new working groups                                               |    Yes   |   N/A   |     Yes     |
|                        | May propose a Work Package                                               |    Yes   |   N/A   |     Yes     |
|                        | Counted towards minimum support quorum of a Work Package                 |    Yes   |   N/A   |     Yes     |
| **Voting**                                                                                                                           |
|                        | Approval of Publications, FOCUS (working) Group formation and Governance |    Yes   |   N/A   |      No     |
|                        | Vote in a Steering Committee vote                                        |    Yes   |   N/A   |      No     |
|                        | Vote in an FOCUS working group Supermajority vote                        |    Yes   |   N/A   |      No     |
|                        | Participate in discussions that reach consensus                          |    Yes   |   Yes   |     Yes     |
| **Access to Meetings**                                                                                                               |
|                        | Attend FOCUS (Work) Group meetings (any mode)                            |    Yes   |   Yes   |     Yes     |
| **Process Administration**                                                                                                           |
|                        | May propose the creation of a Working Group                              |    Yes   |   N/A   |     Yes     |
|                        | May appeal on technical issues                                           |    Yes   |   N/A   |     Yes     |
|                        | May appeal on procedural issues                                          |    Yes   |   N/A   |      No     |

\* The FOCUS SC may appoint individuals to these roles at its discretion
\*\* Approval by the FOCUS Group chairperson

# 4\. FOCUS Working Group (FG) 

Each FOCUS Working group may have an operational_proceedures.md document in the FOCUS Group GitHub respository that outlines their extensions to the processes and proceedures as long as they do not conflict or overrule any of the processes in this document or the [project charter](https://github.com/FinOps-Open-Cost-and-Usage-Spec/foundation/blob/main/FOCUS_-_Membership_Agreement_Package_for_use.pdf).

# 5\. FOCUS Process Flows

The workflow for all Working Groups covered by Patent Policy Option 4: W3C Mode will follow the guidelines in [w3c_mode_workflow.md](w3c_mode_workflow.md).

# 6\. Github Flows

## 6.1 GitHub Access Rights

Table 8.1-1: GitHub Access Rights
|     Role           |                                                              Access Rights                                                                |   |
|:------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------:|---|
| FOCUS Members      | TRIAGE - Can read and clone this repository, and push to a repository feature branches. Can also manage `GitHub Issues` and Pull Requests.|   |
| FOCUS Maintainers  | WRITE - FOCUS Member permissions, plus merge to `working_draft` branch and work on `GitHub Projects`.                                     |   |
| FOCUS Chair        | ADMINISTRATOR - FOCUS Maintainers permissions, they can also manage GitHub repository settings.                                           |   |

All Members are required to have 2FA enabled.

# 7\. Publication

## 7.1 GitHub

Published releases of the FG outputs will be maintained on the `main` branch of the respective FG REPOs. Each merge on this branch will be [tagged](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/managing-commits/managing-tags) with a version following Symantic Versioning. A [`RELEASE-PLANNING.md`](https://github.com/FinOps-Open-Cost-and-Usage-Spec/FOCUS_Spec/blob/working_draft/RELEASE-PLANNING.md) file will be maintained in the REPO to allow consumers of the FG outputs to determine what has changed and when releases occurred.

## 7.2 Website Releases

Some releases may be converted to web friendly formats (such as, PDF, HTML) and made available via the website [focus.finops.org](https://focus.finops.org/). These releases will clearly attribute the ownership of the material to the FOCUS Project and make it easy to identify the version of the publication.

# 8\. Documentation

## 8.1 Terminology and Conventions

### 8.1.1 Language

The default language for writing documentation is American English, English (United States).

### 8.1.2 Conventions

The keywords “MUST”, “MUST NOT”, “REQUIRED”, “SHALL”, “SHALL NOT”, “SHOULD”, “SHOULD NOT”, “RECOMMENDED”, “MAY”,
and “OPTIONAL” in this document are to be interpreted as described in [RFC2119].

Note: It is recommended to use the following terminology when writing Technical Specifications:

MUST: This word, or the terms "REQUIRED" or "SHALL", mean that the definition is an absolute requirement of the specification.

SHOULD: This word, or the adjective "RECOMMENDED", means that there may exist valid reasons in particular circumstances to ignore a particular item, but the full implications must be understood and carefully weighed before choosing a different course.
MAY: This word, or the adjective "OPTIONAL", means that an item is truly optional. One vendor may choose to include the item because a particular marketplace requires it or because the vendor feels that it enhances the product while another vendor may omit the same item. An implementation which does not include a particular option MUST be prepared to interoperate with another implementation which does include the option, though perhaps with reduced functionality. In the same vein an implementation which does include a particular option MUST be prepared to interoperate with another implementation which does not include the option (except, of course, for the feature the option provides.


Appendix A. - Checklist for Working Groups Chairs
=================================================

## A1. General Roles of Officers

- [ ] The chair has overall responsibility for the management of the group
- [ ] Co-chairs can provide full cover for the Chair - the intent being continuity of leadership to the group Chairs and co-chairs are to behave as a single team generating the group's vision
- [ ] Co-chairs provide the chair with a 2nd pair of eyes and ears to gauge the meeting
- [ ] Officers (Chairs, and Co-chairs) have to have visibility of all officers' communications to ensure transparency in the leadership (e.g. a leadership mailing list)
- [ ] Chair needs to drive the co-chairs' support

## A2. General Responsibilities

- [ ] Read, understand and follow the FOCUS processes as defined in the FOCUS operational proceedures, and ensure that all rules are followed. Where there is doubt, seek advice from the Steering Committee.
- [ ] Read, understand and follow any other related FOCUS procedures and guidelines. Familiarize themselves with IPR and Antitrust laws.
- [ ] Ensure execution and fulfillment of the mandate bestowed on the group through its charter and assigned work packages. Work closely with the Steering Committee to ensure the integrated approach required for FOCUS is achieved.
- [ ] Inform the parent group if the work of the group has been completed and recommend closure of the group.
- [ ] Interact with other groups as may be necessary to fulfill the group's own or another group's, charter and work packages.
- [ ] Interact with external fora (consistent with the liaison process) as necessary and report all interaction with external fora to the parent group.
- [ ] At all times act fully impartially in conducting the group's mandate and be prepared to work confidentially with a group member if they wish to express any concerns in private.
- [ ] Support, promote and keep updated the work packages as appropriate. Support the parent group with the responsibilities delegated.
- [ ] Conduct all group business in a fair, reasonable and open manner in accordance with the approved FOCUS processes and procedures.
- [ ] Chairs: Arrange for an agreed number of co-chairs to support the chair in the group leadership; arrange the task assignment for the chairs and co-chairs, delegate assigned tasks to, and supervise, the co-chairs.
- [ ] Co-chairs: Support the chair/convenor/interim chair in task assignment and execute delegated tasks and stand in for the chair as appropriate to fulfill the roles of the group.
- [ ] Internally structure the group as appropriate (e.g. create/modify/close sub-working groups, etc) to best fulfill the mandate.
- [ ] Conduct elections of and manage all sub-group officers consistent with officer election rules, and act as election officer in the strictest confidentiality.
- [ ] Regularly report group status and issues to the parent group, Steering Committee and members as required using the approved templates.
- [ ] Organize group meetings and phone conferences in a timely manner.
- [ ] Monitor your GitHub issues for requests to respond to questions from the public and provide responses. The chair will manage the creation, regular maintenance and obsolescence of their group's charter.

## A3. Meeting Responsibilities

- [ ] Moderate the meeting to ensure the work within the group progresses in a timely manner.
- [ ] When issues are raised within the meeting that the chair considers editorial and that may result in lengthy discussions, the chair should direct the editor to handle these issues outside the face to face session or conference call session subject to agreement on the resulting changes.
- [ ] For class Editorial PRs should be pre-reviewed, then in the meeting the chair should seek agreement and direct the editor to incorporate them in the document without further discussion during the meeting (unless non-editorial issues are raised).
- [ ] Organize and run the meetings in accordance with the processes and procedures of FOCUS as defined in the FOCUS operational proceedures and other guidelines, and ensure that all rules are followed.
- [ ] Where there is doubt, seek advice from the Steering Committee as appropriate. Issue a call for meeting agenda items in a timely manner as defined in the operational proceedures. Ensure that an agenda is prepared for every meeting (face to face or by conference call).
- [ ] When scheduling non-face-to-face real-time meetings such as phone conferences, have in consideration the time zone of the participants.
- [ ] Issue meeting agendas to fulfill the groups charter and work packages.
- [ ] Monitor the discussion and activity of the group and facilitate to ensure that decisions are reached through consensus in a timely manner.
- [ ] Monitor the discussion and activity of the group to ensure that no antitrust violations occur. Remind members regarding IPR and anti-trust at the beginning of each meeting.
- [ ] Ensure that meeting minutes are written, reviewed and published after each meeting.
- [ ] Prepare group status for the parent or Steering Committee meetings as required and ensure there is a representative from the working group who will handle these duties if the chair cannot be present, e.g. co-chair.
- [ ] Ensure that group GitHub repos are kept up to date in a timely fashion Manage the Specification Development Process.

## A4. Administrative Aspects

- [ ] Ensure the technical activities of the group are progressed in a timely manner in accordance with the processes and procedures defined in the "Rules of Engagement".
- [ ] Organize and run the meetings in accordance with the processes and procedures of FOCUS as defined in the FOCUS operational proceedures and other documents, and ensure that all rules are followed. Where there is doubt, seek advice from the parent group chair or ORG Officers as appropriate.

## A5. Technical Aspects

- [ ] Complete all reviews (Requirements, Architecture and Consistency) and address all issues raised in a timely manner.
- [ ] Conduct a full specification dependency analysis, and document the results in the specification and ensure the reference policy and guidelines are adhered to.
- [ ] Address all maintenance issues (PRs) in a timely manner.


Appendix B. - Definitions
=========================

If there is any ambiguity between these definitions here and in the above document, the definition in the above document should be considered correct.

| Term | Description |
|---|---|
| Committee Team |  A group chartered by the Steering Committee to perform specific support tasks |
| Editor(s) | A member of a Working Group who is responsible to edit and maintain a document. |
| e-Vote | Electronic Vote. |
| Issue(s) | An important topic or problem for debate or discussion. Normally, in Issues are tracked in Github. |
|      Steering Group member | A member of the Organization that has been selected by the FinOps Foundation Governing Board as a coordinator for the FOCUS Group Project activities.<br/>A Steering Group member is the person (or persons) responsible for the direction or movement of an Organization Working Groups. He/she/they are committed to improving, driving, and ensuring an outcome.<br/>A Steering Group member doesn’t necessarily have to be someone who writes the data specification. It could be someone who’s done a lot of work evangelizing the Organization, or written documentation that made the Organization more accessible to others. Regardless of what they do day-to-day, a Steering Group member is probably someone who feels responsible over the direction of the project and is committed to improving it.<br/>A Steering Group member is the final control point for contributions to a specification. Typically Pull Requests will be proposed by members and approved by the working group following consensus rules. The Steering Group member ensures the contribution rules are followed and that consensus has been met, especially for controversial or disputed contributions. The Steering Group member(s) should be the ones that merge the PR into the baseline (“main” branch). |
| Member(s) | A person that belongs to a company that has signed the Organization Membership Application, Project and Working Group Charter(s) |
| Membership Application |  A document that provides legal information about rights and obligations of being a member company of an Organization. |
| Participant | A Participant is any individual creating content or commenting on an Issue or Pull Request. |
| Project Charter | A legal document that describes the Organization Project. |
| Pull Request | It indicates what changes are suggested to a branch in a repository on GitHub. |
| Release | It is the distribution of the final version of a document or application. |
| Review & Approval |  A special process that is used to convey agreement or disagreement on a topic. |
| Semantic Versioning |  It is a versioning scheme to convey backwards or not backwards compatibility of a release. |
| Source Code | It is any collection of code, with or without comments, written using a human-readable programming language, usually as plain text. |
| Specification(s) | An act of describing or identifying something precisely or of stating a precise requirement. |
| Steering Committee |  A committee that decides on the priorities or order of business of the Organization. |
|  Working Group / FOCUS Group | A group of experts working together to achieve predefined objectives. The group formalizes its objectives and goals in a formal document, the Working Group Charter. |
| Working Group Maintainer |  A person selected by the Working Group which primary role is to facilitate consensus-building among the group members. |
| Working Group Charter |  A document that contains the scope, objectives and goals of a particular group. |
| Work Package | It is a group of related tasks within a project. Each Work Package can be broken down into one or more groups. |

Abbreviations
-------------

| Abv | Meaning |
|---|---|
| AD | Architecture Document |
| IPR | Intellectual Property Rights |
| WG | Working Group - this term may be confused with FinOps Foundation Working groups so use FG (defined below) |
| PR | Pull Request |
| REQ | Requirements |
| RD | Requirement Document |
| SUP | Supporting Document |
| TS | Technical Specification |
| SC | Steering Committee |
| CLA | Contributor License Agreement |
| F2  | FinOps Foundation |
| LF | Linux Foundation |
| FOCUS | FinOps Open Cost & Usage Specification Project |
| JDF | Joint Development Foundation |
| FG | FOCUS [Working] Group - used in place of WG/Working Group |
| REPO | GitHub Repository for the Project or FOCUS Group |
