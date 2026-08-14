# Sprint Progress Grading Criteria

## Spring

Spring sprint progress is evaluated across 4 areas:
- weekly status updates
- sprint boards
- github
- code reviews (peer & mentor)

Expectations for each of these areas as well as a final grading rubric can be found below.

### Sprints
The spring semester consists of 4 sprints (3 of which are graded) spanning the following dates:
- January: 1/12 - 2/1
- February: 2/2 - 3/1
- March: 3/2 - 3/29
- April: 3/30 - 4/12 (not graded)

### Expectations

#### Weekly Status Updates
Students must create a new status update task for each week. The task must follow the following format:
- The title must be `Status Update - Week of MM/YY` with the date matching the Monday on the course schedule
- The epic must be set to `status update`
- The due date must be set to the following Sunday
- all team members should be assigned to the task

As the week progresses, the task's status should transition from TODO to DONE.

Students should add a comment to the task posting their weekly update covering:
- what they completed (link out to other tasks)
- what they are blocked by
- what they are working on (link out to other tasks)

Note: each student must leave their own comment on the task before the due date to receieve full credit. It is not sufficient to simply update the description of the task.

We recommend that students create all status update tickets at the beginning of their sprint.

#### Sprint Boards
Students should create tasks on their sprint board to capture their project-specific work. To receive full credit, each task must include:
- a detailed description explaining what the task entails as well as the acceptance criteria / deliverable (what it means to complete the task)
- assignee(s)
- due date
- sprint
- epic
- status
- linked PR (when there is code)

While it is ok to have some tasks assigned to multiple team member's the majority of tickets should be assigned to a single person. That way we know who is responsible for which components of the project. We also expect to see a sufficient number of tasks completed by each person in a given sprint. If a student only has one task assigned to them, its usually a sign that the task needs to be broken down into smaller deliverables or the student needs to spend more time on their project.

By the end of the sprint, all tasks should be completed, moved to next sprint, or marked as won't do.

#### Github
All students should contribute code during each sprint. Code should be pushed to feature branches and PRed to main. PRs should have descriptions explaining the code change. Instructors will only evaluate code merged to main. Specifically:
- We will not review code in unmerged branches
- Students will not receive full credit for code committed directly to main without the use of a PR

We use commit history for grading, so:
- The author of the PR should be the one to merge it
- A single branch should only contain one person's commits -- squash-merge assigns all code to the PR merger, so we lose track of who committed what.
- If your github account isn't associated with your commits, you will not get credit.

#### Code Reviews
For the January and March sprints, we require at least one peer code review.
- Each team member must author a PR (already a requirement under the Github section)
- Each team member must review a PR. It is not sufficient to simply approve a PR. The student must leave comments showing they reviewed the code.

For the February sprint, we require at least one mentor code review. During one of the weekly mentor meetings, the team should choose 1 PR to review with their mentor as a group. The mentor should leave at least one comment on the PR as proof they reviewed it.

### Rubric
Each sprint is graded out of a total of 6 points. Below shows the grading breakdown.

#### Weekly Status Updates (1 pt)
The 1 point is divided evenly between the number of weeks in a sprint (typically 0.25 pts / week except for the months with holidays).
For each week:
- 1/2 credit if weekly update is late
- 1/2 credit if weekly update format is incorrect (comments posted as description, task missing epic, title in wrong format, etc)
- 1/4 credit if weekly update late AND format is incorrect
- 0 - 1/2 credit if content of weekly update is missing or does not include sufficient detail

#### Sprint Boards (2 pt)
To receive full credit for a sprint board:
- All tasks must have the correct metadata as defined under the expectations section (description + deliverable, due date, epic, assignee, etc)
- Student has sufficient number of individual, project-specific tasks assigned (typically >= 3 per sprint)
- All tasks moved to done, won't do, or next sprint

Amount of points taken off (the ranges are dependent on the number of tasks missing data):
- -0.1 - 0.25 pts if tasks left in progress / todo or missing metadata (epics, assignees, etc)
- -0.25 - 0.5 pts if tasks don't include clear descriptions & deliverables
- -0.5 - 1 pt if not enough tasks in sprint
- 0 pts if no tasks / not enough evidence of sprint progress

#### Github (2 pt)
To receive full credit:
- Sufficient amount of code merged to main (not committed directly to main)
- PRs used to merge code, and PRs have clear descriptions

Points taken off (ranges are dependent on severity):
- -0.1 - 0.25 pts if PRs missing / don't have sufficient descriptions
- -0.25 - 0.5 pts if minimal / no PRs used and code is instead directly committed to main
- -1 pt if minimal code written / only documentation merged

#### Code Review (1 pt)
Peer code review grading:
- 0.5 pts for authoring a PR
- 0.5 pts for reviwing a PR (must include comments & feedback, not just an approval)
    - -0.25 pts if review is late

Mentor code review grading:
- 1 pt for mentor reviewing a PR (must leave at least one comment as proof of review)
