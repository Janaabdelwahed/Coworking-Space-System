# Coworking-Space-System
a coworking space system with OOP in java


Title : Coworking space System

Description : This project manages a system for coworking space
Your system has 2 types of users: visitor, admin
It contains different types of meeting rooms


**THE DESCRIPTION:**

The system has 3 types of rooms: General room

Meeting room and Teaching room. It has 2 General rooms, 3
Meeting rooms and 3 teaching rooms.
Your visitor is one of 3 types: general, formal, instructor
The system has one admin. The admin manages all entities.
A visitor can login to the system using name and password (check
if it is the first time to use the system, ask to register and take the
rest of needed information to make an account)
The admin can login using name: “admin” and password: “admin”
A visitor has: name, password, ID, Type
A visitor can:
● Register
● Log in
● Make reservation: reserve one slot or more, let him choose
from a list of slots (as long as these slots are available and
in the current month of reservation)
Hint: Let the visitor choose from room slots that goes with the
visitor type
General visitor: general room slot

Formal visitor: meeting room slot
Instructor visitor: teaching room slot
● Cancel reservation: delete reservation and free the slot
● Update reservation: update reservation time or update
reservation date. make all the checkups you need to make
sure the update is valid.
● Display available slots: display times and dates

General room has: name, ID, number_of_visitors (max of 20), list
of slots, list of visitors
Meeting room has: name, ID, number_of_visitors (max of 10), list
of slots, list of visitors
Teaching room has: name, ID, projector_type, board_type,
instructor_name, number_of_visitors (max of 10), list of slots, list
of visitors
A slot has time, date and fees
The admin has: name, password
The admin can:
● Log in
● Add slots
● Delete any entity
● Display all available slots for all rooms (room type + room ID
+ slot details <date and time>)
● Display all visitor’s data
● Display all rooms’ data
● Display all instructor’s data
● Calculate and display the total amount of money from
general room reservation
● Calculate and display the total amount of money from
meeting room reservation
● Calculate and display the total amount of money from
teaching room reservation
● Update any data of any entity
