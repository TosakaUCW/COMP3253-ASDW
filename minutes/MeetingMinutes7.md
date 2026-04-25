# Meeting Minutes of B06

**Date and Time:** 2026/04/23 11:20  
**Location:** T29-101

## Present

- YANG Bohan t330016056
- LI Xinze t330026083
- LIU Chenxu t330025052
- ZUO Ye t330026245
- ZUO Kaiwen t330026244
- ZHANG Wenyi t330026219

**Next Meeting:** 2026/04/30 11:20

## Agenda

1. Review the teacher's feedback on the Architecture Design diagram and identify the main problems to fix.
2. Study the Detailed Design template explanation and confirm this week's required document structure.
3. Decide how to keep the whole class diagram, subsystem design, UI layer, and database tables consistent.
4. Plan the Detailed Design document, including the restructured class diagram, class descriptions, and pre/post-condition requirement.
5. Assign responsibilities and confirm the submission package and deadline.

## Announcements

The teacher reviewed common problems in the Architecture Design document. The purpose of architecture design is to divide the system into subsystems so that they can be developed individually. The design model in Section 2.2 should reflect both the MVC view and the three-layered view. The whole system architecture must remain consistent with the class diagram in Section 2.1: every class in Section 2.1 must appear in Section 2.3, and every class in Section 2.3 must also appear in Section 2.1. A class should not appear in two different subsystems, otherwise subsystem coupling becomes too high. The Section 2.3 architecture diagram should show subsystem structure and coupling using class names only, without attributes, operations, UI elements, or database content.

The teacher also emphasized consistency between the use case diagram and the subsystem UI layer. All UIs in subsystem design must come from the use case diagram in Section 2.1, except HomeUI or MainUI used for navigation. Every use case should appear in exactly one subsystem UI layer, and the team should avoid placing the same use case in multiple subsystems.

For subsystem database tables, table attributes must match class attributes. Associations should be represented properly in the database design: one-to-many relations should usually place the foreign key in the "many" table, many-to-many relations should use an association table, and inheritance may be handled by extending the table structure where appropriate.

For the Detailed Design document, the teacher explained that:

- Section 2.1 should use the same whole class diagram as the Architecture Design document.
- Section 3.1 should contain the restructured class diagram derived from Section 2.1, following the Lecture 11 guidelines.
- Starting from Section 3.2, each section should describe one real class, and the section title should be replaced with the actual class name.
- Each class description should include the class notation with all attributes and operations, reflecting the finished interface design.
- Explanation text is optional unless new attributes or operations are introduced beyond the architecture design.
- Only one operation in the whole document needs pre- and post-conditions for this submission, and the chosen operation should be substantial enough to demonstrate both.
- The table of contents must be updated after all class descriptions are completed.

Submission requirement discussed in class: each team should submit **one copy of the Detailed Design document** to **iSpace** and **GitLab** before **23:59, Saturday 25 April 2026**. Contribution levels on the cover should still be marked as **Full, Fair, Little, or None** next to each member's name.

## Discussion

1. The group first reviewed the architecture feedback and agreed that this week's main task is not to invent a new structure, but to correct inconsistencies between the whole class diagram, subsystem decomposition, subsystem UI, and database tables.

2. The team agreed to re-check the whole system architecture against the baseline class diagram carefully. Members noted that every class should belong to only one subsystem, and subsystem boundaries should be drawn to improve cohesion rather than repeat classes across multiple parts of the design.

3. The group also agreed to verify that every use case is mapped to exactly one subsystem UI layer. Home or main pages may be shared as navigation entry points, but actual functional use cases should not be duplicated across subsystems. This will help keep the architecture design aligned with the teacher's marking criteria.

4. For database design, the members agreed to compare each table against the corresponding class attributes and review how associations are represented. Special attention will be given to foreign keys for one-to-many relations and association tables for many-to-many relations so that the database section is consistent with both the class model and DBMS rules.

5. For the Detailed Design document, the group agreed to keep Section 2.1 unchanged from the Architecture Design document, then restructure the class diagram for Section 3.1 according to Lecture 11. Starting from Section 3.2, each class will be documented with its complete attributes and operations before any optional explanation text is added.

6. The team decided to select one meaningful operation for formal pre- and post-condition description, instead of adding weak or trivial conditions everywhere. Members agreed that this should be an operation with clear state change or validation logic so the example is persuasive and easy to grade.

7. Responsibility allocation for this week:
   - Bohan Yang: write Meeting Minutes 7, integrate the Detailed Design document, and check final submission packaging.
   - Xinze Li: revise section titles, table of contents, and cross-references; ensure wording consistency across class descriptions.
   - Liu Chenxu: prepare the restructured class diagram in Section 3.1 and refine class attributes/operations for the detailed design.
   - Zuo Ye: coordinate progress, verify all Lab 8 requirements are covered, and conduct the final checklist before submission.
   - Zuo Kaiwen: review subsystem allocation and UI/use case consistency; help correct controller and interaction naming where needed.
   - Zhang Wenyi: prepare or refine the database table sections and draft the selected operation's pre- and post-conditions.

## Any Other Business (AOB)

The group agreed to finish the Detailed Design document before the deadline on 25 April 2026 and submit early enough to avoid last-minute upload problems. The team will complete the consistency check across the architecture design and detailed design documents before submission. The members also noted the Lab 9 reminder that next week they will watch videos on unit testing and should bring earpieces if needed.
