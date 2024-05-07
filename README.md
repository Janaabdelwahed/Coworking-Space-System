# Coworking-Space-System
A coworking space system with OOP in java


Title : Coworking space System

Description : This project manages a system for coworking space
Your system has 2 types of users: visitor, admin
It contains different types of meeting rooms


**THE DESCRIPTION:**

The system has 3 types of rooms: General room

Meeting room and Teaching room. It has 2 General rooms, 3
Meeting rooms and 3 teaching rooms. <br/>
Your visitor is one of 3 types: general, formal, instructor <br/>
The system has one admin. The admin manages all entities. <br/>

A visitor can login to the system using name and password (check
if it is the first time to use the system, ask to register and take the
rest of needed information to make an account) <br/>
 
The admin can login using name: “admin” and password: “admin”

A visitor has: name, password, ID, Type <br/>

A visitor can: <br/>
● Register <br/>
● Log in <br/>
● Make reservation: reserve one slot or more, let him choose
from a list of slots (as long as these slots are available and
in the current month of reservation) <br/>


the visitor chooses from room slots that goes with the
visitor type <br/> 


General visitor: general room slot
<br/>
Formal visitor: meeting room slot <br/>
Instructor visitor: teaching room slot <br/>

● Cancel reservation: delete reservation and free the slot <br/>

● Update reservation: update reservation time or update <br/>

reservation date. make all the checkups you need to make
sure the update is valid. <br/>

● Display available slots: display times and dates <br/>

General room has: name, ID, number_of_visitors (max of 20), list
of slots, list of visitors <br/>

Meeting room has: name, ID, number_of_visitors (max of 10), list
of slots, list of visitors <br/>

Teaching room has: name, ID, projector_type, board_type, <br/>

instructor_name, number_of_visitors (max of 10), list of slots, list
of visitors <br/>

A slot has time, date and fees <br/>

The admin has: name, password <br/>

The admin can: <br/>
● Log in <br/>
● Add slots <br/>
● Delete any entity <br/>
● Display all available slots for all rooms (room type + room ID <br/>
+ slot details <date and time>) <br/>
● Display all visitor’s data <br/>
● Display all rooms’ data <br/>
● Display all instructor’s data <br/>
● Calculate and display the total amount of money from 
general room reservation <br/>
● Calculate and display the total amount of money from
meeting room reservation <br/>
● Calculate and display the total amount of money from
teaching room reservation <br/>
● Update any data of any entity
