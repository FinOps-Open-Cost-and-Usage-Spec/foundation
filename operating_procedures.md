FOCUS Operating Procedures
==========================

# 1\. Introduction

  This document provides the working procedures used by the FOCUS Project. 

# 2\. Governance

## 2.0 Membership

  All contributors to the FOCUS work products must be Members of FOCUS.

  Membership is between FOCUS Project and the Employer of any contributing person.

### 2.0.1 Membership Levels

  There are three Membership levels:

  * Steering Members
  * General Members (Currently not in use)
  * Contributing Members

### 2.0.2 Membership Requirements

  Steering Members of FOCUS are organizations that have been designated by the FinOps Foundation Governing Board as members and have signed the FOCUS Project CLA. 
  General Members of FOCUS are currently not in use.
  All organizations after the initial Members join as Contributing Members of FOCUS. Contributing Members are organizations that must sign the FOCUS Project CLA to become members.

## 2.2 Organization Structure

![Org Structure](images/org_structure.png?raw=true "Org Structure")

### 2.2.1 Steering Committee
  
  One of the more important duties of the Steering Committee (SC) is the approval of the Specifications and other works produced as a consensus product of the FOCUS Working Groups.

  The Steering Committee is initially composed of a representative of the founding members of the Organization and it has a single primary member representing each company. Additional SC members will be appointed by the FinOps Foundation Governing Board as specified in the FOCUS Project Governance document.

  Each Steering Committee meeting is called on a regular interval, although this interval can be ad-hoc as long as the proper notice is given.

  Proper notice of the Steering Committee (SC) meeting is given to its representatives including an agenda with the topics to be voted by the SC having been prepared with a proper notice period, typically 7 days.

  A meeting of the Steering Committee should have a quorum of more than one half of currently serving Steering Committee participants for any call to vote to proceed.

  Motions are made and accepted by a vote of the designated Steering Committee members. Members may debate the motion, make changes if thought fit, accept or reject the motion. It is an important principle that there is an opportunity for questions and clarifications of the motion in the process.

  The votes are taken only by the appointed representatives of the Steering Committee. Minutes of the meeting are taken to record the attendance, votes and their outcomes.

### 2.2.2 Steering Committee Approval

  The FinOps Foundation Governing Board has set the following criteria for the FOCUS Project Steering Committee make up.

  Criteria for appointment to the FOCUS Steering Committee from among FOCUS Members:
  *  One member from the F2 Staff/Linux Foundation to initialize the project
  *  At least 2 should represent Cloud Service Providers as producers of cloud billing data
  *  At least 2 should be Premier Members of FinOps Foundation
  *  At least 2 should be Consumers of the FOCUS work outputs and cloud billing data

  FinOps Foundation Governing Board designates all FOCUS Steering Committee members. The FinOps Foundation Governing Board may add/remove FOCUS Steering Committee members and reserve the right to alter the criteria.

### 2.2.3 Marketing Committee Team

  There will be no Marketing Committee within the FOCUS Project.
  Marketing and other Shared Services will be provided by the FinOps Foundation as the project’s funding sponsor.

### 2.2.4 FOCUS [Working] Groups (FG)

  FOCUS Working Groups are chartered by the SC to handle one or more Work Packages. 

  Both the FinOps Foundation and the FOCUS Project have “working groups”. There may be people in FOCUS working groups that will also be in FinOps Foundation working groups, so to keep them straight, we’ll use the term FOCUS Working Group or FOCUS Group, or the abbreviation FG to refer to the FOCUS working groups in non-legal documentation. In CLAs, licenses and governance documents the term "Working Group" will be used to avoid having to redline contract documents which already use this term. 

  Each FOCUS Group will generate its own Charter, with its own Scope and deliverables. Typically each FOCUS Group will work in its own Github repository or in a previously established Github repository within the FOCUS Project's GitHub Organization depending on the FOCUS Group's scope and deliverables. 

  A list of current and previous FOCUS Groups will be maintained in GitHub.

## 2.3 Organization Roles

  Organizational Roles involved in performing work within the Project or as a member of a FOCUS Working Group are:

  * FOCUS Group members (FG member)
  * FOCUS Group Maintainer
  * FOCUS Group Chair(s)
  * Support Staff

### 2.3.1 FOCUS Group members (FG member)

  An FG member is any individual creating content or commenting on an issue or pull request.

  FG members MUST read the Project documentation (e.g.: this operational document, contribution guidelines, README, Contributing, and Release Planning documents) before attempting to submit an Issue or Pull Request

  FG members are not allowed to fork a project to build a feature that has been rejected by the FG.

  FG members must only contribute to FGs content that is not protected by patents or is not likely to have essential claims made against it. Contributions MUST only come from Members who have signed the CLA.

### 2.3.2 FOCUS Group Maintainer
  
  FG Maintainers are a subset of the FOCUS Group members who have been given write access to one or more repositories within the FOCUS Project's Github Organization. They will advance the day-to-day evolution of the specification and related work products.

  FG Maintainers are responsible for ensuring that the contents of documents and work products accurately reflect the decisions that have been made by the group, and that the specification adheres to formatting and content guidelines. 

  Each FG will designate a FG Maintainer or FG Maintainers for that FG. FG Maintainers work on behalf of the Chair.

  The FG Maintainer(s) MUST keep the project documentation up to date (e.g.: contributing, readme and release planning documents).

  The FG Maintainer(s) MUST apply the "Review & Approval" process—covered in 6.1 of this document—to contributions submitted by the Working Group members.

  The FG Maintainer(s) SHOULD use GitHub Labels to indicate the type of “Review & Approval” assigned to each Pull Request.

  The FG Maintainer(s) SHOULD keep FOCUS project related communications with members  within GitHub using GitHub Issues or GitHub Pull Requests and corresponding GitHub comment functionality rather than one to one communications.

  The FG Maintainer(s) SHOULD close contributions that do not follow the rules, or meet the right quality or are related to features that are in the scope of the Release Version under development.

  If an FG is working in Hybrid Contribution mode where some edits are being made outside of GitHub, the FG Maintainer will be responsible for exporting Github content into a FG working document format, and the subsequent porting of that updated working document content back into GitHub content. All access to exported working documents will be limited to the members of the FOCUS group only, no external contributions are allowed.

  An FG may select a new FG Maintainer or FG Maintainers upon Approval of the FG members, with the approval of the FG’s Chair.

### 2.3.3 FOCUS Group Chair(s)

  Chair(s) are a subset of the FOCUS Group members and are responsible for organizing activities around work product(s) developed by the FG, including:
  
  * Developing
  * Maintaining
  * Updating

  FG Chairs are also responsible for determining consensus and coordinating any appeals. Each FG will designate one Chair for that FG. An FG may select a new or additional Chair(s) upon Approval of the Working Group members and Approval of the SC.

  In performing their tasks, FG Chair(s) SHALL maintain strict impartiality and act in the interest of the Project. 

  Chair(s) MAY limit the amount of time allocated to a particular agenda item or discussion point. 

  Chair(s) SHALL, after a reasonable period of discussion time, use means to quickly reach a decision including (but not limited to):

  * a statement of the Chair’s view of group consensus, which shall be accepted by the group if there are no objections
  * assignment of action items to progress the issue in as short a time period as possible.
  * invite single or few objectors to no longer sustain their objections. 
  * informal voting. 
  * formal voting

  Chair(s) MAY require that new information be provided about an issue before earlier decisions can be reopened/revisited.

  The work and progress of the group is appropriately communicated through regular status reports to the SC. The Chair(s) MAY delegate tasks to other Chair(s).

### 2.3.4 Support Staff

  Where possible the FinOps Foundation staff will support the operations of the FOCUS Project. This may include:

  * Program Management 
  * Contractor time for dedicated contributions
  * Review and feedback on operational and technical content

# 3\. Membership Benefits

Table 3.0-1: Membership Benefits
| Benefit Area           | Benefit                                                                  | Steering | General | Contributor |
|------------------------|--------------------------------------------------------------------------|----------|---------|-------------|
| **Pricing**                                                                                                                          |
|                        | Price                                                                    |    N/A   |   N/A   |     N/A     |
| **Leadership**                                                                                                                       |
|                        | Eligible to participate in the Steering Committee                        |    Yes   |   N/A   |      No     |
|                        | Eligible for a FOCUS (Working) Group Chair position                      |    Yes*  |   N/A   |     Yes*    |
|                        | Eligible for a FOCUS (Working) Group Co-Chair position                   |    Yes*  |   N/A   |     Yes*    |
|                        | Eligible for a FOCUS (Working) Maintainer position                       |    Yes** |    N/A  |     Yes**   |
| **Participation**                                                                                                                    |
|                        | Eligible to join a Working Group                                         |    Yes   |   N/A   |     Yes     |
|                        | Eligible to join the Steering Committee                                  |    Yes   |   N/A   |      **     |
|                        | Eligible to join the Marketing Team                                      |    N/A   |   N/A   |     N/A     |
| **Contribution**                                                                                                                     |
|                        | Contribute to Working Groups                                             |    Yes   |   N/A   |     Yes     |
|                        | Propose new working groups                                               |    Yes   |   N/A   |     Yes     |
|                        | May propose a Work Package                                               |    Yes   |   N/A   |     Yes     |
|                        | Counted towards minimum support quorum of a Work Package                 |    Yes   |   N/A   |     Yes     |
| **Voting**                                                                                                                           |
|                        | Approval of Publications, FOCUS (working) Group formation and Governance |    Yes   |   N/A   |      No     |
|                        | Vote in a Supermajority vote                                             |    Yes   |   N/A   |      No     |
|                        | Vote in an FOCUS (working) group vote                                    |    Yes   |   N/A   |     Yes     |
| **Access to Meetings**                                                                                                               |
|                        | Attend FOCUS (Work) Group meetings (any mode)                            |    Yes   |   N/A   |     Yes**   |
| **Process Administration**                                                                                                           |
|                        | May propose the creation of a Working Group                              |    Yes   |   N/A   |     Yes     |
|                        | May appeal on technical issues                                           |    Yes   |   N/A   |     Yes     |
|                        | May appeal on procedural issues                                          |    Yes   |   N/A   |      No     |

\* The FOCUS SC may appoint individuals to these roles at its discretion

\*\* Approval by the FOCUS Group chairperson

# 4\. FOCUS Working Group (FG) Meetings

FGs are encouraged to schedule regular conference calls.

The Meetings MUST be announced at least 2 days in advance for conference calls, and 1 month for face to face meetings. 

All the Project members are contractually bound to the IPR policy under terms of the Membership Application and these IPR Guidelines must be followed.

Meetings SHALL have an antitrust statement and an IPR call where a reminder of the IPR policy and the duties and obligations of members is provided.

A meeting attendee list MUST be produced for each meeting. This is necessary to determine which members can vote in a Supermajority vote, and to ensure all participants have signed appropriate CLAs.


## 4.1 FinOps Working Group Transition

Since late 2022, the FinOps Foundation Open Billing Working Group has been developing open billing standard outputs. 
Membership in this working group has varied and been open to members and practitioners in the FinOps community
All output from that working group was covered under a CC-by-4.0 contribution policy
All work outputs will be contributed by the FinOps Foundation to the FOCUS Project upon creation of the FOCUS Project by the two initial members signing the JDF.

### 4.1.1 Acceptance Period

Contributions from the FinOps Foundation will be placed into https://github.com/finopsfoundation/finops-open-cost-usage-spec/blob/main/specification_sheet_import.md during a period of 30 days, known as the “Acceptance Period”

Any person identified as being involved in previous working group meetings will be notified of this repository location and the acceptance dates. During this time, any contributor involved in the working group meetings from the FinOps Foundation should review the material. If during this period any person or organization would like to assert any patent or copyright claim, they may do so to remove offending material from the contribution

After the Acceptance Period, this FinOps Working Group Transition will be completed and no further relationship between the FinOps Foundation Working Group and FOCUS Group will be maintained. The FinOps Foundation Working Group will be closed.

### 4.1.2 Meetings

* The final FinOps Open Billing WG meeting was Wed Jan 25 at 4:30pm ET 
* First FOCUS Project meeting will be Feb 1, 2023 4:30pm ET
    * Entirely Q&A on new project setup
* The next six meetings will be weekly at 4:30pm ET on Wednesdays
    * Open to public, information provided, no participation except for members
* After these six meetings the FinOps Foundation Working Group will be closed.
* Later meetings by invite only weekly working sessions
* Monthly or quarterly update meetings to follow for public involvement
* Definitive schedule will be set by Steering Committee

## 4.2 Meeting Agenda

Each Meeting of an FG SHALL have a published Agenda published in a Google document and linked in the FOCUS Group Github repository.
Meeting agenda is available here: [Agenda](https://docs.google.com/document/d/1ZmHoBRPm1krxiajMMzi72UcJS4Ux2RlIy4Kxjdg3Oyo/)

## 4.3 Meeting Minutes

Each meeting of an FG shall record its minutes, including attendee list, in the designated Github repository for the FG. 

Because FG meetings are expected to include members from many time zones regularly, each FG may elect to record its meetings using Zoom or similar meeting software. Links to these recordings SHALL be posted to the Github repository for the FG for no more than 60 days, before the recordings are deleted. Meeting minutes should be taken and posted in a Google document prior to meeting recordings being deleted. 
Meeting minutes are captured in-line in the agenda, and is available here: [Agenda](https://docs.google.com/document/d/1ZmHoBRPm1krxiajMMzi72UcJS4Ux2RlIy4Kxjdg3Oyo/)

# 5\. Technical Decision Making

## 5.1 Consensus-Based Decision Making

Working Groups make decisions through a consensus process (“Approval” or “Approved”). While the agreement of all Participants is preferred, it is not required for consensus. Rather, the FOCUS Group Maintainer will determine consensus based on their good faith consideration of a number of factors, including the dominant view of the FOCUS Group members and nature of support and objections. The FOCUS Group Maintainer will document evidence of consensus in accordance with these requirements. Consensus will not be deemed to have been met in the event of a sustained objection from one or more FOCUS Group members.

## 5.2 Appeal Process

Decisions may be appealed via a pull request or an issue, and that appeal will be considered by the FOCUS Group Maintainer in good faith, who will respond in writing within a reasonable time.

## 5.3 Ways of Working

Inspired by American National Standards Institute’s (ANSI) Essential Requirements for Due Process, FGs must adhere to consensus-based due process requirements. These requirements apply to activities related to the development of consensus for approval, revision, reaffirmation, and withdrawal of specifications. Due process means that any person (organization, company, government agency, individual, etc.) with a direct and material interest has a right to participate by: a) expressing a position and its basis, b) having that position considered, and c) having the right to appeal. Due process allows for equity and fair play. The following constitute the minimum acceptable due process requirements for the development of consensus.

### 5.3.1 Openness

Participation shall be open to all persons who are directly and materially affected by the activity in question. There shall be no undue financial barriers to participation. Voting membership on the consensus body shall not be conditional upon membership in any organization, nor unreasonably restricted on the basis of technical qualifications or other such requirements. Membership in a FOCUS Group’s parent organization, if any, may be required.

### 5.3.2 Lack of Dominance

The development process shall not be dominated by any single interest category, individual or organization. Dominance means a position or exercise of dominant authority, leadership, or influence by reason of superior leverage, strength, or representation to the exclusion of fair and equitable consideration of other viewpoints.

### 5.3.3 Balance

The development process should have a balance of interests. Participants from diverse interest categories shall be sought with the objective of achieving balance.

### 5.3.4 Coordination and Harmonization

Good faith efforts shall be made to resolve potential conflicts between and among deliverables developed under FOCUS Groups and existing industry standards.

### 5.3.5 Consideration of Views and Objections

Prompt consideration shall be given to the written views and objections of all Participants.

### 5.3.6 Written procedures

This governance document and other materials documenting the Community Specification development process shall be available to any interested person.

As part of their responsibilities defined in from FG Chair(s), Chair(s) need to ensure efficient and effective decision-making:
The decision making process in FGs is intended to be as inclusive as possible. FGs shall attempt to use consensus to make decisions.
If consensus cannot be reached, voting mechanisms MAY be used. Formal notice SHALL be given for decision making, e.g.:Inclusion of a document on an agenda, proposing a specific decision to be taken (e.g. Pull Request). Inclusion of an item directly in the agenda (e.g. proposed next meeting date).
Items proposed for approval via the group mailing list (e.g. agreement a document revision). Inclusion of a document for decision in an electronic Review, Comment and Approval event Inclusion of a document for decision in an e-vote (Supermajority) vote.
The above list is not exhaustive.

There SHALL be no distinction in the decision-making merit of real-time or non-real-time meetings.

In real-time meetings, consensus can be determined by receiving no sustained objections to a proposal.

In non-real-time meetings, consensus SHOULD be developed using Review, Comment and Agreement periods, e.g. using Review and Approval 

Proposals SHALL be available for a reasonable period for review.

## 5.4 Seeking Consensus

Groups shall endeavor to reach consensus on all decisions.

Informal methods of reaching consensus are encouraged (e.g. a show of hands).

Groups SHOULD attempt to ensure contributions relating to the same subject matter are considered together before being disposed of.

However the FOCUS Group chair SHALL ensure that progress is not delayed by unavailable contributions or participants. Agreement SHALL be sought in all forms of meeting.

## 5.5 Handling objections when seeking consensus

Objections from a small minority SHOULD be minuted and the objecting delegates SHOULD be questioned if having their objections minuted is sufficient and they agree to not sustain their objections.

If such agreements are secured, then there is consensus for approving the proposal.

If such agreements are not secured, then the proposal is not agreed and further action SHALL be taken (e.g. the proposal is withdrawn, updated, or voted on).

Members are discouraged from sustaining their objections when it is clear that they would be overruled by a vote were one to take place.

In real-time meetings, consensus can be determined by receiving no sustained objections to a proposal. Efforts to immediately resolve or record objections can be taken to attempt to achieve consensus.

Where attendance is sparse when viewed from normal participation levels, potentially controversial proposals SHOULD be made available to the broader membership.

The Chair is responsible for ensuring such opportunity for participation in the decision making process. Sparsely attended meetings SHOULD NOT be used to drive through proposals that would not have broad support.

Following a decision-making meeting, a summary of decisions and document dispositions SHALL be published as soon as is practical.

This will be addressed if the meeting minutes are available in a timely fashion.

When there is insufficient time for review in a real-time meeting, non-real-time consensus approaches SHOULD be considered.

In non-real time meetings consensus SHOULD be developed by using Review and Approval periods.
Using the group mailing list
Using GitHub "Review and Approval" label Proposals SHALL be available for a given period.

## 5.6 Using Supermajority vote to achieve agreement

### 5.6.1 Phrasing of Voting Questions

The Maintainer ensures that questions to be voted upon SHALL be phrased in a concise and unambiguous manner. Questions SHOULD NOT be phrased as “The group SHALL not do xyz”. 

Examples of appropriate questions are:
SHALL the group agree to the Specification? SHALL the liaison be approved?
SHALL the new Work Package be approved? SHALL the existing Work Package be stopped?
If the issue is to choose between two options (i.e. A or B), an example of the appropriate question may be: SHALL the group agree Option A or Option B?

The option receiving no less than 3/4 of the Supermajority Votes SHALL be the decision of the group.

If the issue is to choose between three or more options, the group SHOULD use informal voting to reduce the number of options to two, and then use formal voting, if necessary.

### 5.6.2 Voting on Technical Issues

Before voting, a clear definition of the issues SHALL be provided by the Chair(s). Members eligible to vote, SHALL only be entitled to one vote each.

Each member MAY cast a vote as often as  they wish, and the last vote they cast counts. Voting MAY be performed electronically.

Voting MAY be performed by show of hands and members announcing their vote verbally one by one, or paper ballots. The result of the vote SHALL be recorded in the meeting minutes.

Groups MAY use informal voting to reach consensus. If the Group is still unable to reach consensus, then a formal vote MAY be taken.

Voting MAY be performed using  the "lazy consensus" method to reach a consensus in favor of proposed work or actions.  This method does not require a call to vote to get approval and assumes support for the proposed work or action by the members unless a member says otherwise.

Each member’s electronic vote SHALL be electronically acknowledged to confirm participation in the vote. Voting at In-person meetings MUST also provide a remote contribution option. Voting on Teleconference meetings outside of the regular documented meeting times require at least 5 days notice.

# 6\. Approval Process

Specification(s) created by FOCUS Groups within the FOCUS Project will approve or reject contributions following a democratic process; the majority. 

This differs from an Open Source organization that normally follows a meritocratic process where the Maintainer decides what to accept or reject and If a person doesn’t like the decision that their contribution is rejected, then they can “fork” the project.

The goal for a specification creation in the FOCUS project is to reach interoperability, therefore “forking” is not the solution to a technical dispute. If there is a sustainable objection in a contribution the resolution is via a vote, see Seeking Consensus.

The Review & Approval process implies that all the contributions need to be accepted by the Working Group.

FOCUS Groups generating Non-Specification outputs will follow the same Review & Approval process, but not specifically avoid members “forking” the project.

## 6.1 Review & Approval Process

### 6.1.1 Review period

Period of time during which the contribution will be under review before being merged.
The period can be: 0 or some number of days specified by the FG Chair.

0 days imply that the contribution is merged without Working Group review
Comments or Objections, 0 day review merges MUST only be used for non-material changes to the FOCUS group work product(s).

During the Review & Approval process members MAY raise comments or objections.

Comments MUST be taken in consideration by the Working Group, but they MAY be dismissed if they group thinks that are not relevant.

Objections MUST be taken in consideration and they SHALL NOT be dismissed by the Working Group without being reviewed.

If a contribution receives an objection the group MUST resolve the issue, with the person that raised the objection, before deciding the status of the contribution. If the objection is sustained, meaning the person doesn’t remove it, then the group will have to recur to a vote to resolve it.

### 6.1.2 Approval Criteria

A contribution is considered approved and therefore it can be merged if:
The contribution has not received any sustainable objection during the review period, AND At least 3 reviewers have indicated that they agree with the contribution

If a sustained objection is received, the contribution cannot be merged, even if 3 or more contributors agreed with the contribution.

If during the review period a contribution receives a comment, it is up to the group or maintainer(s) to accept the comment or not. In any case, in order to merge the contribution at least 3 reviewers MUST indicate that they agree with the contribution.

# 7\. FOCUS Process Flows

## 7.1 Work Packages

[TBC]

## 7.2 Technical Spec Lifecycle

# 8\. Github Flows

## 8.1 GitHub Access Rights

Table 8.1-1: GitHub Access Rights
|     Role     |                                                              Access Rights                                                              |   |
|:------------:|:---------------------------------------------------------------------------------------------------------------------------------------:|---|
| Participants | TRIAGE - Can read and clone this repository. Can also manage issues and pull requests.                                                  |   |
| Editors      | WRITE - Can read, clone, and push to this repository. Can also manage issues and pull requests.                                         |   |
| Maintainer   | ADMINISTRATOR - Can read, clone, and push to this repository. They can also manage issues, pull requests, and some repository settings. |   |

# 9\. Publication

## 9.1 GitHub

Published releases of the FG outputs will be maintained on the 'main' branch of the respective FG REPOs. Each merge on this branch will be [tagged](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/managing-commits/managing-tags) with a version following Symantic Versioning. A `releases.md` file will be maintained in the REPO to allow consumers of the FG outputs to determine what has changed and when releases occurred.

## 9.2 Website Releases

Some releases may be converted to web friendly formats (such as, PDF, HTML) and made available via the website [focus.finops.org](https://focus.finops.org/). These releases will clearly attribute the ownership of the material to the FOCUS Project and make it easy to identify the version of the publication.

# 10\. Documentation

## 10.1 Terminology and Conventions

### 10.1.1 Language

The default language for writing documentation is American English, English (United States).

### 10.1.2 Conventions

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
- [ ] Officers have to have visibility of all officers' communications to ensure transparency in the leadership (e.g. a leadership mailing list)
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
