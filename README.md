# Timetable Scheduler
----------------------------------------------------------------------------------------------------------------------------
### An intelligent timetable generator that generates University timetable using `Genetic Algorithm`.

#### Dependencies:
 1. python 3.6 or above
 2. Django 2.0 or above

#### About the project:
Project uses genetic algorithm to satisfy the constraints related to Timetable scheduling. The program satisfies the following constraints:-

| Hard Constraints                                  | Soft Constraints                                     |
| --------------------------------------------------|:----------------------------------------------------:|
| Unique class timing                               | classes are alloted according to section requirements|
| Course.students <= room.seating capacity          | All courses are according to their department        |
| Two classes dont have same room                   | Even distribution of course in a section per week    |
| Class timing for each teacher is unique           |
| Teachers are allocated to their course accordingly|


