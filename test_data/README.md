# Test data

This module includes artificially generated data which matches the format of [Moodle SQL Database Table Exports](https://www.examulator.com/er/4.0/).
- 27 tables formatted in CSVs, as described in the Moodle data dictionary. Assets can be adapted to integrate ingestion/refinement functionality for more, different or less tables.

<strong>Note:</strong> This module contains one set of test data - for mock higher education data. This module does not currently contain test data formatted as a K-12 institution.

## Data dictionary

### [HEd Moodle Tables](https://github.com/microsoft/OpenEduAnalytics/tree/main/modules/module_catalog/Moodle/test_data/hed_test_data)

See full details on the [Moodle SQL Database Table Data Dictionary](https://www.examulator.com/er/4.0/)

| Domain | Table Name | Description |
|-----------|-----------|-----------|
| Activity/Assignments | [assign](https://www.examulator.com/er/4.0/tables/assign.html) |  |
| Activity/Assignments | [assign_grades](https://www.examulator.com/er/4.0/tables/assign_grades.html) |  |
| Activity/Assignments | [assign_submission](https://www.examulator.com/er/4.0/tables/assign_submission.html) |  |
| Activity/Assignments | [assignsubmission_file](https://www.examulator.com/er/4.0/tables/assignsubmission_file.html) |  |
| Activity/Assignments | [assign_user_mapping](https://www.examulator.com/er/4.0/tables/assign_user_mapping.html) |  |
| Academic Groups | [cohort](https://www.examulator.com/er/output/tables/cohort.html) |  |
| Academic Groups | [course](https://www.examulator.com/er/4.0/tables/course.html) | Course/class records. |
| Academic Groups | [course_categories](https://www.examulator.com/er/4.0/tables/course_categories.html) | Course category records. |
| Academic Groups | [enrol](https://www.examulator.com/er/4.0/tables/enrol.html) |  |
| Activity/Forums | [forum](https://www.examulator.com/er/4.0/tables/forum.html) |  |
| Activity/Forums | [forum_discussions](https://www.examulator.com/er/4.0/tables/forum_discussions.html) |  |
| Activity/Forums | [forum_grades](https://www.examulator.com/er/4.0/tables/forum_grades.html) |  |
| Activity/Forums | [forum_posts](https://www.examulator.com/er/output/tables/forum_posts.html) |  |
| Activity/Lessons | [lesson](https://www.examulator.com/er/4.0/tables/lesson.html) |  |
| Activity/Lessons | [lesson_answers](https://www.examulator.com/er/4.0/tables/lesson_answers.html) |  |
| Activity/Lessons | [lesson_attempts](https://www.examulator.com/er/4.0/tables/lesson_attempts.html) |  |
| Activity/Lessons | [lesson_grades](https://www.examulator.com/er/4.0/tables/lesson_grades.html) |  |
| Activity/Lessons | [lesson_pages](https://www.examulator.com/er/output/tables/lesson_pages.html) |  |
| Activity/Lessons | [lesson_timer](https://www.examulator.com/er/output/tables/lesson_timer.html) |  |
| Activity/Messaging | [messages](https://www.examulator.com/er/4.0/tables/messages.html) | no test data at the moment |
| Activity/Messaging | [message_conversations](https://www.examulator.com/er/4.0/tables/message_conversations.html) | no test data at the moment |
| Activity/Messaging | [message_conversation_members](https://www.examulator.com/er/4.0/tables/message_conversation_members.html) | no test data at the moment |
| Pages | [page](https://www.examulator.com/er/output/tables/page.html) |  |
| Activity/Quizzes | [quiz](https://www.examulator.com/er/4.0/tables/quiz.html) |  |
| Activity/Quizzes | [quiz_attempts](https://www.examulator.com/er/4.0/tables/quiz_attempts.html) |  |
| Activity/Quizzes | [quiz_grades](https://www.examulator.com/er/4.0/tables/quiz_grades.html) |  |
| Role | [role](https://www.examulator.com/er/4.0/tables/role.html) |  |
| Role | [role_assignments](https://www.examulator.com/er/4.0/tables/role_assignments.html) |  |
| People | [user](https://www.examulator.com/er/4.0/tables/user.html) | Contains the last updated set of information for a given user. |
| Affiliations | [user_enrolments](https://www.examulator.com/er/4.0/tables/user_enrolments.html) | The relationship between a user and a course. |
