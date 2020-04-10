# Adroit-Scheduler
----------------------------------------------------------------------------------------------------------------------------
### An intelligent timetable generator that generates University timetable using `Genetic Algorithm`.

  A wrorking version of the prototype:- ['Adroit Scheduler'](http://abhik.pythonanywhere.com/)
  
 #### Dependencies:
 1. python3.6 or above
 2. Django2.0 or above
 
#### Run on your local machine by:
* `git clone https://github.com/Adroit-Abhik/Adroit-Scheduler/`
* `cd M1`
* `python manage.py runserver`
* then go to port `http://127.0.0.1:8000/timetable_generation/` to run the local server

#### About the project:
project uses genetic algorithm to satisfy the constraints related to Timetable scheduling. The program satisfies the following constraints:- 

| Hard Constraints                                  | Soft Constraints                                     |
| --------------------------------------------------|:----------------------------------------------------:|
| Unique class timing                               | classes are alloted according to section requirements|
| Course.students <= room.seating capacity          | All courses are according to their department        |
| Two classes dont have same room                   | Even distribution of course in a section per week    |
| Class timing for each teacher is unique           |
| Teachers are allocated to their course accordingly|

#### For any queries or to commit any changes, contact:
['Abhik Mitra'](mitraabhik2212@gmail.com)
