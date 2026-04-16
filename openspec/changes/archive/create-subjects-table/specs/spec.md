### Requirement: Subjects table

The system must provide a `subjects` table to store subject information.

#### Scenario: Create subjects table
Given the database schema
When the subjects table is created
Then it must contain the fields `id`, `name`, `teacher`, `hours`, and `user_id`
And it must not contain extra fields beyond the requested scope