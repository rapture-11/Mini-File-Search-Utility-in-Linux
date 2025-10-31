🗂️ Mini File Search Utility

A simple Linux-based Bash tool to search files by name, extension, or size.

📖 Overview

The Mini File Search Utility is a terminal-based script built in Bash that helps users locate files quickly and efficiently.
It supports multiple search criteria — making it a lightweight alternative to GUI-based search tools.
This script is perfect for students, system administrators, or Linux enthusiasts who want to understand shell scripting, file handling, and automation.

✨ Features

🔍 Search by File Name: Finds files containing specific keywords.

📄 Search by File Extension: Lists all files with a chosen extension (e.g., .txt, .sh, .cpp).

📏 Search by File Size: Filters files between minimum and maximum sizes.

📁 Recursive Directory Traversal: Automatically searches through all subdirectories.

⚙️ No External Dependencies: Works on any Linux system with bash and find.

🧩 Clear Console Output: Displays full file paths and file sizes.

⚙️ How It Works

The script takes a directory path as input.

You select a search mode:

name → search files containing a keyword

extension → search by file type

size → search by file size range

It uses the find command with filters to locate matching files.

Results are displayed with absolute paths and file sizes.

🧠 Concepts Demonstrated

Shell scripting basics (if, case, functions)

File system traversal with find

String and pattern matching in Bash

User input handling

Output formatting with printf

🛠️ Installation & Usage
Requirements

Linux / macOS terminal

Bash version 4+

👨‍💻 Author

Rushil Agnihotri
Student | Developer | Linux Enthusiast
