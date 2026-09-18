# Smart-Parking-Management-System

## About the Project

The **Smart Parking Management System** is a simple Java-based project made to manage vehicles in a parking area.

The main idea of this project is to keep track of which parking slots are free or occupied and make the parking process easier. When a vehicle enters, the system assigns it a parking slot and records the entry time. When the vehicle leaves, the system calculates the parking fee and makes the slot available again.

This project is mainly created to understand how Java concepts can be used in a real-world type of application.

---

## Features

The system provides the following features:

* View available parking slots
* Register a vehicle when it enters
* Assign an available parking slot
* Store vehicle and parking details
* Record vehicle exit
* Calculate parking fees according to parking time
* Make the parking slot available after the vehicle leaves
* Handle invalid inputs and basic errors

---

## How the System Works

The basic working of the project is:

1. The user starts the program.
2. Available parking slots are displayed through the menu.
3. When a vehicle enters, its vehicle number and type are entered.
4. The system checks for an available slot.
5. An available slot is assigned to the vehicle.
6. The entry time is stored.
7. When the vehicle leaves, the user enters the vehicle number.
8. The system finds the vehicle's parking record.
9. Entry and exit time are used to calculate the parking duration.
10. The parking fee is calculated.
11. The vehicle record is removed and the parking slot becomes available again.

---

## Java Concepts Used

This project uses some basic and important Java concepts:

### OOP

Different classes can be used to represent different parts of the system, such as:

* `Vehicle`
* `ParkingSlot`
* `ParkingTicket`
* `ParkingManager`
* `Main`

This helps in keeping the code organized and makes the project easier to manage.

### Collections

Collections like `ArrayList` and `HashMap` can be used to store parking slots and vehicle records.

For example:

```java
ArrayList<ParkingSlot> parkingSlots;
HashMap<String, ParkingTicket> parkedVehicles;
```

### Date and Time

Java's `LocalDateTime` is used to keep track of when a vehicle enters and exits.

```java
LocalDateTime entryTime = LocalDateTime.now();
```

### Loops and Conditions

Loops are used for displaying slots and processing the menu, while `if-else` conditions are used for checking slot availability and vehicle records.

### Exception Handling

`try-catch` is used to prevent the program from crashing when the user enters something incorrectly.

---

## Example

Suppose a parking area has 10 slots.

If a car enters and slot `A-03` is free, the system assigns:

```text
Vehicle Number : MP04AB1234
Vehicle Type   : Car
Parking Slot   : A-03
Entry Time     : 01:30 PM
```

When the car leaves after 3 hours:

```text
Duration       : 3 Hours
Parking Fee    : ₹90
```

After the vehicle exits, slot `A-03` becomes available again.

---

## Sample Menu

```text
   SMART PARKING SYSTEM

1. Show Available Slots
2. Register Vehicle Entry
3. Vehicle Exit
4. Show Parked Vehicles
5. Exit

Enter your choice:
```

---

## Project Structure

```text
Smart-Parking-Management-System
│
├── Main.java
├── Vehicle.java
├── ParkingSlot.java
├── ParkingTicket.java
├── ParkingManager.java
│
└── README.md
```

---

## Objective

The main objective of this project is to create a small parking management system while practicing Java programming.

Through this project, we can understand how concepts like **OOP, collections, loops, exception handling and date/time** work together in an actual application.

---

## Future Improvements

Some things that can be added later are:

* Login system for admin
* Different parking charges for bikes and cars
* GUI using Java Swing or JavaFX
* Database connectivity using MySQL
* Online/digital payment option
* Parking history
* Daily revenue report
* Multiple parking floors

---

## Technologies Used

* **Language:** Java
* **Type:** Console-based application
* **Concepts:** OOP, Collections, Loops, Date & Time, Exception Handling

---

## Conclusion

The Smart Parking Management System is a simple project, but it gives a good idea of how Java can be used to solve a practical problem. It also helps in understanding how different Java concepts can be combined to build a complete working application.
