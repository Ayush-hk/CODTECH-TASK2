Name: Aayush Thapa

Company: CODTECH IT SOLUTION

ID: CT08DS8554

DOMAIN: WEB DEVELOPMENT

DURATION: SEPT 25TH TO 25TH OCT 2024

MENTOR: NEELA SANTHOSH KUMAR

### Overview of the Advanced To-Do List

**Project Name:** Advanced To-Do List

**Description:** This web application allows users to manage their tasks effectively with features such as adding tasks, setting due dates, editing tasks, marking them as completed, and filtering tasks based on their status (completed or pending). The tasks are stored in the browser's local storage, ensuring persistence even after the page is refreshed.

---

### Key Features

1. **Task Management:**
   - Users can add new tasks with optional due dates.
   - Each task can be edited or removed.

2. **Completion Status:**
   - Users can mark tasks as completed by clicking on the task text, which visually indicates completion.

3. **Filtering:**
   - Users can filter tasks based on their completion status: all, completed, or pending.

4. **Local Storage:**
   - Tasks are saved in the browser's local storage, enabling persistence across page reloads.

---

### Code Structure

#### HTML

- **Container:** The main layout of the application is wrapped in a `<div>` with the class `container`, which holds all UI elements.
- **Inputs:** 
  - A text input for adding new tasks.
  - A date input for setting due dates.
  - A button for adding tasks.
  - A dropdown for filtering tasks.
- **Task List:** An unordered list (`<ul>`) to display tasks dynamically.

#### CSS

- **Styling:** Basic styles are applied to enhance the appearance, including layout, colors, padding, and responsive design.
- **Classes:** Specific classes for completed tasks, buttons for editing/removing tasks, and the filter dropdown.

#### JavaScript

- **Event Listeners:** 
  - `DOMContentLoaded`: Loads existing tasks from local storage upon page load.
  - Click events for adding tasks, filtering tasks, and editing/removing tasks.
  
- **Functions:**
  - **addTask():** Handles task creation, updates the UI, and saves tasks to local storage.
  - **editTask(li):** Prompts the user to edit the task text and due date, updating the display and saving changes.
  - **saveTasks():** Collects task data and stores it in local storage.
  - **loadTasks():** Retrieves tasks from local storage and displays them.
  - **filterTasks():** Filters the displayed tasks based on their completion status.

---

### Conclusion

The Advanced To-Do List application is a functional and user-friendly tool that allows users to manage their tasks efficiently. It showcases essential web development skills such as DOM manipulation, event handling, and local storage management. The application can be further enhanced by implementing features like user authentication, task prioritization, and due date notifications. Overall, this project serves as a great example of a practical, interactive web application.

![Screenshot (6)](https://github.com/user-attachments/assets/6ad9f0d7-f494-472b-b19b-d25f3eb84a7e)

