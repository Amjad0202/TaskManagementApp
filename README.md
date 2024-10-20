# 📝 Task Management App

Welcome to the **Task Management App**! This is a simple yet effective console-based Java application designed to help you manage your tasks efficiently. With this app, you can create, view, and complete tasks seamlessly.

---

## 🚀 Features

- **Add Task**: Easily create a new task with a name and description.
- **List Tasks**: View all your tasks with their current status (completed or not).
- **Mark Task as Completed**: Quickly mark any task as done with just a few clicks.

### 🔮 Future Enhancements

- **Data Persistence**: Save tasks to a file (e.g., JSON or text) to retain them even after closing the app.
- **Task Deadlines**: Implement deadline and priority features for better task management.
- **Graphical User Interface (GUI)**: Upgrade to a more user-friendly interface using JavaFX.

---

## 📚 Getting Started

### 📋 Prerequisites

Before running the app, make sure you have:

- [Java JDK 11+](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) installed on your machine.
- A terminal or command prompt to compile and run the Java program.

### 📥 Installation Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/TaskManagementApp.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd TaskManagementApp
   ```

3. **Compile the Java Files**:
   ```bash
   javac src/TaskManager.java
   ```

4. **Run the Program**:
   ```bash
   java -cp src TaskManager
   ```

---

## 💻 How to Use

1. When the program starts, you’ll see a menu with options:
   - **1**. Add a new task.
   - **2**. List all tasks.
   - **3**. Mark a task as completed.
   - **0**. Exit the application.

2. Select an option by entering the corresponding number and follow the prompts.

### 🌟 Example Interaction

```
Task Management System
1. Add Task
2. List Tasks
3. Mark Task as Completed
0. Exit

Enter your choice: 1
Enter task name: Complete Java Project
Enter task description: Finish the task management app by the end of the week.
Task added successfully!
```

---

## 🗂 Project Structure

```
TaskManagementApp/
│
├── src/
│   ├── Task.java          # Defines the Task class with attributes and methods.
│   └── TaskManager.java   # Main program that manages tasks using ArrayList.
├── README.md              # This file contains project documentation.
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests for improvements, such as:
- Adding a file-based storage system.
- Enhancing the user interface with JavaFX.
- Implementing task sorting based on deadlines.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
