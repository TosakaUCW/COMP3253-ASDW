# Meeting Minutes of B06

**Date and Time:** 2026/04/02 11:20  
**Location:** T29-101

## Present

- YANG Bohan t330016056
- LI Xinze t330026083
- LIU Chenxu t330025052
- ZUO Ye t330026245
- ZUO Kaiwen t330026244
- ZHANG Wenyi t330026219

**Next Meeting:** 2026/04/16 11:20

## Agenda

1. Review Lab 6 task briefing and confirm this week’s deliverables.
2. Re-check key requirements from previous labs (state-transition/UI matching and numbering rules).
3. Plan Class Diagram work for the current partial SRS submission.
4. Plan Sequence Diagram work for the mentor use case **Search Student’s Info**.
5. Assign responsibilities and confirm submission package and deadline.

## Announcements

The team reviewed the Lab 6 instructions released this week. The required work includes:

- Continue partial SRS refinement based on feedback.
- Prepare a **Class Diagram** with only participating classes, including key attributes and operations needed for understanding the design.
- Prepare a **Sequence Diagram** for the mentor use case **Search Student’s Info** (according to Lecture 6 and Lecture 7 guidance).
- Place both diagrams in **Appendix B** of the SRS and provide proper figure labels.

The group also noted reminders from earlier feedback that still apply:

- State transition diagram states and corresponding UIs must match exactly (state number, label, and controls).
- All UIs should remain in one consolidated UI file and be organized by numbering groups (1/2/3/4).
- Avoid duplicated UI pages and inconsistent state numbering.

Submission reminder discussed in class: submit one copy of the partial SRS to **iSpace** and **GitLab** before the deadline (noon, 4 April 2026).

## Discussion

1. The group first reviewed the Lab 6 scope and agreed that this week’s core focus is adding analysis/design models rather than rewriting all previous text sections.

2. For the **Class Diagram**, the team agreed to model only classes directly participating in current core use cases, especially around login, mentor/student information query, interview record context, and role-based access behavior. Members agreed to include only important attributes/operations for readability and completeness at this stage.

3. For the **Sequence Diagram** of **Search Student’s Info (Mentor)**, the group agreed on the main interaction chain: Mentor UI -> Controller/Service -> Data Access -> User/Student data source -> result return to UI. The team will ensure message order clearly reflects validation, query, and response display.

4. The group discussed consistency rules between artifacts: use case intent, transition states, UI controls, class responsibilities, and sequence messages should not conflict. This is necessary to avoid losing marks for cross-artifact inconsistency.

5. The members also agreed to reserve Reading Week time for revising Lab 5 after formal grading feedback is released, so that the team can avoid overlap pressure before the next lab meeting.

6. Responsibility allocation for this week:
   - **Bohan Yang**: draft and finalize Meeting Minutes 5; integrate Appendix B sections and check submission packaging.
   - **Xinze Li**: review SRS wording and section references; ensure figure captions and cross-references are correct.
   - **Liu Chenxu**: draft the Class Diagram structure and core class operations.
   - **Zuo Ye**: coordinate progress, verify alignment with Lab 6 slides, and conduct final pre-submission checklist.
   - **Zuo Kaiwen**: draft/refine Sequence Diagram for mentor Search Student’s Info and verify message flow logic.
   - **Zhang Wenyi**: check UI/state consistency and support diagram labeling/formatting in the final document.

## Any Other Business (AOB)

The group agreed to complete the class and sequence diagrams first, then run a final consistency check across Section 3, UI file, and Appendix B before submission. The team leader will remind everyone to upload finished parts early and avoid last-minute submission risk. After final confirmation, the secretary will upload this meeting minutes file to the repository.