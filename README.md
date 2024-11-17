Overview
This project is a simplified version of Airbnb with select features.

Features
Command-Line Interface
Description
The command-line tool manages the application, allowing users to:

Create, view, update, and delete objects.
Perform operations like counting and computing statistics.
Usage
Run in interactive mode:

bash
./console.py
Or non-interactive mode:

bash
echo "command" | ./console.py

Commands
Command	Description	Example Usage
help	Shows available commands or command info.	help
quit	Exits the program.	quit
EOF	Ends the program (for piped inputs).	N/A
create	Creates a new <class_name> instance and prints its ID.	create <class_name>
show	Displays a specific instance by class name and ID.	show <class_name> <id>
destroy	Deletes an instance by class name and ID.	destroy <class_name> <id>
all	Lists all or class-specific instances.	all or all <class_name>
update	Modifies an instance's attributes.	update <class_name> <id> <key> <value>

Testing
Run all tests from the test/ folder with:

bash
python3 -m unittest discover tests
