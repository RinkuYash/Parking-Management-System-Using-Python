Overview of the Project
Project Name: Vehicle Parking Management System

Description: The project is a command-line-based Python application designed to manage a parking facility. It allows for the entry, removal, and viewing of vehicles within a parking area. The system also provides details about available parking spaces and calculates the billing for parked vehicles.

Key Features:

Vehicle Entry: Allows new vehicle entries into the parking system, capturing details such as vehicle number, type (e.g., Bike, Car, Bicycle), vehicle name, owner name, and the time of entry.
Remove Entry: Removes a vehicle entry from the parking system, likely when the vehicle exits the parking facility.
View Parked Vehicles: Displays a list of all currently parked vehicles with their details.
View Available Parking Spaces: Shows the number of available parking spots for different vehicle types (bikes, cars, bicycles).
Amount Details: Calculates and displays the parking fee based on the duration of parking.
Billing: Generates a bill for the parked vehicles based on their type and parking duration.
Exit: An option to close the program.
Data Management:

The system uses lists to manage details of vehicles, including vehicle numbers, types, names, owner names, and the date and time of entry.
There are predefined slots for different types of vehicles (e.g., bikes, cars, bicycles).
Code Structure:

The script begins by importing necessary libraries, such as time, for managing date and time functions.
Global variables are used to track the number of available parking slots for each type of vehicle (bikes, cars, bicycles).
The main function (main()) contains a while loop that continuously prompts the user to choose an option from the parking management menu.
Depending on the user’s input, different functions or logic blocks are executed to perform the desired actions (e.g., adding a vehicle entry, removing an entry, etc.).
