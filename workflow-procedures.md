## FOCUS Workflow Procedures


## Specification LifeCycle
The **Specification Lifecycle** outlines the end-to-end process for creating, refining, reviewing, and releasing specifications in the FinOps FOCUS project. This lifecycle ensures that each specification is rigorously developed, approved, and made publicly available for stakeholder implementation.

<figure>
    <img src="images/FOCUS-Process-spec-life-cycle-2.drawio.png" alt="Technical Specifications Lifecycle">
    <figcaption>FOCUS Specifications Lifecycle</figcaption>
</figure>

1. **Work Item Creation:** Propose and define the scope and objectives of a new specification.
2. **Specification Development:** Draft and refine technical content to ensure the specification meets its intended goals.
3. **Consistency, IPR Review:** Review the draft for coherence, intellectual property rights compliance, and alignment with the defined scope.
4. **Final Specification Working Group Approval:** Validate the specification against technical and quality standards set by the working group.
5. **Steering Committee Ratification:** Obtain higher-level oversight and approval for public release from the steering committee.
6. **Technical Specification Publication:** Officially publish and release the specification with a version number for stakeholder implementation.

### 1. Work Item Creation Phase
The below diagram illustrates the **Work Item Creation** phase, which is the first stage in the Specifications Lifecycle for the FinOps FOCUS project. The main purpose of this phase is to define and refine the scope for the next FOCUS release, such as e.g. v1.2, ensuring that all proposed work items align with strategic priorities and are well-documented and actionable.

<figure>
    <img src="images/FOCUS-Process-work-item-creation-4.drawio.png" alt="Work Item Creation Phase">
    <figcaption>FOCUS Work Item Creation Phase</figcaption>
</figure>

#### Key Steps in Scope Definition:

1. **Ideation and Intake:** The process begins by capturing a variety of inputs, including bugs, use cases, discussion documents, pull requests (PRs), and spreadsheets. These inputs serve as the foundation for new Work Item Issues, which are documented using a standardized template to ensure consistency across all submissions.

2. **Work Item Issue Documentation:** For each potential work item, a Work Item Issue is created with mandatory information, such as a title, problem statement, and relevant supporting documents (e.g., data examples, or epics for consideration). This documentation provides the initial structure and context for each proposal, making it easier to assess relevance to the release scope.

3. **Triage and Theming:** The Maintainers and the Steering Committee (SC) review each Work Item Issue to evaluate alignment with high-level FinOps themes and release priorities. This triage step is critical for categorizing and prioritizing items, helping to shape the initial scope for the upcoming release by filtering out items that do not align with current goals.

4. **Elaboration and Input:** Items that pass the triage are moved to the Elaboration phase, where additional supporting documents are prepared, and each item is assigned to relevant epics. Stakeholders provide input to further clarify requirements and validate that each work item aligns with both technical and business objectives, ensuring it is relevant to the intended scope for the release.

5. **Requirements Documentation:** After elaboration, a Requirements Document is created for all the work items. This document details essential information, including the estimated effort level and priority, collaboratively determined by both stakeholders and maintainers. This formalized documentation helps clarify expectations and ensures that all necessary information is captured to support the item’s inclusion in the upcoming release.

6. **Epic Assignment and Steering Committee Ratification:** Completed requirements are grouped into epics and presented to the Steering Committee for review. Through ratification, the committee finalizes which epics and associated work items will be included in the scope for the targeted release version, such as e.g., v1.2.

### 2. Development Phase
The **Specification Development** phase is a structured process in the FinOps FOCUS project, implemented in GitHub, that guides contributions from ideation to final approval. This phase ensures that all contributions—whether new features, modifications, or corrections—are thoroughly reviewed, aligned with project goals, and integrated into the technical baseline when approved. The workflow progresses through the following stages:

<figure>
    <img src="images/FOCUS-Process-spec-dev-workflow.drawio.png" alt="Specification Development Phase">
    <figcaption>FOCUS Specification Development Phase</figcaption>
</figure>

1. **Creation:**
    * **WG Members Generate Contributions:** Working Group (WG) members initiate contributions by creating Issues or Pull Requests (PRs) on GitHub. These contributions represent proposed changes, new features, or corrections aligned with the project’s defined scope.
    * **Parking Lot (Qualifiers):** Items that are either not immediately actionable or need further clarification are placed in the **Parking Lot** for future consideration. This stage allows the project to capture ideas and prioritize contributions that require additional refinement before moving forward.

2. **Discussion:**
    * **Triage:** All contributions are reviewed by the **Maintainers** who assess each item’s relevance, urgency, and alignment with project goals. During this **Triage** stage, maintainers determine which items should proceed to development, be redirected for more information, or remain in the **Parking Lot**.
    * **Work in Progress:**
        * Contributions approved in triage move to **Work in Progress**, where they undergo in-depth discussion and development.
         * **Task Forces** (e.g., Task Force 1, 2, or 3) lead the discussion and development of contributions, focusing on technical details, implications, and solutions.
         * **Maintainers** guide these discussions, ensuring that work progresses within project standards and timelines and that contributions align with the project’s broader objectives.

3. **Review & Approval:**

    * **WG Member Review & Approval:** Once contributions reach a mature state, they enter the **Review & Approval** phase. Here, WG members and maintainers thoroughly scrutinize each item for technical accuracy, completeness, and consistency with project standards.
    * **Consensus-Based Decision:** Contributions are reviewed in a structured manner, with members engaging in discussions to address feedback and achieve consensus. If consensus is reached, the contribution moves forward. If further modifications are required, the item may be sent back for additional work or revision.

4. **Conclusion:**

    * **Merged or Closed:** At the end of the development phase, contributions are either:
        * **Merged** into the technical baseline, formally incorporating the changes into the project.
        * **Closed** if they are deemed unnecessary, outdated, or not aligned with current project goals.

#### Review & Approval Process
The diagram in this section outlines the **Review & Approval (R&A)** process, which is activated whenever consensus is required on proposed documents or decisions in the FOCUS project. This process typically takes place during FOCUS Members' Meetings, where members discuss, review, and seek to reach agreement on key items needing formal approval.

The **R&A** process follows a structured path, emphasizing open discussion, consensus-building, and, if necessary, voting to resolve objections. The diagram serves as a guide for this process, detailing each stage and the possible outcomes.

<figure>
    <img src="images/FOCUS-Process-R&A-4.drawio.png" alt="Review & Approval Process">
    <figcaption>Review & Approval Process</figcaption>
</figure>

#### Key Highlights of the R&A Process:

1. **Objections and Artifacts:**
    * Members who wish to object to a proposal are encouraged to submit an Objection Artifact, such as a Pull Request or Issue proposal, to clearly articulate their concerns and offer constructive alternatives.

2. **Decision Path:**
    * **Discussion:** The process begins with a collaborative discussion among members to understand different perspectives and address any concerns. The goal is to achieve consensus without formal voting.
    * **Decision:** Following discussion, a decision is made. If there are no objections, the proposal is marked as **Agreed** and merged or approved.

3. **Handling Objections:**
    * If an objection is raised, members attempt to resolve it through consensus.
    * If consensus cannot be achieved, the objection is sustained, and the proposal moves to a Vote.

> Note: Voting on a proposal is considered a last resort. While voting is possible, the group is strongly encouraged to reach a resolution through discussion and consensus wherever feasible.

4. **Voting Requirements:**
 * **For Technical Votes:**
    * Only **Steering Members** and **General Members** are eligible to participate.
    * A **Supermajority Vote** is required to resolve technical disputes, ensuring that only the most critical disagreements necessitate formal voting and higher levels of consensus.
    * If the vote results in an agreement, the proposal proceeds as **Agreed** and is merged. If rejected, it may require further changes or be closed.

5. **Final Outcomes:**
 * **Agreed / Merged:** If consensus is achieved or a vote passes, the proposal is approved and implemented.
 * **Rejected / Closed:** If consensus cannot be reached and the vote fails, the proposal is closed.

This **R&A** process fosters an inclusive, structured approach to decision-making, ensuring that all member concerns are addressed, and important technical issues are resolved with input from both Steering and General Members. By establishing clear steps for consensus-building and a formal voting mechanism, the R&A process maintains rigor and accountability within the FOCUS project.

### 3. Consistency & IPR Reviews


### 4. Working Group Final Approval


### 5. Steering Committee Ratification


### 6. Publication