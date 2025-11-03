# "My Notion" Planner 📅

## Introduction

"My Notion" Planner is a **Graphical User Interface (GUI)** application for task and event scheduling, built entirely in **Python**.

The application uses the **Tkinter** module for the user interface and the built-in **JSON** and **OS** modules for local data storage and retrieval.

### Key Features:
* Input and manage both tasks and events.
* Prioritize items for better organization.
* Add detailed notes and descriptions.
* Securely save all planning data locally on your device.

---

**Current Version:** 1.0.1 | **Latest Edit:** September 19, 2025

![Planner Interface Screenshot](Interface.png)

---

## Planned Improvements 🚀

We are actively working on the following features:

1.  **Interface Rework:** Enhancing the GUI for a more intuitive and modern user experience.
2.  **User Registration:** Implementing a user registration system for non-preset accounts.
3.  **Alarm Settings:** Adding customizable reminders and notifications.
4.  **Project Management Tools:** Integrating **CPM-PERT** (Critical Path Method / Program Evaluation and Review Technique) functionality for complex projects.
5.  **Human Resource Management:** Features for assigning and tracking work among team members.

---

## For Developers: Compiling to a Standalone .EXE

If you want to create a standalone executable (`.exe`) file for Windows, you can use the **PyInstaller** package.

**Note:** Since this is a GUI application, we use the `--windowed` flag to prevent the console window from opening when the program runs.

1.  **Install PyInstaller**
    * Open your command line (Terminal or Command Prompt) and run the installation command:
        ```bash
        pip install pyinstaller
        ```

2.  **Navigate to the Script Directory**
    * Change your directory to the folder containing the main script (assuming the filename is still **`GUI To-do List.py`**):
        ```bash
        cd path\to\your\script\folder
        ```

3.  **Compile the Executable**
    * Run the PyInstaller command:
        ```bash
        pyinstaller --onefile --windowed "GUI To-do List.py"
        ```

**Result:** The final executable, **`GUI To-do List.exe`**, will be generated in the **`dist`** folder within your script's directory.

---

## ⚠️ IMPORTANT NOTE

Please ensure you **remove** or replace all placeholder test accounts and credentials before deploying or sharing the application. 
However for only testing purpose | Username: Test_user / Password: 0123
