
Mariam Walid 

Responsibilities:

	1.	Flight Class:
	•	Attributes:
	•	flightNumber, departure, destination, departureTime, arrivalTime, availableSeats, ticketPrice, flightType (Economy, Business, First Class).
	•	Encapsulation:
	•	All attributes are private with getter and setter methods.
	•	Methods:
	•	Constructor(s) for initializing flight details.
	•	calculateTicketPrice():
	•	Determines price based on class type (Economy, Business, First Class).
	•	Applies discounts for children, seniors, or frequent flyers.
	2.	Passenger Class:
	•	Attributes:
	•	passengerName, passengerID, flightNumber, frequentFlyerPoints, bookingHistory (list of past flights).
	•	Methods:
	•	updateFrequentFlyerPoints(int miles): Adds miles to a passenger’s points.
	•	viewBookingHistory(): Displays a passenger’s booking history.
	•	Constructor(s) to initialize passenger details.
	3.	Flight Extensions:
	•	Create subclasses of Flight:
	•	DomesticFlight:
	•	Specialized attributes or methods (e.g., no visa required, lower cost).
	•	InternationalFlight:
	•	Additional attributes (e.g., visa requirements, higher cost).

Mariam Sarhan

Responsibilities:

	1.	Flight Management:
	•	Manage a list of Flight objects using a collection (e.g., ArrayList).
	•	Methods:
	•	addFlight(Flight flight): Add a flight to the system.
	•	viewFlights(): Display all available flights or a specific flight.
	•	updateFlight(String flightNumber): Modify flight details (e.g., departure time, available seats).
	•	deleteFlight(String flightNumber): Remove a flight from the system.
	•	searchFlights(String criteria): Find flights by destination, price, or time.
	2.	Passenger Management:
	•	Manage a list of Passenger objects for each flight.
	•	Methods:
	•	bookSeat(String flightNumber, Passenger passenger):
	•	Assign a seat to a passenger and update availability.
	•	cancelReservation(String passengerID):
	•	Remove a passenger from a flight and update availability.
	•	viewBookingHistory(String passengerID):
	•	Retrieve a passenger’s booking history.
	3.	Analytics and Reports:
	•	Methods:
	•	generateDailyReport(): Summarizes bookings, cancellations, and available seats.
	•	viewPopularRoutes(): Identifies frequently traveled routes.

Farida Soliman

Responsibilities:

	1.	Enhanced Console Interface:
	•	Create a user-friendly menu system:
	•	Options:
	1.	Add Flight
	2.	View Flights
	3.	Search Flights
	4.	Book Seat
	5.	Cancel Reservation
	6.	View Passenger Booking History
	7.	Generate Reports (Daily Report and Popular Routes)
	8.	Exit
	•	Take user input using Scanner and call appropriate methods from FlightManager.
	2.	Error Handling and Validation:
	•	Validate all inputs (e.g., flight numbers, passenger IDs).
	•	Display meaningful error messages for invalid inputs.
	•	Ensure recovery from invalid operations (e.g., booking on a full flight).
	3.	Data Persistence:
	•	Implement file handling or connect to a database (e.g., SQLite):
	•	Save and load flight and passenger data.
	•	Methods for writing and reading data.
	4.	Concurrency:
	•	Use multithreading to simulate multiple users booking and canceling flights at the same time.
	5.	Testing and Debugging:
	•	Create test cases to simulate all functionalities.
	•	Verify the correctness of booking, cancellations, and reports.
