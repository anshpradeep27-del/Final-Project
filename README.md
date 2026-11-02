# Final-Project
# Local Code Snippet & Boilerplate Vault

## Project Goal
A lightweight Java command-line interface (CLI) application designed to help developers quickly save, organize, and retrieve reusable code snippets and boilerplate code locally without complex setup or external tools.

## MVP Scope
- **Save Snippets:** Create new entries with a title, descriptive tags, and code blocks.
- **Search & Filter:** Instantly locate saved code by keyword or specific tag.
- **List All:** View all stored snippets in a structured format.
- **Local Persistence:** Read from and write to a local `snippets.txt` storage file.

## Tech Stack
- **Language:** Java (Standard JDK)
- **Libraries/Tools:** `java.util.Scanner`, `java.io.BufferedReader`, `java.io.BufferedWriter`, `java.io.File`
- **Data Storage:** Local plain text file (`snippets.txt`) using custom delimiter formatting
- **External Data Sources:** None (fully local execution)

## Future Plans (Schedule Quadrant)
- Edit and update existing saved snippets.
- Delete outdated code snippets.
- Export snippets into dedicated source files (`.java`, `.py`, `.txt`).
- Syntax highlight styling preview in terminal output.

## Folder Structure
- `src/` - Standard Java source code files
- `docs/` - Project documentation, Eisenhower Matrix, and System Diagram
- `snippets.txt` - Local storage file for code snippets
