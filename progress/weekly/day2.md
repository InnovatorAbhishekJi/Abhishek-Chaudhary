Day 2 — Linux Files & Directories

Goal

Learn how to create, read, copy, move, rename, and delete files and directories using the Linux terminal.

Environment

- Windows 10
- WSL 2
- Ubuntu
- Linux User: abhishek

Commands Practiced

mkdir

Creates a new directory.

mkdir directory-name

touch

Creates an empty file.

touch file.txt

cat

Displays the contents of a file.

cat file.txt

cp

Copies files or directories.

cp source.txt destination/

mv

Moves or renames files and directories.

mv old-name.txt new-name.txt

rm

Removes files.

rm file.txt

Redirection

Practiced writing command output into a file using ">".

echo "Linux is the foundation of my engineering journey." > notes.txt

The content was then verified using:

cat notes.txt

Practical Lab

Created and manipulated files and directories inside:

/home/abhishek/engineering-lab

Created a project structure:

engineering-lab/
└── project/
    ├── README.md
    ├── src/
    │   └── main.cpp
    ├── docs/
    │   └── notes.txt
    └── backup/
        └── main-backup.cpp

Key Learning

Linux treats files and directories as fundamental building blocks of the filesystem.

The important mental model from this lab:

mkdir → create directory
touch → create file
cat   → read file
cp    → copy
mv    → move / rename
rm    → delete

I also learned that "mv" is used for both moving and renaming files.

Engineering Lesson

Instead of memorizing commands individually, understand what operation is happening:

Create → Read → Copy → Move → Rename → Delete

This makes terminal usage easier to understand and apply in real systems.

Status

Day 2 completed successfully.

Next Step

Move beyond basic filesystem operations and learn Linux tools for:

- Searching files
- Searching text
- Filtering command output
- File permissions
- Pipes and redirection