# Degrees - Six Degrees of Separation
The Degrees project is a Python program that determines the degrees of separation between two actors in the Hollywood film industry. It is based on the Six Degrees of Kevin Bacon game, where any actor can be connected to Kevin Bacon within six steps, by finding a film that both actors starred in.

The program is framed as a search problem, where the states are people and the actions are movies. The goal is to find the shortest path between two actors by choosing a sequence of movies that connects them. By using breadth-first search, the program can find the shortest path from one actor to another.

The program uses a large and a small dataset, each containing three CSV files. The CSV files organize data in a text-based format, where each row corresponds to one data entry, with commas separating the values for that entry.

The implementation of the shortest_path function is left unimplemented in the project, and the task is to complete the implementation to return the shortest path from the source to the target person.

To run the program, use the command:

`python degrees.py [large/small]`

where large or small specifies which dataset to use. The program will prompt the user to input two actor names, and will return the shortest path and the movies that connect them.

This project is a part of the CS50 AI curriculum, and the latest version of Python to be used in this course is Python 3.10.

Enjoy playing the Six Degrees of Separation game with the Degrees project!

Note: Since "Large" folder is too big, "Small" is the only available example for now. Feel free to test it on your own examples.
