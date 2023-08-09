# To-Do Application System Design

## Introduction

The To-Do application is designed to provide users with a convenient way to manage their tasks. It includes a command-line interface (CLI), a graphical user interface (GUI) using PySimpleGUI, and a web-based interface using Streamlit.

## Architecture

The architecture of the To-Do application consists of four main components:

1. `cli.py`: This component handles user interactions through the command-line interface. It communicates with the `functions` module to perform operations on the to-do list data.

2. `functions.py`: The functions module contains utility functions for reading and writing to-do tasks to a text file. It provides an interface for both the CLI and GUI/web components to access and manipulate task data.

3. `gui.py`: This component provides a graphical user interface using the PySimpleGUI library. It interacts with the `functions` module to manage tasks and display them to the user.

4. `web.py`: The web component implements a web-based interface using the Streamlit framework. It communicates with the `functions` module to manage tasks and display them in a web browser.

## Data Flow

1. User interactions in the CLI version (`cli.py`) are processed by taking user input and performing corresponding actions using the functions provided by the `functions` module. The to-do data is read from and written to a text file.

2. In the GUI version (`gui.py`), user interactions are handled by the PySimpleGUI framework. The GUI elements are updated based on user actions, and the functions from the `functions` module are used to manage the to-do data.

3. The web version (`web.py`) uses the Streamlit framework to create a web-based interface. User interactions are processed similarly to the GUI version, with data managed through the `functions` module.

## File Structure

- `cli.py`
- `functions.py`
- `gui.py`
- `web.py`
- `todos.txt` (Text file for storing to-do tasks)

## Dependencies

- Python 3.x
- PySimpleGUI (for GUI version)
- Streamlit (for web version)

## Interaction Flow

1. User opens the CLI version (`cli.py`) and follows the prompts to manage their to-do tasks.
2. User opens the GUI version (`gui.py`) and interacts with the graphical interface to add, edit, complete, and view tasks.
3. User opens the web version (`web.py`) in a browser, adds tasks through the text input, and marks tasks as completed by checking the checkboxes.

## Data Management

- The `functions` module handles reading and writing to-do tasks from and to the `todos.txt` file.
- Tasks are stored as individual lines in the text file.

## Limitations and Future Improvements

- Current storage mechanism uses a text file; consider using a database for more efficient data management.
- Implement user authentication and task sharing features for collaborative task management.
- Improve the GUI with additional styling and features.

## Conclusion

The To-Do application provides users with multiple interfaces to manage their tasks conveniently. Users can choose between CLI, GUI, and web-based interactions to manage their to-do lists effectively.

---

**Note:** This document provides an overview of the To-Do application's system design. It is intended to guide developers and contributors in understanding the application's architecture and components.
