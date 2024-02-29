# Elevators Game Design AI
Language: C++

## Overview
This project is a simulation game developed in C++ that challenges players to manage a set of elevators within a virtual building. The goal is to efficiently transport people to their desired floors, optimizing for speed and minimizing wait times, which are creatively measured in anger levels. This game employs object-oriented programming principles to model the intricate dynamics of elevator movement and human behavior within a building environment.

## Note
Due to university policy, I cannot share the assignment-specific file, though it is available for viewing upon request. 

## Key Features
Object-Oriented Design: Leveraging C++ to implement a robust system of classes representing different aspects of the game, including people, elevators, floors, and more.
AI-Driven Elevator Management: An AI framework that analyzes player inputs and incoming events to optimize elevator operations, balancing speed and passenger satisfaction.
Dynamic Gameplay: Players receive continuous streams of information about future events and must strategize elevator movements in real-time.
Visual Feedback: Users can visualize the current state of the building, making informed decisions to manage the elevator fleet effectively.

## Classes Overview
Person: Represents individuals within the building, each with unique destination floors and anger levels.
Elevator: Models the elevators' operational dynamics, including movement, current floor, and occupancy.
Floor: Represents the floors within the building, serving as the origin and destination for persons.
Move: Encapsulates the actions of elevators, including ascending, descending, and stopping.
Building: The environment in which the elevators operate, containing floors, elevators, and people.
Game: Acts as the central engine, coordinating the flow of the game, processing user inputs, and displaying the state of the building.
SatisfactionIndex: A metric to evaluate the efficiency of elevator operations based on the minimization of wait times and the optimization of passenger delivery.
AI.cpp: Contains the AI framework logic that guides the optimization strategies for elevator movements.

## Gameplay Mechanics
Input File (game.in): The game reads from a game.in file detailing all future events, such as the arrival of people and their desired floors.
User Commands: Players issue commands to control elevator movements, reacting to the dynamic changes within the building.
Real-Time Strategy: The game challenges players to think ahead, anticipate future events, and strategically manage elevators to ensure high satisfaction levels.

## AI Implementation
The AI framework within AI.cpp is designed to analyze both the current state of the building and the player's input to make decisions that optimize the operation of the elevators. It aims to reduce wait times by prioritizing moves that deliver the maximum number of people to their destinations efficiently while minimizing their anger levels.


