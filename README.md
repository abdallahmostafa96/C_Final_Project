# C_Final_Project
Clinic Management System!
# Welcome to my Clinic Management System!

## Description

Admin mode has a default password of 1234, and can only accept 3 wrong password entries. After that, it will terminate.

Patients' records is loaded from patients_data.txt (if available) upon launch, and is auto saved after we add a new patient or edit or remove an existing one. So you don't have to add them every time you launch the system.

Reservation time slots are reset every time we launch the system, the system is intended to run once per day, so each day has his own reservation slots.



## Files

- **main.c:** Contains main code that will run upon execution.
- **type_def.h:** Contains data types used in the whole project.
- **func.c:** Contains functions used in the whole project.
- **func.h:** Contains declaration for functions used in the whole project.




## Main features:

### Program consists of two modes, and you can always log out to enter the other mode
###  Admin mode: 


- Add a new patient record
- Edit patient record
- Remove patient record
- Reserve a time slot with the doctor for an ID within available time slots
- Cancel a reservation 
- View all patients' records in a table
- Manually import data from patients_data.txt.
- Manually export data to patients_data.txt.

###  User mode: 
- View single patient record with his/her ID.
- View all reserved time slots with it's corresponding time and ID.

# Author
#### Abdallah Mostafa Abd El-Haq
#### Group ID:   0225112210
#### Student ID: 022511221018

# License
####  Made for IMT School for educational use only
####   All copyrights are reserved
