# FAT32 File System Utility
This project involves creating a shell-like utility to interpret and manipulate a FAT32 file system image, supporting commands for file operations while maintaining system integrity. It emphasizes modular code design, robust error handling, and practical experience with FAT32's functionality.

## Group Members
- Rachel Andris: raa20cc@fsu.edu
- Elizabeth Sauer: es20fk@fsu.edu
- Isabella Perez: iep21@fsu.edu
## Division of Labor

### Part 1: Mounting the Image
- **Responsibilities**: Mount a FAT32 image file through command line arguments, parsing its structure, and starting a shell interface for user commands. Displaying boot sector details with info and safely closing the program using exit.
- **Assigned to**: Elizabeth Sauer

### Part 2: Navigation
- **Responsibilities**: Implements navigation commands for a FAT32 shell. The cd command changes the current directory while maintaining its state, and the ls command lists the names of files and directories in the current directory, including "." and "..", with error handling for invalid directories.
- **Assigned to**: Elizabeth Sauer

### Part 3: Create
- **Responsibilities**: Adds creation functionality to the FAT32 shell. The mkdir command creates a new directory, the creat command creates an empty file in the current directory.
- **Assigned to**: Elizabeth Sauer

### Part 4: Read
- **Responsibilities**: Adds file operations to the shell, including opening files with specific modes, closing them, listing open files, retrieving file size, adjusting file offsets, and reading file data. It manages a data structure for open files and includes error handling for invalid operations.
- **Assigned to**: Rachel Andris, Isabella Perez

### Part 5: Update
- **Responsibilities**: Enables file and directory updates in the shell. The write command writes a string to a file, extending its size if needed, while updating the file's offset. The rename command renames files or directories, with error handling for invalid operations or conflicts.
- **Assigned to**: Rachel Andris, Isabella Perez

### Part 6: Delete
- **Responsibilities**: Adds delete functionality to the shell. The rm command removes a file and its data, while rmdir deletes empty directories, ensuring proper cleanup and error handling for invalid or restricted operations.
- **Assigned to**: Rachel Andris

### Extra Credit
- **Responsibilities**: Dump command generates a hex dump of a directory or file, displaying its contents in hexadecimal format for inspection.
- **Assigned to**: Rachel Andris

## File Listing
```
root/
│
├── src/
│ └── filesys.c
├── README.md
└── Makefile
```
## How to Compile & Execute

### Requirements
- **Compiler**: e.g., `gcc` for C/C++, `rustc` for Rust.
- **Dependencies**: List any libraries or frameworks necessary (rust only).

### Compilation
For a C/C++ example:
```bash
make
```
This will build the executable in ...
### Execution
```bash
make run
```
This will run the program ...

## Bugs
- **Bug 1**: This is bug 1.
- **Bug 2**: This is bug 2.
- **Bug 3**: This is bug 3.

## Extra Credit
- **Extra Credit 1**: [Extra Credit Option]
- **Extra Credit 2**: [Extra Credit Option]
- **Extra Credit 3**: [Extra Credit Option]

## Considerations
[Description]
