# task4
# 📝 NoteApp

A simple **Java console application** that allows you to **write and read notes** from a text file (`notes.txt`).  
This project demonstrates basic **file handling** in Java using `FileWriter` and `BufferedReader`.

## 🚀 Features
- **Write Notes** → Add new notes to a file.
- **Read Notes** → Display all previously saved notes.
- **Persistent Storage** → Notes are saved in `notes.txt` so they remain even after restarting the program.
- **Menu-Driven Interface** for easy navigation.

**Example Output**

1. Write note
2. Read notes
3. Exit
Enter your choice: 1
Enter your note: This is my first note.
Note written successfully!

1. Write note
2. Read notes
3. Exit
Enter your choice: 2
Notes:
This is my first note.
This is my first note.

**How It Works**

Writing Notes → The note is appended to notes.txt using FileWriter.

Reading Notes → Reads each line from notes.txt using BufferedReader.

Exit → Ends the application without deleting notes.
