# Scrum Overview

## 1. Scrum Roles

| Role | Member Name | Registration Number | Responsibilities |
|------|-------------|---------------------|------------------|
| Product Owner | ASHURA ABASI JUMA | 31072/T.2023 | - Define and prioritize product backlog items<br>- Ensure backlog is visible and transparent<br>- Accept or reject work results<br>- Represent stakeholders' interests |
| Scrum Master | DAVID ZENO SIKUKUU | 32347/T.2023 | - Facilitate Scrum events<br>- Remove impediments<br>- Coach team on Scrum practices<br>- Protect team from external interference |
| Developer 1 | KABWE KASIM RASHIDI | 31432/T.2023 | - Design and implement features<br>- Write clean, maintainable code<br>- Participate in code reviews<br>- Write unit tests |
| Developer 2 | JACOB LUCAS BULLUGU | 32285/T.2023 | - Design and implement features<br>- Write clean, maintainable code<br>- Participate in code reviews<br>- Write unit tests |
| Developer 3 | MAIMUNA BAKARI DIONI | 30954/T.2023 | - Design and implement features<br>- Write clean, maintainable code<br>- Participate in code reviews<br>- Write unit tests |
| Developer 4 | [YOUR_NAME] | [REG_NUMBER] | - Design and implement features<br>- Write clean, maintainable code<br>- Participate in code reviews<br>- Write unit tests |
| Developer 5 | [YOUR_NAME] | [REG_NUMBER] | - Design and implement features<br>- Write clean, maintainable code<br>- Participate in code reviews<br>- Write unit tests |

---

## 2. Scrum Events

### Sprint Planning
- **Duration:** 2-4 hours (for a 2-week sprint)
- **Participants:** Entire Scrum Team (Product Owner, Scrum Master, Developers)
- **Agenda:**
  1. Product Owner presents prioritized Product Backlog
  2. Team discusses backlog items and asks clarifying questions
  3. Team selects items for Sprint Backlog based on capacity
  4. Team breaks down selected items into tasks
  5. Team commits to Sprint Goal
- **Outcome:** Sprint Backlog with committed items and Sprint Goal

### Daily Scrum
- **Duration:** 15 minutes
- **Frequency:** Every day at 9:00 AM
- **Participants:** Developers (Product Owner and Scrum Master optional)
- **Format:** Each team member answers:
  - What did I complete yesterday?
  - What will I work on today?
  - Are there any impediments blocking my progress?
- **Outcome:** Synchronized team understanding and identification of impediments

### Sprint Review
- **Duration:** 1-2 hours
- **Participants:** Entire Scrum Team + Stakeholders
- **Agenda:**
  1. Team demonstrates completed work (Increment)
  2. Stakeholders provide feedback
  3. Product Owner updates Product Backlog based on feedback
  4. Discussion on what to do next
- **Outcome:** Updated Product Backlog and stakeholder feedback

### Sprint Retrospective
- **Duration:** 1-2 hours
- **Participants:** Entire Scrum Team
- **Format:**
  1. **What went well?** - Celebrate successes
  2. **What could be improved?** - Identify areas for improvement
  3. **Action items** - Commit to specific improvements for next sprint
- **Outcome:** Actionable improvements for the next sprint

---

## 3. Scrum Artifacts

### Product Backlog
- **Owner:** Product Owner
- **Description:** An ordered list of all features, enhancements, bug fixes, and technical work needed for the product
- **Characteristics:**
  - Ordered by priority (highest at top)
  - Continuously refined and updated
  - Contains user stories with acceptance criteria
  - Estimated by the Development Team
- **Example Items:**
  - Add new task functionality
  - Assign task to user
  - Mark task as complete
  - Display task list
  - Notification system

### Sprint Backlog
- **Owner:** Development Team
- **Description:** The set of Product Backlog items selected for the sprint, plus a plan for delivering them
- **Characteristics:**
  - Created during Sprint Planning
  - Owned and managed by Development Team
  - Updated throughout the sprint
  - Contains tasks broken down from selected backlog items
- **Example Structure:**
  - User Story: "As a user, I want to create a new task"
    - Task 1: Design task creation form UI
    - Task 2: Implement backend API endpoint
    - Task 3: Write unit tests
    - Task 4: Integration testing

### Increment
- **Owner:** Development Team
- **Description:** The sum of all Product Backlog items completed during a sprint, plus all increments from previous sprints
- **Characteristics:**
  - Must be in "Done" state (meets Definition of Done)
  - Must be potentially releasable
  - Must be working software
  - Integrated with previous increments
- **Quality Criteria:**
  - Code reviewed and approved
  - All tests passing
  - Documentation updated
  - Deployed to staging environment (if applicable)

---

## Sprint Timeline 

**Sprint Duration:** 2 weeks (10 working days)

**Event Schedule:**
- **Day 1:** Sprint Planning (Morning)
- **Days 1-10:** Daily Scrum (Every day)
- **Day 10 (Afternoon):** Sprint Review
- **Day 10 (End of day):** Sprint Retrospective

---

## Team Commitments

### Definition of Done (DoD)
1. Code is written, reviewed, and merged to main branch
2. All unit tests pass (minimum 80% code coverage)
3. Code follows team coding standards and style guide
4. Documentation is updated (README, API docs, inline comments)
5. Feature is tested manually and works as expected
6. No critical bugs or security vulnerabilities

### agreement among members
- All code changes must go through Pull Request review
- Minimum of 1 approval required before merging
- Commit messages must follow conventional commit format
- Daily standup attendance is mandatory
- Communicate blockers immediately
- Respect each other's time and expertise

