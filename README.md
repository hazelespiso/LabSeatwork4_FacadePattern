# Lab Seatwork 4 FacadePattern
# Simplified Intelligent Home System

The HomeApp needs to manage various home services for an intelligent home system. These services include turning on and off the lights, TV, and air conditioning. However, the HomeApp aims to interact with these services through a simplified, single interface provided by the HomeInterface. The HomeInterface class should delegate the user’s requests to the appropriate service classes (Light, TV, AirConditioning) while abstracting the service details from the user. Additionally, the HomeInterface should provide methods to turn on all services (turnOnAll()) and turn off all services (turnOffAll()).

## Class Definitions:

* **`HomeService` (Interface):** Defines the common interface for all home services.
* **`Light`:** A service class implementing the `HomeService` interface, responsible for turning the lights on and off (`turnOn()` and `turnOff()`).
* **`TV`:** A service class implementing the `HomeService` interface, responsible for turning the TV on and off (`turnOn()` and `turnOff()`).
* **`AirConditioning`:** A service class implementing the `HomeService` interface, responsible for turning the air conditioning on and off (`turnOn()` and `turnOff()`).
* **`HomeInterface`:** The facade class that coordinates interactions between the client and individual home services. It includes `turnOnAll()` and `turnOffAll()` methods to control all services at once.
* **`HomeApp`:** The client class that uses the `HomeInterface` to access and utilize home services seamlessly.

In your solution you must provide the following in your Github link account:

  Problem statement (description of the problem. Just copy what is stated here.
  Uploaded java codes for the solution.
