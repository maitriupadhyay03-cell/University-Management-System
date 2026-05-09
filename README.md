# University Management System

This is a Java assignment I did where I built a terminal-based university management system. It's a multi-file Java project with no GUI — everything runs in the terminal and displays in a tabular format to keep things readable.

## How it works

When you start the program, you log in as one of four roles: Student, Teacher, Admin, or Teaching Assistant. Depending on who you log in as, you get access to different options and features. You can log out and switch between roles.

There's no data persistence — once you close the program everything resets. It's purely session-based, which kept things simpler to implement.

## What each role can do

Each role has its own set of actions. Things like enrolling in courses, viewing grades, assigning grades, managing students, and handling course-related tasks are all part of the system depending on which role you're logged in as. There are quite a lot of options across the different roles.

## How to run

Make sure you have Java installed. Then compile all the .java files and run the main class:

javac *.java
java Main

(Replace Main with whatever the actual main class is named in the project)

## Notes

This was a Java assignment so the focus was more on the logic and structure than on making it look fancy. Everything is displayed in a clean tabular format in the terminal. The project has multiple Java files, each handling different parts of the system.
