# Functional Requirements

## Scope
This document defines the core task-management functional requirements.

## Requirements

1. The user can add a due date to a task.
   - The system must allow setting a due date when creating a task.
   - The system must allow adding or updating a due date for an existing task.

2. A task can be edited.
   - The system must allow editing task details after creation.
   - Editable fields include, at minimum, task title/description and due date.

3. Tasks are sorted in order of date created.
   - The task list must be displayed in ascending order by creation timestamp (oldest first).
   - If two tasks have the same creation timestamp, the system should preserve insertion order.
