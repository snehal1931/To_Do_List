# Simple To-Do List Application

This is a basic command-line To-Do List application written in Python. It's a simple, yet effective tool for managing your daily tasks. The application uses a text file (`tasks.txt`) to save and load tasks, ensuring your list is persistent across sessions.

---

### Features

-   **Add Tasks:** Add new tasks to your to-do list with a simple command.
-   **View Tasks:** Display all current tasks in a numbered list. The program will let you know if there are no tasks to display.
-   **Mark as Done:** Remove a task from the list by its index once it's completed. The program includes error handling for invalid input or indices.
-   **Data Persistence:** Tasks are automatically saved to and loaded from a file, so you don't lose your list when you close the application.

---

### How to Run

1.  **Prerequisites:** Make sure you have Python 3 installed on your system.
2.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/your-repo-name.git](https://github.com/YourUsername/your-repo-name.git)
    cd your-repo-name
    ```
    (Remember to replace `YourUsername` and `your-repo-name` with your actual GitHub username and repository name.)
3.  **Run the script:**
    ```bash
    python todo.py
    ```

---

### Usage

When you run the application, you will be presented with a menu. Follow the on-screen instructions to interact with your to-do list.

-   Enter `1` to add a new task.
-   Enter `2` to view all tasks.
-   Enter `3` to mark a task as done by its number.
-   Enter `4` to exit the application. Your tasks will be saved automatically.

### Example
