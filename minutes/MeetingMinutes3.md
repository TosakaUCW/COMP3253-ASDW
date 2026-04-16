# Meeting Minutes of B06

**Date and Time:** 2026/03/19 11:20  
**Location:** T29-101

## Present

- YANG Bohan t330016056
- LI Xinze t330026083
- LIU Chenxu t330025052
- ZUO Ye t330026245
- ZUO Kaiwen t330026244
- ZHANG Wenyi t330026219

**Next Meeting:** 2026/03/26 11:20

## Agenda

1. Review the teacher's feedback on the partial SRS document, context model, and use case diagram from the previous lab.
2. Study the teacher's explanation of SRS Section 3 and Section 4.1, together with the updated Long Project Description v1.1.
3. Decide how to revise the partial SRS according to the Lab 4 requirements.
4. Discuss the required state transition diagrams, user interfaces, and basic scenarios for the specified use cases.
5. Assign responsibilities and confirm the submission plan before the deadline.

## Announcements

The teacher reviewed the common problems in last week's submission. For the context model, only Login, MCS, and BNBU User Database should be included, and the system boundary must be clearly shown. For the use case diagram, login must be included, actor and use case relationships must be consistent, and unnecessary detail or redundant use cases should be removed.

The teacher also explained that the state transition diagram for each use case should be placed in Section 3.X.2 rather than Appendix B. A separate UI document should be prepared, and each UI must correspond exactly to the states in the transition diagram. The updated Long Project Description v1.1 on iSpace should be used when revising the SRS. The partial SRS must be submitted to both iSpace and GitLab before 23:55 on 20 March 2026.

## Discussion

1. The group reviewed the teacher's feedback on the partial SRS, context model, and use case diagram. The members agreed that some earlier diagrams might still contain avoidable notation and completeness problems, so the team decided to update the document strictly according to the Lab 4 slides and the teacher's recommended solution.

2. The team studied the Lab 4 task requirements and focused on the newly required parts of Section 3 and Section 4.1. The group discussed how the state transition diagrams should reflect user actions and system responses, and how the UI diagrams should match the state labels exactly for grading and cross-reference.

3. The group decided to revise the context model so that it contains only the Mentor Caring System, Login Verification, and School User Database, with a clear boundary around the system. The team also agreed to replace or revise the previous use case diagram using the teacher's version to avoid losing marks again in later labs.

4. The members discussed the specified use cases for this week:
   - Section 3.1: Search Student's Info for Mentor and Coordinator
   - Section 3.2: Edit Interview Record for Mentor, combined with the transition flow of Search Student's Info
   - Section 3.3: Search Mentor Info for Faculty Consultant and Coordinator

5. The group agreed that the basic scenarios should be written before finalizing the transition diagrams because the scenario sequence helps determine the states and transitions. The members also noted that assumptions must be clearly stated in each scenario and that any remaining functional requirements not covered by the diagrams and UI should be added briefly in Section 3.X.3.

6. The group assigned responsibilities as follows:
   - Bohan Yang: write Meeting Minutes 3, organize the final submission files, and help integrate the revised SRS.
   - Xinze Li: revise Section 1 and the revision history, and help update the scenario text to match the new Section 3 structure.
   - Liu Chenxu: draft the transition diagram content for Search Student's Info and help prepare the combined flow for Edit Interview Record.
   - Zuo Ye: coordinate the overall progress, review the revised SRS against the Lab 4 instructions, and check deadline readiness.
   - Zuo Kaiwen: update the context model and revise the use case diagram according to the teacher's feedback and provided examples.
   - Zhang Wenyi: prepare the UI document and help write the Search Mentor Info scenario and related Section 4.1 references.

## Any Other Business (AOB)

The group agreed to complete the updated partial SRS, transition diagrams, UI document, and required scenarios before the submission deadline on 20 March 2026. The team leader will monitor progress and remind members of unfinished tasks. After the files are finalized, the group will submit the SRS to iSpace and GitLab, and the secretary will upload the official meeting minutes to the repository.
