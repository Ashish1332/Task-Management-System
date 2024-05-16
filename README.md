# Task Management System
A task management system to manage the tasks and its status.

# Contributors

Thanks to the following people who have contributed to this project:
- **[Pranav Lahitkar](https://github.com/PranavLahitkar)**
- **[Prathmesh Tiwari](https://github.com/username)** 


## Overview
This task management system is built using the Nest.js framework and MongoDB as a database. It allows you to create, update, and delete tasks and manage their statuses.

## Features
1. Create, update and delete tasks.
2. Assign task to a person.
3. Change task status between to-do, in-progress, and completed.
4. Validate status change.

## How to Setup
1. Clone the project repository
2. git clone https://github.com/Ashish1332/Task-Management-System)
3. Install the dependencies
```npm install```
4. Run the application
```npm run start```
5. Open the browser and visit http://localhost:3000/tasks to view the list of tasks.

## Current Tasks
- [ ] adding update-assignee service & controller
- [ ] adding user module
- [ ] adding project module
Introduction
This report documents the development of a task management system backend using NestJS, a progressive Node.js framework. The primary objective of this system is to assist users and organizations in efficiently managing, organizing, and prioritizing tasks. By leveraging the power of RESTful APIs and a relational database, this application aims to streamline task management processes, ensuring tasks can be added, updated, and deleted seamlessly.

Purpose and Scope
The purpose of this task management system is to provide a robust backend solution that supports comprehensive task management features. This system does not include a frontend interface but is designed to be tested using Postman software, which allows for thorough testing of the RESTful APIs. The scope of this project encompasses the creation, retrieval, updating, and deletion of tasks.

Technologies Used
NestJS
NestJS is a framework for building efficient, scalable Node.js server-side applications. It incorporates elements of OOP (Object-Oriented Programming), FP (Functional Programming), and FRP (Functional Reactive Programming). NestJS is built with TypeScript, which ensures type safety and supports modern JavaScript features.



Relational Database
A relational database, such as MongoDB, is used to store tasks and related data. These databases are chosen for their robustness, scalability, and support for complex queries and transactions.

Features
The task management system includes the following core features:
1. Task Creation: Users can create new tasks, providing necessary details such as title, description, priority, and due date.
2. Task Retrieval: Users can retrieve a list of tasks or a specific task by its ID. The system supports querying tasks based on various criteria such as priority or due date.
3. Task Update: Users can update existing tasks, modifying details such as title, description, priority, and due date.
4. Task Deletion: Users can delete tasks that are no longer needed.

API Endpoints
The backend system provides several RESTful API endpoints to support these features:
- POST /tasks: Create a new task.
- GET /tasks: Retrieve a list of tasks.
- GET /tasks/:id: Retrieve a specific task by ID.
- PUT /tasks/:id: Update a specific task by ID.
- DELETE /tasks/:id: Delete a specific task by ID.

Implementation Details
NestJS Modules and Controllers
The application is structured using NestJS modules and controllers. Each feature is encapsulated within its own module, promoting modularity and reusability.

- Tasks Module: Contains the business logic for managing tasks.
- Tasks Controller: Handles incoming HTTP requests and delegates them to the service layer.

Service Layer
The service layer contains the core business logic for handling tasks. It interacts with the database via a repository pattern, ensuring separation of concerns and promoting a clean architecture.

Data Access Layer
The data access layer interacts with the relational database. Using TypeORM, an Object-Relational Mapping (ORM) tool, the system maps TypeScript classes to database tables, allowing for seamless data manipulation using repository patterns.

Testing with Postman
Postman is used for testing the RESTful APIs. Each endpoint is tested to ensure it performs the intended operations correctly. Test cases include:
- Creating a new task.
- Retrieving all tasks.
- Retrieving a task by ID.
- Updating a task.
- Deleting a task.

