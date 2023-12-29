This C++ code implements a simulation system for managing events using a combination of a linked list (queue) and an AVL tree. The program allows users to add events, process upcoming events, and display the current state of the simulation.

Course Information:

Course Code: CS221
University: Ghulam Ishaq Khan Institute of Engineering Sciences and Technology (GIKI)
Instructor: Usama Arshad
Group Members: Abdullah Shabbir, Usama Sadiq, Syed Faiq Haider Naqvi
Code Overview:

Event Types and Events:

The program defines classes for "EventType" and "Event," where EventType represents predefined event types, and Event represents individual events with various details.
Events are timestamped and categorized into types.
Event Queue:

A linked list-based event queue is implemented for managing the order of events.
Events are enqueued and dequeued based on their scheduled time.
AVL Tree:

An AVL tree is used to efficiently manage events ordered by timestamp.
The tree ensures balanced insertion and deletion operations for optimized event scheduling.
Simulation System:

The SimulationSystem class integrates the event queue and AVL tree to manage the overall simulation.
It includes methods for adding events, processing the next event, and displaying the simulation state.
User Interaction:

The main function provides a user interface for interacting with the simulation.
Users can add events, process the next event, display the simulation state, or exit the program.
Menu-driven Interface:

The main loop allows users to choose options from a menu, including adding events, processing events, and viewing the simulation state.
File Input:

Event types are loaded from a file ("event_types.txt") during initialization.
Key Functionality:

Adding events ensures proper insertion into both the event queue and the AVL tree.
Processing the next event removes it from the queue and AVL tree, simulating event execution.
The displaySimulationState function showcases the current state of the simulation, including the event queue and the in-order traversal of the AVL tree.
Note:

The code demonstrates a practical implementation of data structures (linked list and AVL tree) for managing events efficiently.
Timestamps are used for ordering events in both the queue and the AVL tree.
The program allows for predefined event types loaded from a file.
This code serves as a foundational structure for a simulation system, showcasing the application of data structures and algorithms in event management.
