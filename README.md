# **Smart Parking System in Python**

**Name**: Sujal Ganngadhar Sahane  
**Contact**: sahanesujal@gmail.com  

## Project Overview

The Smart Parking System automates the management of parking spaces and calculates parking charges based on the duration of parking. This version of the system has been implemented in Python, using SQLite for database management.

### **Parking Slot Management:**
- Tracks parking slot availability and assigns vehicles to slots.
- Each parking slot has a status: available or occupied.
  
### **Vehicle Tracking:**
- Records vehicle entry and exit times.
- Tracks the type of vehicle (car or bike) for charge calculation.

### **Parking Charge Calculation:**
- Automatically calculates parking charges based on the duration of the vehicle's stay and the type of vehicle (car or bike).
- **Cars** are charged 10 units per hour, and **bikes** are charged 5 units per hour.

### **SQLite Database:**
- SQLite is used to store parking slot data and transaction details in the database (`smart_parking.db`).
- The database handles:
  - Parking slot availability (whether occupied or free).
  - Transaction records, including entry time, exit time, and charge calculations for each vehicle.

### **Key Features:**
- **Parking Slot Management**: Automates the tracking of available and occupied parking slots.
- **Real-Time Slot Availability**: Instantly updates the slot status when vehicles enter or exit.
- **Vehicle Tracking**: Records vehicle entry and exit times, along with vehicle type.
- **Dynamic Charge Calculation**: Calculates parking charges based on the vehicle's parking duration and type.
- **Optimized Space Usage**: Ensures maximum utilization of available parking spaces by allocating the first available slot.
- **Improved Operational Efficiency**: Reduces manual errors and streamlines parking operations by automating the process.

---

## **Main Objectives:**

### **Efficient Parking Slot Management:**
- Automates the tracking of available and occupied parking slots using SQLite, improving parking space management.

### **Real-Time Slot Availability:**
- Provides instant updates of slot availability by querying the SQLite database, allowing real-time tracking.

### **Vehicle Tracking:**
- Tracks the entry and exit times of vehicles, along with the type of vehicle (car or bike), enabling efficient tracking and accurate billing.

### **Dynamic Parking Charge Calculation:**
- Automatically calculates parking charges based on the vehicle type and parking duration, ensuring accurate and fair pricing.

### **Optimized Space Usage:**
- Allocates the first available slot to incoming vehicles, maximizing space usage and minimizing idle time.

### **Improved Operational Efficiency:**
- Automates parking operations, reducing the need for manual interventions and minimizing errors in the parking management process.

---

## **Technologies Used:**
- **Python**: The main programming language for implementing the logic.
- **SQLite**: A lightweight relational database used to store parking and transaction data.
- **Datetime**: Python's built-in library for handling entry and exit times.

---

## **Setup and Usage:**

### **Installation:**
1. **Python Version**: Ensure Python 3.x is installed on your system.
2. **SQLite Database**: The system uses SQLite, which is built into Python. No additional installation is required for the database.
   
### **Running the Project:**
1. Save the script to a file, e.g., `smart_parking.py`.
2. Execute the script from the command line or terminal using:
   ```bash
   python smart_parking.py
