# Dynamic Time Table Generation

Making a class schedule is one of those NP hard problems. The problem can be solved using a heuristic search algorithm to find the optimal solution, but it only works for simple cases. For more complex inputs and requirements, finding a considerably good solution can take a while, or it may be impossible. This is where genetic algorithms come in to the game.

When you make a class schedule, you must take into consideration many requirements (number of professors, students, classes and classrooms, size of classroom, laboratory equipment in classroom, and many others). These requirements can be divided into several groups by their importance. 

Hard requirements (if you break one of these, then the schedule is infeasible):
-------------------------------------------------------------------------------------
A class can be placed only in a spare classroom.
No professor or student group can have more then one class at a time.
A classroom must have enough seats to accommodate all students.
To place a class in a classroom, the classroom must have laboratory equipment (computers, in our case) if the class requires it.

Some soft requirements (can be broken, but the schedule is still feasible):
-------------------------------------------------------------------------------------
Preferred time of class by professors.
Preferred classroom by professors.
Distribution (in time or space) of classes for student groups or professors
.

dynamicTimeTable
================

This is a simple implementation of Time Table Generation

Instructions to use this project : 

This project is configured in eclipse and is a simple implementation.

1) Clone this repository.	
	
2) Import the project in Eclipse ( you can even copy the package into a new project if you use a different IDE / If import of Eclipse project doesnt work well with that IDE )

3) Set up your requirements in the ```'Initialization.java'``` class, which is very self explanatory 
	
4) Run the ```'TimeTableMain.java'``` file and you will see a ```'timetable.csv'``` file created in the Project Directory


Good Luck !
