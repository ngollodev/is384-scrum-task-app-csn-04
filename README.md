# Cloud-Based Task Management App

## Project Overview 

This is a cloud-based task management application developed as part of the IS 384 – Cloud and DevOps course. The application enables teams to create, assign, track, and complete tasks in a collaborative environment.

## Short Description

A cloud-based task management application that allows users to create different tasks, assign them to each team member, and track task completion. Built using modern cloud technologies and relay on Scrum methodology for development.


## Features

- **Create Tasks** - Users can create new tasks with title, description, due  date, and priority
- **Assign Tasks** - Tasks can be assigned to each team member
- **Track Completion** - Users can mark tasks as complete and track progress
- **Task List** - View, filter, and sort tasks assingned to members


## Technology Stack

- **Frontend:** [To be determined - e.g., React, Vue.js, Angular]
- **Backend:** [To be determined - e.g., Node.js, Python Flask/Django, Java Spring]
- **Database:** [To be determined - e.g., PostgreSQL, MongoDB, MySQL]
- **Cloud Platform:** [To be determined - e.g., AWS, Azure, GCP]
- **DevOps Tools:** Git, GitHub, CI/CD (to be implemented)

## Group Information

### Group Details
- **Programme:** CSN-03
- **Group Number:** 04
- **Course:** IS 384 – Cloud and DevOps
- **Instructor:** Mr. Christian

### Team Members and Roles

| Role           | Name          | Registration Number | GitHub Username |
|----------------|---------------|---------------------|----------------|
| Product Owner | ASHURA ABASI JUMA | 31072/T.2023 | sheyriz |
| Scrum Master | DAVID ZENO SIKUKUU | 32347/T.2023 | holiday-UI |
| Developer 1 | KABWE KASIM RASHIDI | 31432/T.2023 | Chammy-5050 |
| Developer 2 | JACOB LUCAS BULLUGU | 32285/T.2023 | ngollodev |
|Developer 3| NURU MOHAMED KISIMIKWE |32226/T.2023 | nur523 |
## Repository Structure

```
is384-scrum-task-app-CSN-03/
│
├── README.md                 # This file
├── scrum-overview.md         # Scrum roles, events, and artifacts
├── sprint-plan.md            # Product backlog, sprint goal, and DoD

```

## DEVELOPMENT WORKFLOW

This project follows Scrum methodology:

1. **Sprint Planning** - Team selects items from Product Backlog
2. **Daily Scrum** - Daily 15-minute standup meetings
3. **Sprint Review** - Demo completed work to stakeholders
4. **Sprint Retrospective** - Reflect and improve

See `scrum-overview.md` for detailed Scrum process information.

## Git Workflow

- **Main Branch:** Production-ready code
- **Feature Branches:** `feature/<registration-number>` for individual work
- **Pull Requests:** All changes must go through PR review before merging

### Branch Naming Convention
- Feature branches: `feature/<registration-number>`
- Bug fixes: `fix/<registration-number>-<brief-description>`
- Hotfixes: `hotfix/<registration-number>-<brief-description>`

### Commit Message Format
We follow conventional commits:
- `feat: add task creation functionality`
- `fix: resolve task assignment bug`
- `docs: update README with installation steps`
- `test: add unit tests for task API`

## Contributing

1. Create a feature branch: `git checkout -b feature/<your-registration-number>`
2. Make your changes and commit with descriptive messages
3. Push to your branch: `git push origin feature/<your-registration-number>`
4. Open a Pull Request to merge into main
5. Ensure at least one team member reviews your PR before merging

## Definition of Done

A task is considered "Done" when:
1. Code is written, reviewed, and merged to main branch
2. All unit tests pass (minimum 80% code coverage)
3. Code follows team coding standards
4. Documentation is updated
5. Feature is tested manually and works as expected
6. No critical bugs or security vulnerabilities

See `sprint-plan.md` for detailed Definition of Done criteria.

---

**Note:** This is a group assignment for IS 384 – Cloud and DevOps. Repository access has been granted to the instructor (GitHub username: `christiansolomon`) for evaluation purposes.

