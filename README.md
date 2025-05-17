## 🧩 Mini Project: Task Manager
## 🎯 Goal:
Create a task management system using TypeScript that supports adding, completing, deleting, and filtering tasks. You’ll apply core TypeScript concepts without relying on frameworks.

✅ Feature Breakdown (What to Build)
## 1. Define the Task Structure
  Each task should have:
- A unique ID
- A title
- A status: completed or not
  Define the structure using an interface.

## 2. Create a Task Manager
Build a class to handle task operations:

- Add a new task
- Mark a task as completed
- Delete a task by ID
- Return tasks based on filters: all, completed, or pending
  Use proper access modifiers (private, public) to encapsulate logic.

## 3. Implement Task Filtering
Use an enum to define filter options:
- All
- Completed
- Pending
  The user should be able to request a list of tasks based on these filters.

## 4. Add Utility Methods
Create a utility method to:
- Search tasks by any property
- Count tasks by status
- Optionally sort tasks (by title or date, if you implement timestamps)
  Use type aliases, union types, or generics where appropriate.

## 5. Build a Simple UI (optional but recommended)
You can choose one:
Console version using Node.js:
- Use readline or any input method
- Interact with the user via console commands

Basic HTML UI:

- Input box and buttons
- Display task list dynamically
Avoid using Angular or any frontend framework for this phase.

## 6. Data Persistence (Optional Bonus)
- Store tasks temporarily in memory (array)
- Bonus: store and load tasks from localStorage (if using browser)

🎓 Skills You'll Validate
- Interfaces
- Classes and OOP
- Access modifiers (public, private)
- Enums
- Union types and type guards
- Generics (optional)
- Separation of concerns
- Simple module/file structure
- Type safety and clean code
