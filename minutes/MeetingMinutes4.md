# Meeting Minutes of B06

**Date and Time:** 2026/03/26 11:20  
**Location:** T29-101

## Present

- YANG Bohan t330016056
- LI Xinze t330026083
- LIU Chenxu t330025052
- ZUO Ye t330026245
- ZUO Kaiwen t330026244
- ZHANG Wenyi t330026219

**Next Meeting:** 2026/04/02 11:20

## Agenda

1. Review the teacher’s feedback on last week’s partial SRS (transition diagrams, UI file, and scenarios).
2. Study the teacher’s explained solutions for Search Students’ Info + Edit Interview Record and Search Mentors’ Info.
3. Plan the Lab 5 work: full Section 3 renumbering, diagrams and UIs for all use cases, and scenarios for all important (goal-oriented) use cases.
4. Assign responsibilities and confirm submission to iSpace and GitHub before the deadline.

## Announcements

The teacher emphasized that each state in a transition diagram must have a matching UI, with state number and label identical to the UI. Every event or condition in a transition must correspond to a control in the UI (e.g. “Click Button 1” requires Button 1); the UI file must not contain unused controls. State numbers must be unique across the whole SRS (e.g. avoid two different “2. …” states). Improper actions such as “Go to Edit page” should be avoided where the arrow already expresses navigation; warning boxes with only one button are actions, not states. After login, every state should provide a “Home” button to the role’s home page. Only the login diagram needs state “1. Login”; other diagrams may start from home and state “Assume the user has logged in” in Section 3.x.3.

All UIs must live in one separate UI document (not inside the SRS). There should be one complete set of UIs for all transition diagrams, organized by numbering (1: login and home pages; 2: search, edit, export for main goal-oriented use cases; 3: utility/support pages; 4: admin and maintenance). Each UI appears only once; graders look up UIs by state number.

Scenarios must alternate user action and system response. The cover must record each member’s contribution as Full, Fair, Little, or None. Font sizes in diagrams and UIs should be readable and comparable to body text; state/UI numbers and labels should be slightly larger than event/condition text.

For Search Student’s Info / Edit Interview Record, conditions must reflect the actor so coordinators cannot edit interview records in the diagram.

Submission: each group submits the partial SRS and the UI file (two documents, one copy) to **iSpace** and **GitHub**. **Deadline: 12:00 noon, Saturday 28 March 2026.** Leaders should indicate contribution next to each name on the cover. Avoid submitting at the last minute.

## Discussion

1. The group reviewed Lab 5 feedback on matching transition diagrams and UIs, unique numbering, Home buttons, and the single consolidated UI file with numbering scheme 1 / 2 / 3 / 4.

2. The team studied the teacher’s reference solutions: combined flow for Search Students’ Info and Edit Interview Record (including coordinator/faculty read-only view vs mentor edit with Save/Cancel), and the Search Mentors’ Info flow with search, group selection, member list, and student record display.

3. The group agreed to restructure Section 3 so that **3.1 is Login**, **3.2 is Search Student Info**, and following subsections follow the course order: list goal-oriented use cases first, then support and maintenance; related use cases may share one transition diagram for clarity.

4. The members planned to produce **state transition diagrams and matching UIs for all use cases** this week, and **basic scenarios for all important use cases**, writing scenarios before finalizing diagrams where helpful.

5. The group assigned responsibilities (to be adjusted as work progresses):
   - Bohan Yang: meeting minutes, integrate SRS and UI cross-references, check submission packaging.
   - Xinze Li: Section 1, revision history, and scenario wording consistency.
   - Liu Chenxu: transition diagrams for search/edit/export-related flows and actor-specific conditions.
   - Zuo Ye: overall coordination, Section 3 ordering and checklist against Lab 5 slides.
   - Zuo Kaiwen: align diagrams with teacher’s examples and numbering rules.
   - Zhang Wenyi: single UI document, numbering 1/2/3/4 layout, and Section 4.1 file naming.

## Any Other Business (AOB)

The group agreed to finish updates before **noon, 28 March 2026**, and to submit early enough to avoid network issues. After finalization, the team will upload to iSpace and GitHub; the secretary will upload the official meeting minutes to the group repository as required.
