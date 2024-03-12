AirBnB_clone
Project Description
The AirBnB_clone project is a simplified replica of the Airbnb web application, focusing on the development of a console-based command interpreter. The primary goal is to create a functional system that allows users to manage and interact with various objects such as User, Place, State, City, Amenity, and Review through a command-line interface.

Command Interpreter
The command interpreter is a Python script named console.py that provides a text-based interface for users to interact with the AirBnB_clone project. The interpreter allows users to perform CRUD (Create, Read, Update, Delete) operations on the different classes mentioned above. Users can input commands to manage objects, display information, and manipulate the data in the system.

How to Start
To start the command interpreter, run the following command in your terminal:

bash
$ ./console.py

How to Use
The command interpreter supports the following commands:

create: Create a new instance of a class and save it to the JSON file.
show: Display information about a specific instance.
destroy: Delete an instance.
all: Display all instances or all instances of a specific class.
update: Update attributes of an instance.
For detailed information on each command, use the help command within the interpreter.

Examples
Here are some examples of commands you can use in the AirBnB_clone console:

bash
$ ./console.py
(hbnb) create User
(hbnb) show User 1234-5678
(hbnb) destroy User 1234-5678
(hbnb) all
(hbnb) update User 1234-5678 first_name "John"
