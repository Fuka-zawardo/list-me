# List Me

This is a simple ToDo list management app built with Vue 3 using the Composition API. The application allows users to create tasks categorized under Business and Personal. Tasks are stored in the localStorage for persistence.

## Application Structure

- **Script Setup**:

  - Imports required modules from Vue (`ref`, `onMounted`, `computed`, `watch`).
  - Defines reactive variables to hold the todos, name, input fields and a computed variable to hold the todos sorted in ascending order of creation.
  - Uses `watch` functions to save the name and todos to localStorage whenever they are updated.
  - Defines functions `addTodo` and `removeTodo` to manage the todo list.
  - On component mount, it retrieves the stored name and todos from localStorage.

- **Template**:

  - Defines the main layout for the application, divided into sections for greeting, creating a task, and displaying the todo list.
  - Employs Vue directives such as `v-model`, `v-for` and event handlers like `@submit`, `@click` to manage the data and handle events.

- **Style**:
  - Contains custom styles for the application, including CSS variables for colors, shadows and other reusable elements.
  - Defines styles for input fields and buttons.
  - Different styles are applied based on the state of the todo (such as completed).

## Installation

To install and run this application, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/Fuka-zawardo/list-me.git
```

2. Navigate into the project directory:

```bash
cd list-me
```

3. Install the dependencies:

```bash
npm install
```

4. Start the project:

```bash
npm run dev
```

## Usage

- Enter your name in the input field under "What's up,".
- To create a new task, fill in the "What's on your task list?" input field.
- Choose a category for the task - Business or Personal.
- Click on "Add todo" to add the task to your list.
- You can mark a task as done by clicking on the checkbox.
- Click on the "Delete" button to delete a task.

## Support

For support or to report issues, please open an issue at https://github.com/Fuka-zawardo/list-me/issues

## Contribution

Contributions are always welcome! Please open a pull request with your changes.
