# Airbnb Clone Project

This is a project to create a clone of the popular vacation rental platform, Airbnb. This project aims to provide users with a platform to find and book unique travel experiences.

## Description of the Project

The Airbnb Clone project is a full-stack web application that allows users to find and book vacation rental properties. The project includes a database to store information about properties and user accounts, as well as a front-end interface that allows users to search and book properties.

Users can search for properties based on location, dates, and other criteria, and view detailed information about each property, including photos, descriptions, and reviews from other users. They can also book properties and manage their reservations through the platform.

### Description of the Command Interpreter

The command interpreter is a module that allows users to interact with the Airbnb Clone project through the command line. This module provides a user-friendly interface for managing properties, reservations, and other aspects of the platform.

The command interpreter is written in Python and is designed to be easy to use and understand. It supports a variety of commands for managing properties and reservations, including commands for creating, updating, and deleting properties, and for managing reservations.

### How to Start It

To start the command interpreter, open a terminal window and navigate to the project directory. Then, enter the following command:

```
python3 manage.py
This will launch the command interpreter, which you can then use to manage the Airbnb Clone project.
```

### How to Use It
The command interpreter provides a variety of commands for managing properties and reservations. The available commands are listed below, along with a description of what each command does:

create: creates a new property or reservation
update: updates an existing property or reservation
delete: deletes a property or reservation
show: displays information about a property or reservation
list: lists all properties or reservations
quit: quits the command interpreter
To use the command interpreter, simply enter one of the available commands followed by the relevant information. For example, to create a new property, you might enter the following command:

python
```
create property
And to show information about a reservation, you might enter the following command:
```

sql
```
show reservation 123
```

##Examples
Here are a few examples of how you might use the command interpreter to manage properties and reservations:

sql
```
# Create a new property
> create property
Enter property name: Ocean View Villa
Enter property description: Beautiful villa with an ocean view
Enter property location: Hawaii

# Update a property
> update property 1
Enter property name: Paradise Villa
Enter property description: Stunning villa with a breathtaking view of the ocean

# Delete a property
> delete property 1
Are you sure you want to delete Paradise Villa? (y/n) y
Property Paradise Villa has been deleted.

# Show information about a property
> show property 1
Name: Paradise Villa
Description: Stunning villa with a breathtaking view of the ocean
Location: Hawaii

# List all properties
> list properties
1. Paradise Villa
2. Mountain Retreat
3. Urban Loft

# Create a new reservation
> create reservation
Enter property ID: 2
Enter start date (YYYY-MM-DD): 2022-07-01
Enter end date (YYYY-MM-DD): 2022-07-07

# Show information about a reservation
> show reservation
```
