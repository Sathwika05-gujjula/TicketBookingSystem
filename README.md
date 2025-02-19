# Railway Ticket Booking System  

## Overview  
The Railway Ticket Booking System is a simple Python-based console application that allows users to check train seat availability, book tickets, and check their PNR status. It simulates a basic railway reservation system with predefined trains, seat availability, and fares.

## Features  
- *Check Seat Availability* – View available seats for Sleeper and AC classes in different trains.  
- *Book a Ticket* – Reserve a seat by providing passenger details, train name, and class.  
- *Check PNR Status* – Retrieve booking details using a unique PNR number.  
- *Simple Console Interface* – Easy-to-use interactive menu for booking and inquiries.  

## Prerequisites  
- Python 3.x installed on your system.  
- Basic knowledge of running Python scripts in the terminal or command prompt.  

## How to Run  
1. Download or clone the repository.  
2. Open a terminal or command prompt in the project folder.  
3. Run the script using:  
   bash
   python railway_booking.py
   
4. Follow the on-screen instructions to check availability, book tickets, or check PNR status.  

## File Structure  
- *railway_booking.py* – Main script containing the booking system logic.  
- *README.md* – Project documentation.  

## Example Usage  
### Check Availability  

Enter train name: Rajdhani Express  
Enter class (Sleeper/AC): Sleeper  
Seats available in Rajdhani Express (Sleeper): 50  

### Book a Ticket  

Enter passenger name: John Doe  
Enter train name: Shatabdi Express  
Enter class (Sleeper/AC): AC  
Ticket booked successfully! PNR: PNR12345  

### Check PNR Status  

Enter PNR number: PNR12345  
Booking Details:  
Passenger: John Doe  
Train: Shatabdi Express  
Class: AC  
Fare: ₹1200  


## Future Enhancements  
- Implement a database for persistent storage.  
- Add cancellation and refund features.  
- Introduce a GUI-based interface for better user experience.  

## License  
This project is free to use and modify for learning purposes.
