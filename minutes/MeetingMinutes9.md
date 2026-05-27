# Meeting Minutes of B06

Date and Time: 2026/05/14 11:20  
Location: T29-101

## Present

- YANG Bohan t330016056
- LI Xinze t330026083
- LIU Chenxu t330025052
- ZUO Ye t330026245
- ZUO Kaiwen t330026244
- ZHANG Wenyi t330026219

Next Meeting: 2026/05/21 09:00

## Agenda

1. Review the Lab 11 announcement and upcoming presentation/survey schedule.
2. Study the Test Plan template and Test Report template requirements.
3. Decide how to prepare black-box system test cases for the required use cases.
4. Discuss the use of LoadRunner and TestComplete for testing evidence.
5. Assign responsibilities and confirm the Lab 11 submission package and deadline.

## Announcements

The teacher announced that SE Assignment 5 will be released soon, and students should review Lecture 16 before the 10-minute online assignment. The next lab on Thursday, 21 May 2026 will include a very important survey. Every student must arrive on time at 9:00 AM and bring a pen. Students who cannot attend must have an official excuse; otherwise points will be deducted.

The teacher also announced that final presentations will be held from 26 May to 28 May 2026 during lab and SE class time. Teams should sign up with the teacher.

For Lab 11, the teacher explained the Test Plan template and Test Report template, both of which are available on iSpace. The test report should report only test cases that contain bugs. If no test cases have bugs, the team should write NONE.

Students should prepare the test plan after the code is running. The test plan should use black-box testing on the following use cases, with one table for each use case:

- Search Student's Info (by Mentor and Coordinator)
- Edit Interview Record (by Mentor)
- Search Mentor Info (by Faculty Consultant and Coordinator)

The teacher reminded students that these use cases already had transition diagrams in Lab 4, and Lecture 14 provides guidance on generating test cases from transition diagrams. The teacher also clarified the difference between unit testing and system testing: in unit testing, a class and its methods are tested; in system testing, use cases are tested, and each use case may involve several classes.

For testing tools, students should practice with LoadRunner for the use case Edit Interview Record. Each student should read Reading instructions and questions.pdf, answer the questions, and submit the answers to iSpace individually. Students may use LoadRunner 12.02 installed in the computer room or LoadRunner 2021 on their own computers.

The teacher also introduced TestComplete by SmartBear for the use case Search Student's Info. Students should design black-box test cases and use TestComplete to record and repeat GUI tests after bug fixes or code changes. The required practice includes creating a TestComplete project, recording a Keyword Test, adding checkpoints for valid and invalid/empty Student ID inputs, running the test, and viewing the test log.

Group submission requirement discussed in class: each group should submit one copy of the test plan and one copy of the test report to both iSpace and GitLab before 23:55, Saturday 16 May 2026. The appendix of the test report should include three whole-screen screenshots from TestComplete, each with one sentence explanation:

1. Recorded Keyword Test steps.
2. Added checkpoint steps/settings.
3. Test log after running the test.

Each student should also submit the LoadRunner practice answers to iSpace only before the same deadline.

## Discussion

1. The group first reviewed the Lab 11 requirements and agreed that this week's main focus is moving from unit testing to system testing. Members noted that the test plan should be based on use cases rather than individual classes.

2. The team agreed to reuse the Lab 4 transition diagrams as the starting point for black-box test case design. This avoids inventing unrelated test cases and keeps the test plan consistent with previous SRS and UI/state-transition work.

3. For the required use cases, the group agreed to prepare one table for each use case. Each table should clearly describe test inputs, expected outputs, and whether the case covers normal, invalid, empty, or boundary conditions.

4. The members discussed the Test Report rule and agreed to report only test cases that reveal bugs. If the current implementation passes all selected test cases, the report should explicitly write NONE for bug-containing cases instead of adding unnecessary failure descriptions.

5. For TestComplete, the team agreed to focus on Search Student's Info because the required screenshots and checkpoints can be clearly demonstrated with valid and invalid Student ID inputs. Members agreed that the screenshots must be whole-screen captures and each one should have a short explanation.

6. For LoadRunner, the team agreed that each member should complete the individual practice and answer the required questions independently. The team will also include one Vuser script copy in the appendix of the group test report, following the teacher's instruction.

7. Responsibility allocation for this week:
   - Bohan Yang: write Meeting Minutes 9, integrate the test plan and test report package, and check final submission readiness.
   - Xinze Li: draft the test plan tables for Search Student's Info and ensure black-box test case wording is clear.
   - Liu Chenxu: prepare the test plan table for Edit Interview Record and support LoadRunner-related appendix material.
   - Zuo Ye: coordinate the testing workflow, verify Lab 11 requirements are covered, and run the final checklist before submission.
   - Zuo Kaiwen: complete TestComplete recording, checkpoints, and test log screenshots for Search Student's Info.
   - Zhang Wenyi: prepare the test report content, document bug-related cases or NONE, and format screenshot explanations.

## Any Other Business (AOB)

The group agreed to finish the test plan first, then run or document the required tool-based tests before preparing the final test report. Members will complete the LoadRunner individual answers before the deadline and submit them to iSpace. The team also noted the important survey on 21 May 2026 and the final presentation period from 26 May to 28 May, so upcoming work should prioritize stable testing evidence and presentation preparation.
