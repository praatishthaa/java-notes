# Java Notes App

A simple command-line based Notes Manager application built using Java. This project utilizes `FileWriter` and `BufferedReader` to implement persistent data storage for user-generated notes. The goal of this project is to demonstrate basic file I/O operations in Java and handle exceptions gracefully using best practices.

## Features

- Add new notes via terminal input
- View all previously saved notes
- Notes are stored in a persistent file (`notes.txt`)
- Handles missing files and I/O exceptions with user-friendly messages

## Technologies Used

- Java (JDK 8+)
- VS Code / Terminal
- File I/O (`FileWriter`, `FileReader`, `BufferedReader`)
- Exception handling (`IOException`, `FileNotFoundException`, etc.)

## How It Works

The application follows a simple interactive menu pattern. The user is prompted with options to add a note, view notes, or exit. When a note is added, it is written to `notes.txt` using `FileWriter` in append mode. When the user chooses to view notes, the application reads the content of the file using `BufferedReader` and displays each line as an individual note.

## Usage Instructions

1. Clone this repository or download the `NotesApp.java` file.
2. Open the project in any Java IDE or run it using terminal.
3. Compile the program:javac NotesApp.java
4. Run the application: java NotesApp
5. Follow the on-screen prompts to interact with the app.

## Concepts Demonstrated

- File reading and writing in Java
- Append vs overwrite modes in file writing
- Using `try-with-resources` to automatically manage stream closures
- Exception handling for robust file operations
- Command-line based interaction and scanner usage
