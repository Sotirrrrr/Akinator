# Akinator
This project represents my own implementation of the popular game Akinator, developed together with one of my classmates. The application is entirely console-based and is written in C#, using a Tree data structure for storing and processing knowledge.

Idea and implementation:
The game asks a sequence of questions to which the user answers “yes” or “no”. Through these answers, the system gradually narrows down the possible options until it attempts to guess the thought-of object.
If it fails to guess it, the program asks the user to enter a new question that would differentiate the new object from the already known ones. In this way, the application “learns” with each new game — a primitive form of machine learning is implemented, where the tree expands dynamically based on player interaction.

Technologies and concepts:

Language: C#

Application type: Console Application

Main data structure: Tree (Binary Tree)

Main logic: Interactive learning through user input

Storage and expansion of knowledge during gameplay

Result:
The project demonstrates an understanding of basic algorithmic principles, working with tree-based data structures, and implementing self-learning logic in a gaming context.
