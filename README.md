# Simple Line Editor in C

## Project Description

A simple command-line line editor developed in C.

The editor works with a document one line at a time and provides
commands for inserting, deleting, and displaying lines.

## Data Structure

The project uses an **array of strings** to store the document.

- Maximum lines: 100
- Maximum characters per line: 200

### Why an Array of Strings?

An array of strings provides a simple and direct way to store and
access individual lines. It also makes the insert, delete, and
display operations straightforward to implement.

## Implemented Features

1. Insert a line
2. Delete a line
3. Display the document

## Supported Commands

| Command | Description |
|---|---|
| `insert` | Insert a new line |
| `delete` | Delete an existing line |
| `display` | Display all lines |
| `quit` | Exit the editor |

## Compilation and Execution

Compile using GCC:

```bash
gcc line_editor.c -o line_editor
```

Run the program:

```bash
./line_editor
```

## Team Members

- Rakesh

## Work Completed

- Designed the data structure and command structure.
- Implemented the insert operation.
- Implemented the delete operation.
- Implemented the display operation.
- Tested empty document and line insertion/deletion cases.
- Created HELP.md with command documentation.

## Learning Outcome

This project provided practical experience with arrays of strings,
functions, input handling, string manipulation, and command-line
program design in C.