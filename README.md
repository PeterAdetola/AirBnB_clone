![hbnb logo](img/65f4a1dd9c51265f49d0.png)
# AirBnB_clone - The Console
This is the first step towards building the first full web application in alx: the AirBnB clone. 

## Description
This team project is part of the ALX School Full-Stack Software Engineer program. It's the first step towards building a first full web application: an AirBnB clone. This first step consists of a custom command-line interface for data management, and the base classes for the storage of this data. Console commands allow the user to create, update, and destroy objects, as well as manage file storage. Using a system of JSON serialization/deserialization, storage is persistent between sessions.

##Usage
The console works both in interactive mode and non-interactive mode, much like a Unix shell. It prints a prompt (hbnb) and waits for the user for input.

| Command | Example |
|---------|---------|
| Run the console | `./console.py` |
| Quit the console | `(hbnb) quit` |
| Display the help for a command | `(hbnb) help <command>` |
| Create an object (prints its id) | `(hbnb) create <class>` |
| Show an object | `(hbnb) show <class> <id> or (hbnb) <class>.show(<id>)` |
| Destroy an object | `(hbnb) destroy <class> <id> or (hbnb) <class>.destroy(<id>)` |
| Show all objects, or all instances of a class | `(hbnb) all or (hbnb) all <class>` | 
| Update an attribute of an object | `(hbnb) update <class> <id> <attribute name> "<attribute value>" or (hbnb) <class>.update(<id>, <attribute name>, "<attribute value>")` |

Non-interactive mode example

```
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  all  count  create  destroy  help  quit  show  update
```
##Models
The folder models contains all the classes used in this project.

| File | Description | Attributes |
|------|-------------|------------|
| base_model.py | BaseModel class for all the other classes | id, created_at, updated_at |

