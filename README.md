# ObjectOrientedProgramming
This project is a Python implementation of a simple car rental system, which involves various types of vehicles (Vehicle, Car, Truck), a Garage to park these vehicles,
and a Customer class to represent customer details. The GarageTester class demonstrates how to park a vehicle in a garage and prints the details of the parked vehicle.

#Features of Object-Oriented Programming (OOP)
1. Encapsulation:
Data and methods (e.g., color, has_winter_tires, get_color()) are encapsulated within classes like Vehicle, Car, and Truck.
2. Inheritance:
Car and Truck inherit from Vehicle, reusing the base class's functionality while adding their own attributes (e.g., has_trailer).
3. Polymorphism:
Car and Truck override the __str__() method from Vehicle. The Garage class can handle any vehicle object.
4. Abstraction:
Users interact with methods like set_vehicle() and __str__() without needing to understand the internal implementation of classes.

#Project Structure
vehicle.py: Base Vehicle class.
car.py: Extends Vehicle with has_winter_tires.
truck.py: Extends Vehicle with has_trailer.
garage.py: Handles parking vehicles.
garage_tester.py: Demonstrates parking a truck.
customer.py: Stores customer detail

#Expected Output:
Description of the parked vehicle...
This vehicle is black
Has trailer: False
