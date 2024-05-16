# Tasks Endpoints

## Task CRUD (Create, Read, Update, Delete) Operations
- `GET /tasks` for retrieving a list of tasks
- `GET /tasks/:id` for retrieving a specific task by ID
- `POST /tasks` for creating a new task
- `PUT /tasks/:id` for updating an existing task
- `DELETE /tasks/:id` for deleting a specific task

## Task Status Updates
- `PUT /tasks/:id/status` for updating the status of a task

## Task Assignment Operations
- `GET /tasks/assigned` for retrieving a list of assigned tasks
- `PUT /tasks/:id/assign` for assigning a task to a user
- `PUT /tasks/:id/unassign` for unassigning a task from a user

# Task Schema Properties
- `title`: A string property that represents the title or brief description of the task
- `description`: A string property that provides a more detailed description of the task
- `dueDate`: A date property that represents the deadline for completing the task
- `status`: A string property that represents the current status of the task (e.g. "To Do", "In Progress", "Completed")
- `assignedTo`: A string property that represents the user who has been assigned to the task
- `createdAt`: A date property that represents the date and time the task was created
- `updatedAt`: A date property that represents the date and time the task was last updated
