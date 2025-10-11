# "My Notion" Planner

## Introduction:

A Graphical User Interface (GUI) created as a task and event scheduling written in Python. The program use Tkinter module for the display window following by JSON and OS module for the data saver and loader. 
The program is able to input both task and event, prioritize it, add details for memorization, and save the data on to the local device.
Current Version: 1.0.0 | Latest Edit: 19 Sept 2025

![Interface Picture](Interface.png)

## Improvements:

1. Interface improvement for better user experience
2. Registration system for non preset accounts
3. Alarm settings
4. CPM - PERT Systems
5. Human Resource Management (Assigning work)

## For Developers: Compiling the Python Script to a Standalone .EXE

If you want to create a standalone executable (.exe) file for Windows, you can use **PyInstaller**.

1.  **Install PyInstaller**
    * Open your command line (Terminal or Command Prompt) and run:
        ```bash
        pip install pyinstaller
        ```

2.  **Navigate to the Script Directory**
    * Change your directory to the folder containing the script:
        ```bash
        cd path\to\your\script\folder
        ```

3.  **Compile to .EXE**
    * Run the PyInstaller command. The `--onefile` flag creates a single executable, and `--windowed` prevents a console window from opening:
        ```bash
        pyinstaller --onefile --windowed "GUI To-do List.py"
        ```

**Result:** The final executable, **`GUI To-do List.exe`**, will be located in the newly created **`dist`** folder.

## NOTED:
For Editing | Username: Test_user / Password: 0123
