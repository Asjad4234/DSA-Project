Introduction
The Parcel Delivery Management System is designed to optimize the delivery process by efficiently managing parcels, courier trucks, and delivery personnel. 
The primary objective is to deliver parcels to customers in the shortest possible time while maintaining a record of deliveries and improving overall performance. 
This system incorporates various data structures such as linked lists, queues, binary trees, and stacks to organize and track parcel deliveries effectively.

Methodology

Courier Truck Management:
Utilizes a linked list to store courier trucks, allowing addition and deletion of trucks.
Trucks are sorted by unique identification numbers.
Upon receiving a parcel, trucks depart to deliver it to the assigned address.

Parcel Management:
Parcels are stored in a separate linked list.
Each parcel is assigned a unique identification number for tracking purposes.
Parcels include source and destination addresses.

Order Queue:
Incoming orders are maintained in a queue.
Orders are processed and removed from the queue upon delivery completion.

Delivery Time Tracking:
Utilizes a binary tree to track and store delivery times.
Enables management to analyze performance and improve delivery times.

Delivery Record Maintenance:
Addresses of delivered parcels are stored in a stack to maintain a record of deliveries.

Employee Management:
Maintains a linked list of employees with unique ID numbers and positions within the courier system.
Allows addition and deletion of employees.

Optimal Path Calculation:
Calculates the shortest or best possible path using shortest path algorithm/MST for delivery routes.
Guides truck drivers to follow the optimal path for efficiency.
