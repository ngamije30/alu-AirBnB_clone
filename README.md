Description
This project provides a Python command-line interpreter for managing Airbnb data, allowing users to create, manage, and book property listings for short-term rentals.

Command Interpreter
The command interpreter serves as the interface for interacting with the Airbnb clone allowing the user to create, retrieve, update, and delete objects.

Getting started

Installation:
Clone this repository using Git:
git clone https://github.com/yourusername/alu-AirBnB_clone.git
Navigate to the project directory:
cd alu-AirBnB_clone
Running the Interpreter:
To start the command interpreter, navigate to the project directory and run:
From the project directory, execute:

./console.py

3. **How to use the command interpreter**

 Once the command interpreter is running, you can use the following commands:

- create <class>: Create a new instance of the specified class (e.g., create User).
- show <class> <id>: Display information about the specified instance (e.g., show User 1234).
- update <class> <id> <attribute> "<value>": Update the specified attribute of the specified instance (e.g., update User 1234 email "example@example.com").
- destroy <class> <id>: Delete the specified instance (e.g., destroy User 1234).
- all <class>: Display information about all instances of the specified class (e.g., all User).

4. **Examples**

Here are some examples of how to use the command interpreter:

- create User email="example@example.com" password="password"
- show User 1234
- update User 1234 email "new@example.com"
- destroy User 1234
- all User

5. **Authors**
 
 - NGAMIJE RUHUMULIZA Davy is the only contributor to this work
