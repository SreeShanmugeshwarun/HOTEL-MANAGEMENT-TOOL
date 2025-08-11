Hotel Management Tool

This is a comprehensive Hotel Management application designed to handle various operations such as storing customer information, booking rooms of four distinct types, placing food orders for specific rooms, cancelling room bookings, and generating bills. The system also allows users to view different room features and check room availability.

It is a menu-driven program that continues running until the user chooses to exit. File handling is used to store the hotel’s current state (customer details, booked rooms, and food orders) when the program ends, ensuring that previous data is preserved when the program is restarted. Upon startup, the application reads this file to restore the hotel’s prior status.

File writing is executed in a separate thread, enabling it to run in parallel without interrupting other operations. If a user attempts to book a room that is already allocated, a custom (user-defined) exception is raised. Robust exception handling is implemented to address any unexpected errors gracefully.

Topics Covered – Object-Oriented Concepts (Classes and Objects), Inheritance, File Handling with Objects, ArrayList Usage, Implementing Interfaces, Custom Exceptions, and Exception Management.
