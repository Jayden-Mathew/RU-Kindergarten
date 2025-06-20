# RU-Kindergarten

The purpose of this project was to implement a simulation of a kindergarten classroom using Java and fundamental data structures. The simulation involves three key classroom activities: students standing in line, students seated at their desks, and students playing a game of musical chairs. Each activity is modeled using a different data structure, reinforcing understanding of singly linked lists, 2D arrays, and circular linked lists.

The following objectives were implemented and demonstrated through this simulation:

 - Simulate a line of students using a Singly Linked List
 - Create a classroom seating chart using a 2D boolean array and seat students using a 2D Student array
 - Move students into a Circular Linked List to simulate a musical chairs game
 - Randomly eliminate students during the game and insert them back into the line alphabetically
 - Determine a winner from the game and seat them in the classroom

Java was the primary language used, with custom classes for student data and node structures. File I/O was managed using StdIn and StdOut, and randomness for the game was provided via the StdRandom utility.

Within the contents of this repository, you’ll find the core implementation (Classroom.java), supporting classes (Student.java, SNode.java), a driver for testing (Driver.java), and example input files containing student and seating data.

Key concepts reinforced:

 - Linked List insertion/removal
 - Circular linked list traversal
 - 2D array indexing and management
 - File parsing and simulation control
