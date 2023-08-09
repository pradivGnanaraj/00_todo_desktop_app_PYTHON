# My To-Do Application

This repository contains a simple To-Do application implemented in Python. The application has both command-line and graphical user interfaces, providing users with an easy way to manage their tasks.

## Files

1. `cli.py`: This file contains a command-line interface (CLI) implementation of the To-Do application. It allows users to interact with their tasks using text-based commands.

2. `functions.py`: This file defines utility functions used by both the CLI and GUI versions of the application. It provides functions for reading and writing to-do tasks to a text file.

3. `guilty.py`: This file implements a graphical user interface (GUI) for the To-Do application using the PySimpleGUI library. Users can manage their tasks through an interactive GUI.

4. `web.py`: This file implements a web-based interface for the To-Do application using the Streamlit framework. It allows users to manage tasks through a web browser.

## How to Run

### CLI Version (`cli.py`)

1. Make sure you have Python installed on your system.
2. Run the `cli.py` script using the command: `python cli.py`.
3. Follow the prompts to interact with the To-Do application.

### GUI Version (`gui.py`)

1. Install the PySimpleGUI library if not already installed: `pip install PySimpleGUI`.
2. Run the `gui.py` script using the command: `python gui.py`.
3. Interact with the To-Do application using the graphical interface.

### Web Version (`web.py`)

1. Install the Streamlit library if not already installed: `pip install streamlit`.
2. Run the `web.py` script using the command: `streamlit run web.py`.
3. Access the To-Do application through a web browser by following the link provided.

## Functionality

- **Adding Tasks**: Users can add new tasks to their to-do list.
- **Listing Tasks**: Users can view their existing tasks.
- **Editing Tasks**: Users can modify the content of a specific task.
- **Completing Tasks**: Users can mark tasks as completed and remove them from the list.

## Dependencies

- Python 3.x
- PySimpleGUI (for GUI version)
- Streamlit (for web version)

## Contribution

Feel free to contribute to this project by submitting pull requests or suggesting improvements. Please follow the standard coding guidelines and maintain consistency with the existing code.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The PySimpleGUI and Streamlit libraries for providing user-friendly interfaces.
- The Python community for their continuous support and contributions.
