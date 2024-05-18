
### AirBnB Clone - The Console
The **AirBnB Clone - The Console** project is part of the ALX Software Engineering program. Its primary goal is to build a full web application similar to Airbnb. In this initial step, we focus on creating a custom command-line interface (CLI) to manage various aspects of the application, such as creating, updating, deleting, and retrieving objects².

#### Project Description
- **Objective**: Deploy a replica of the Airbnb website using your own server.
- **Components**:
    1. **Command Interpreter**: A shell-like interface for manipulating data without a visual interface. It's useful for development and debugging.
    2. **Website (Front-end)**: Includes both static and dynamic functionalities.
    3. **Comprehensive Database**: Manages backend functionalities.
    4. **API**: Provides communication between the front-end and backend of the system.
- **Supported Objects (Instances)**:
    - `BaseModel`
    - `User`
    - `City`
    - `Amenity`
    - `State`
    - `Review`
    - `Place`
- **Project Phases**:
    1. **Phase One**: Implement a powerful storage system that abstracts the handling of objects and their persistence. Key steps include:
        - Creating a parent class (`BaseModel`) for initialization, serialization, and deserialization of instances.
        - Establishing a flow of serialization/deserialization: `Instance <-> Dictionary <-> JSON string <-> File`¹.
- **How to Start the Command Interpreter**:
    - To begin, navigate to the project directory and run the following command:
        ```
        $ ./console.py
        ```
    - This will launch the command interpreter, and you'll see the `(hbnb)` prompt.

#### Available Commands
- `help`: Displays a list of available commands and their descriptions.
- `quit`: Exits the command interpreter.
