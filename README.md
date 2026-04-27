# synent-task-3
The To-Do List (CLI) is a command-line based task management application designed to help users organize, track, and manage their daily activities efficiently. It provides a simple and intuitive menu-driven interface where users can perform essential operations such as adding new tasks, viewing all existing tasks, and deleting tasks that are no longer needed.

At its core, the application maintains a dynamic list that stores tasks during program execution. Each task entered by the user is appended to this list and displayed with a corresponding index number, making it easy to identify and manage individual entries. The numbering system allows users to select specific tasks for deletion without confusion, improving usability.

The program operates in a continuous loop, ensuring that users can perform multiple operations in a single session without restarting the application. The menu is repeatedly displayed after each action, allowing seamless navigation between different functionalities. This interactive design enhances user experience and makes the application more practical for real-world use.

A key aspect of the program is its input validation and error handling. The application checks for invalid inputs such as empty task entries or incorrect task numbers during deletion. Instead of crashing, it provides appropriate feedback and prompts the user to enter valid data. This ensures stability and reliability of the program even when unexpected inputs are provided.

Although the basic version stores tasks temporarily (in-memory), the structure of the program can be easily extended to support persistent storage using files or databases, allowing tasks to be saved and retrieved across sessions. Additional enhancements such as task prioritization, deadlines, or status tracking (completed/pending) can also be integrated to make the system more advanced.

From a learning perspective, the To-Do List (CLI) project is highly valuable as it demonstrates several fundamental programming concepts, including:

Lists (data structures) for storing and managing tasks
Loops for continuous program execution
Conditional statements for decision-making and menu handling
Functions and modular design for better code organization
User input handling and validation for robust interaction
