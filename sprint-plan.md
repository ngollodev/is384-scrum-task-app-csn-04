# Sprint Plan

## 1. Product Backlog

### Backlog Item 1: Add New Task
- **Priority:** High (P0)
- **Story Points:** 5
- **User Story:** As a user, I want to create a new task so that I can track my work items.
- **Acceptance Criteria:**
  - User can access "Create Task" form
  - Form includes fields: Title (required), Description (optional), Due Date (optional), Priority (Low/Medium/High)
  - User can submit the form to create a task
  - Success message is displayed upon creation
  - New task appears in the task list
- **Technical Notes:**
  - Backend API endpoint: `POST /api/tasks`
  - Frontend component: TaskCreationForm
  - Database: tasks table with appropriate schema

### Backlog Item 2: Assign Task to User
- **Priority:** High (P0)
- **Story Points:** 8
- **User Story:** As a project manager, I want to assign tasks to team members so that work is distributed effectively.
- **Acceptance Criteria:**
  - User can view a list of available team members
  - User can select a task and assign it to a team member
  - Assigned user receives a notification
  - Task status updates to "Assigned"
  - Task shows assigned user in the task details
- **Technical Notes:**
  - Backend API endpoint: `PUT /api/tasks/{id}/assign`
  - User management system required
  - Notification service integration

### Backlog Item 3: Mark Task Complete
- **Priority:** High (P0)
- **Story Points:** 3
- **User Story:** As a user, I want to mark tasks as complete so that I can track my progress.
- **Acceptance Criteria:**
  - User can toggle task completion status
  - Completed tasks are visually distinct (e.g., strikethrough, different color)
  - Task status updates to "Completed"
  - Completion date is recorded
  - Completed tasks can be filtered or grouped separately
- **Technical Notes:**
  - Backend API endpoint: `PUT /api/tasks/{id}/complete`
  - Frontend: Task status toggle component
  - Database: Update task status and completion_date fields

### Backlog Item 4: Display Task List
- **Priority:** High (P0)
- **Story Points:** 5
- **User Story:** As a user, I want to view all my tasks in a list so that I can see what needs to be done.
- **Acceptance Criteria:**
  - Task list displays all tasks (or filtered by user)
  - Tasks show: Title, Status, Assigned User, Due Date, Priority
  - Tasks can be sorted by: Due Date, Priority, Status, Created Date
  - Tasks can be filtered by: Status, Assigned User, Priority
  - List is responsive and works on mobile devices
- **Technical Notes:**
  - Backend API endpoint: `GET /api/tasks` with query parameters for filtering/sorting
  - Frontend: TaskList component with sorting/filtering UI
  - Pagination for large task lists

### Backlog Item 5: Notifications
- **Priority:** Medium (P1)
- **Story Points:** 8
- **User Story:** As a user, I want to receive notifications when tasks are assigned to me or updated so that I stay informed.
- **Acceptance Criteria:**
  - User receives notification when task is assigned to them
  - User receives notification when assigned task is updated
  - User receives notification when task is due soon (24 hours before)
  - Notifications appear in a notification center/bell icon
  - User can mark notifications as read
  - User can dismiss notifications
- **Technical Notes:**
  - Real-time notification system (WebSocket or Server-Sent Events)
  - Backend: Notification service
  - Frontend: Notification component and notification center
  - Database: notifications table

---

## 2. Sprint Goal

Deliver a functional cloud-based task management system that allows users to create, assign, view, and complete tasks, establishing the foundation for collaborative task management.

---

## 3. Definition of Done (DoD)

A Product Backlog item is considered "Done" when:

1. Code is written, reviewed, and merged to the main branch via Pull Request
2. All tests pass (unit tests and integration tests, if applicable)
3. Documentation is updated (README.md and relevant API documentation)
4. Feature is manually tested and works as expected with no critical bugs

---

## Sprint Backlog (Selected Items for This Sprint)

Based on team capacity and sprint goal, the following items are selected for Sprint 1:

| Backlog Item | Story Points | Assigned To | Status |
|--------------|--------------|-------------|--------|
| Add New Task | 5 | Developer 1 - KABWE KASIM RASHIDI | Not Started |
| Assign Task to User | 8 | Developer 2 - JACOB LUCAS BULLUGU | Not Started |
| Mark Task Complete | 3 | Developer 3 - DAVID ZENO SIKUKUU | Not Started |
| Display Task List | 5 | Developer 4 - [NAME] | Not Started |
| Notifications | 8 | Developer 5 - [NAME] | Not Started |

**Total Story Points:** 29

**Note:** [Developer 1], [Developer 2], [Developer 3], [Developer 4], and [Developer 5] represent the assigned team members for each backlog item.

---

## Task Breakdown

### Backlog Item 1: Add New Task
- [ ] Design and create task creation form UI
- [ ] Implement backend API endpoint `POST /api/tasks`
- [ ] Create database schema for tasks table
- [ ] Add form validation (frontend and backend)
- [ ] Write unit tests for API endpoint
- [ ] Write unit tests for frontend component
- [ ] Integration testing
- [ ] Update documentation

### Backlog Item 2: Assign Task to User
- [ ] Design user selection UI component
- [ ] Implement backend API endpoint `PUT /api/tasks/{id}/assign`
- [ ] Create user management system (if not exists)
- [ ] Add user-task relationship in database
- [ ] Implement notification trigger on assignment
- [ ] Write unit tests
- [ ] Integration testing
- [ ] Update documentation

### Backlog Item 3: Mark Task Complete
- [ ] Design task status toggle UI
- [ ] Implement backend API endpoint `PUT /api/tasks/{id}/complete`
- [ ] Update database schema for completion tracking
- [ ] Add visual indicators for completed tasks
- [ ] Write unit tests
- [ ] Integration testing
- [ ] Update documentation

### Backlog Item 4: Display Task List
- [ ] Design task list UI component
- [ ] Implement backend API endpoint `GET /api/tasks` with filtering/sorting
- [ ] Add sorting functionality (frontend)
- [ ] Add filtering functionality (frontend)
- [ ] Implement pagination (if needed)
- [ ] Make UI responsive
- [ ] Write unit tests
- [ ] Integration testing
- [ ] Update documentation

### Backlog Item 5: Notifications
- [ ] Design notification UI component
- [ ] Implement notification service (backend)
- [ ] Set up real-time communication (WebSocket/SSE)
- [ ] Create notifications table in database
- [ ] Implement notification triggers (assignment, updates, due dates)
- [ ] Add notification center/bell icon
- [ ] Implement mark as read functionality
- [ ] Write unit tests
- [ ] Integration testing
- [ ] Update documentation

---

## Risk Assessment

| Risk | Impact | Probability | Mitigation |
|------|--------|-------------|------------|
| Team member unavailability | High | Low | Cross-train team members, document work |
| Technical complexity underestimated | Medium | Medium | Break down tasks further, seek help early |
| Integration issues | Medium | Medium | Early integration testing, continuous integration |
| Scope creep | High | Low | Strict adherence to Sprint Goal, Product Owner prioritization |

---

**Note:** This sprint plan is a living document and may be updated during the sprint as new information becomes available. However, the Sprint Goal remains fixed for the duration of the sprint..

