# AIREASE
This code implements an airline reservation system (AIREASE) allowing users to book local and international flights, search for available flights, and view booking details &amp; generate ticket
Classes:
mytime: Handles time information for travel.
passenger: Abstract class managing passenger data.
booking: Inherits from passenger, handles local flight bookings.
search: Searches for available international flights.
local: Inherits from booking, adds functionality for local flight bookings.
international: Inherits from booking, adds functionality for international flight bookings.
main1: Manages the main menu and program flow.
Functions:
main(): Program entry point, initializes the main menu and starts the reservation system.
getdata(): Within main1, displays the main menu and handles user input.
Features:
Users can choose between booking local or international flights.
The system allows searching for available international flights.
Booking details are displayed for confirmation.
generates a ticket 
