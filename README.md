# Contact Management System

A console-based Contact Management System developed in Java that allows users to efficiently store, manage, and organize contact information using file handling techniques.

## Features

* Add new contacts with name and phone number
* Display all saved contacts
* Search contacts by name
* Update existing contact details
* Delete contacts from the system
* Persistent storage using text files
* Exception handling for file operations

## Technologies Used

* Java
* File Handling (FileReader, FileWriter, BufferedReader, BufferedWriter)
* Collections Framework (ArrayList)
* Exception Handling
* Object-Oriented Programming (OOP)

## Project Structure

```text
Contact-Managment-System/
│
├── ContactManager.java
├── contacts.txt
└── README.md
```

## How It Works

The system stores contact information in a text file and provides a menu-driven interface for performing CRUD operations:

1. Add Contact
2. Display Contacts
3. Search Contact
4. Update Contact
5. Delete Contact
6. Exit

All contact records are saved in the following format:

```text
Name: John Doe and Phone: 9876543210
```

## How to Run

### Compile

```bash
javac ContactManager.java
```

### Execute

```bash
java ContactManager
```

## Learning Outcomes

* File handling in Java
* Exception handling using custom exceptions
* Data management using ArrayList
* Menu-driven application development
* CRUD operation implementation
* Object-Oriented Programming concepts

## Future Enhancements

* Graphical User Interface (GUI)
* Contact categorization
* Email field support
* Database integration (MySQL/MongoDB)
* Import and export functionality
* Contact validation and duplicate detection

## Author

**Dev Patel**
