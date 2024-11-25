# Angular To-Do List App

### First Angular project aimed at learning the core aspects of the framework.

This project is a simple To-Do List application built with Angular. It serves as an introduction to the main concepts of the framework, including components, services, data binding, routing, and form handling.

## Features

1. **Add a new task**:
   - Users can add new tasks to the list using a simple input field.
   - **Learning Goal**: Understand how to use Angular forms (Template-Driven or Reactive) to handle user inputs and bind form data to components.

2. **Mark tasks as completed**:
   - Users can mark a task as completed, and the UI will update to reflect this change.
   - **Learning Goal**: Practice data binding and conditional rendering using Angular directives like `*ngIf` and `*ngFor`.

3. **Delete a task**:
   - Users can remove a task from the list.
   - **Learning Goal**: Learn how to update component state and use event binding to trigger actions when a button is clicked.

4. **Filter tasks by status (all, completed, pending)**:
   - Users can filter the task list to display all tasks, only completed tasks, or only pending tasks.
   - **Learning Goal**: Gain experience with component communication, using services to share data between components and handle state changes.

5. **Task persistence with local storage (optional)**:
   - Save the list of tasks in the browser’s local storage, so they persist after a page refresh.
   - **Learning Goal**: Explore integration with browser APIs and learn how to manage persistent state in a front-end application.

## Why this project?

This To-Do List project is an ideal starting point to grasp the fundamentals of Angular. It covers several essential features and learning points:

- **Component Architecture**: Learn how to break down an application into reusable components.
- **Data Binding**: Master one-way and two-way data binding to dynamically update the UI.
- **Directives**: Understand structural directives like `*ngFor` and `*ngIf` for rendering lists and conditionally displaying elements.
- **Routing (Optional)**: Add a simple navigation structure (e.g., task views) to practice routing and URL management.
- **Services and Dependency Injection**: Use services to manage and share data between components, a critical part of building scalable Angular applications.

---

### Getting Started

To get started with this project, clone the repository and install the necessary dependencies:

```bash
git clone <repository-url>
cd angular-todo-list
npm install
```

Run the application locally with:
```bash
ng serve
```

Then open your browser and navigate to http://localhost:4200/ to view the app.

---

