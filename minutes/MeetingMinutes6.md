# Meeting Minutes of B06

Date and Time: 2026/04/16 11:20  
Location: T29-101

## Present

- YANG Bohan t330016056
- LI Xinze t330026083
- LIU Chenxu t330025052
- ZUO Ye t330026245
- ZUO Kaiwen t330026244
- ZHANG Wenyi t330026219

Next Meeting: 2026/04/23 11:20

## Agenda

1. Review the Lab 6 grading result and detailed feedback on the partial SRS class diagram.
2. Study Lab 7 briefing: class/sequence diagram revision, updated long description v1.2, and architecture design template requirements.
3. Decide how to reorganize classes, associations, and notation in the class diagram using the teacher’s solution as baseline.
4. Plan the architecture design document structure and writing scope according to the provided template.
5. Assign responsibilities and confirm submission package and deadline.

## Announcements

The group received the Lab 6 grading result for Partial SRS - Class diagram-SE. Feedback highlighted:

- Completeness: missing associations such as: each faculty has some faculty consultants, each department has a coordinator, and each major has several MCP groups.
- Consistency: operations in a class should operate on attributes of that class, not user-level actions (for example, operation naming similar to import/manage).
- Redundancy: user-role operations do not automatically mean associations between role classes and target object classes (for example, view/search/manage/edit).
- Notation: fonts were too small and line spacing was too large.

Based on the Lab 7 briefing in class (15 April 2026), this week’s required work includes:

- Update the class and sequence diagrams according to teacher feedback.
- Use the teacher-provided class diagram solution as the baseline for consistency in future grading.
- Prepare the architecture design document using the template.
- Submit updated SRS + architecture design document (one copy each) to iSpace and GitLab before Saturday, 18 April 2026, 11:59 PM.

## Discussion

1. The group reviewed all feedback items and agreed that the primary issue is model quality rather than missing text volume. Members agreed to prioritize correctness of class responsibilities and associations before polishing wording.

2. For completeness, the team agreed to explicitly include the missing structural relations in the class model:
   - Faculty and Faculty Consultant allocation relation.
   - Department and Coordinator relation.
   - Major and MCP Group relation.
   The team will verify cardinalities and naming against the teacher’s solution slide and current SRS terminology.

3. For consistency, the group agreed to remove role-centered or UI-action-like operations from domain classes. Operations will be rewritten so each class operation reflects responsibility over its own attributes/state.

4. For redundancy, the team agreed to re-check all associations among Faculty Consultant, Coordinator, Mentor, MCP Group, and Student. Only information-dependency/static relationships will be kept; operation verbs alone will not be treated as associations.

5. For notation, the team agreed to redraw the class diagram with readable font size, tighter but clear spacing, fewer crossing lines, and standard UML inheritance symbols.

6. For Lab 7 deliverables, the team agreed to:
   - Update class diagram first using teacher solution as baseline.
   - Adjust the related sequence diagram after class responsibilities are stabilized.
   - Complete architecture design document sections according to template structure and keep text concise (especially overview sections).

7. Responsibility allocation for this week:
   - Bohan Yang: write Meeting Minutes 6, integrate final submission package, and check iSpace/GitLab upload readiness.
   - Xinze Li: revise SRS wording and cross-references after class diagram update; ensure consistency of class names across sections.
   - Liu Chenxu: implement class diagram revisions (associations, multiplicities, operations, notation cleanup) based on feedback and sample solution.
   - Zuo Ye: coordinate progress, verify all feedback points are addressed, and run final checklist before submission.
   - Zuo Kaiwen: update sequence diagram to align with revised class responsibilities and interaction flow.
   - Zhang Wenyi: complete architecture design document draft from template and align subsystem descriptions with updated SRS artifacts.

## Any Other Business (AOB)

The group agreed to finish the revised class diagram first, then finalize the sequence diagram and architecture design document, followed by a final consistency review across all files. The team will submit early on 18 April 2026 to avoid last-minute network risk, and contribution levels (Full/Fair/Little/None) will be marked on document covers before upload.
