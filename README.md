
This C++ code, part of the CS221 course at Ghulam Ishaq Khan Institute of Engineering Sciences and Technology (GIKI), implements a simulation system for event management. 
Developed by:
-Abdullah Shabbir
-Usama Sadiq
-Syed Faiq Haider Naqvi
under the instruction of Usama Arshad, the program utilizes linked lists (queue) and an AVL tree for efficient scheduling and processing of events.

Code Overview:

Event Types and Events:

Classes for "EventType" and "Event" store predefined event types and individual event details.
Events are timestamped and categorized into types.
Event Queue:

A linked list-based event queue manages event order.
Events enqueue and dequeue based on scheduled time.
AVL Tree:

An AVL tree optimizes event scheduling by ensuring a balanced structure.
Efficient insertion and deletion operations maintain tree balance.
Simulation System:

The SimulationSystem class integrates the event queue and AVL tree for overall simulation management.
Methods include adding events, processing the next event, and displaying the simulation state.
User Interaction:

Main function provides a user interface for adding events, processing events, displaying the simulation state, or exiting.
Menu-driven Interface:

The program offers a menu-driven interface for user interaction.
File Input:

Event types load from a file ("event_types.txt") during initialization.
Key Functionality:

Events added insert into both the event queue and AVL tree.
Processing the next event simulates execution by removal from the queue and AVL tree.
DisplaySimulationState shows the current state, including the event queue and AVL tree traversal.
Note:

The code demonstrates practical use of data structures for event management.
Timestamps order events in both the queue and AVL tree.
Predefined event types load from a file, enhancing flexibility.
This foundational structure for a simulation system showcases the application of data structures and algorithms in event management.
