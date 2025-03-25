Observer Pattern & Event Management System Welcome to My Lab 3 Project! This repository contains implementations of: *Observer Pattern – Demonstrating how observers react to state changes dynamically. *Event Management System – Handling SMS notifications using the Observer Pattern.

Table of Contents:

*Observer Pattern: 📌 First, watch the ObserverPattern video before running the code.

The Observer Pattern is used to notify multiple objects (observers) when the state of a subject changes.

We implement an Observer interface and different observer types (Binary, Octal, Hexa).

Key Features: attach() to subscribe an observer. detach() to remove an observer. notifyAllObservers() to update all active observers.

*Event Management System (SMS Support) 📌 After the Observer Pattern video, watch the EventManagement video for SMS notifications.

This system extends the Observer Pattern for real-world event handling (e.g., file uploads).

EventManager manages multiple event listeners.

SMSSupportListener sends an SMS when a file upload event occurs.

The listener checks if the message exceeds 160 characters before sending.