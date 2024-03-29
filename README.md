Electronic Bus Fare Payment System (EBFPS) 


EBFPS is a web-based application designed to streamline the process of booking bus tickets and managing fare payments electronically. This system offers a user-friendly interface for passengers to easily book tickets, check PNR status, and Additionally, it provides robust management tools for bus operators and administrators to efficiently manage routes, buses, and bookings.

git clone https://github.com/your-Sirmooooh/Electronic-Bus-Fare-Ticketing-Software.git

cd EBFPS

php -S localhost:8000

http://localhost:8000


FEATURES

Manage  bookings.
Booking Management: Passengers can search for routes, select seats, and make bookings seamlessly.
PNR Enquiry: Passengers can check the status of their bookings using their PNR (Passenger Name Record) numbers.
Administrator Dashboard: Bus operators and administrators have access to a dashboard for managing routes, buses, and bookings.

API DOCUMENTATION

Routes
GET /routes: Retrieve all available bus routes.
GET /routes/:id: Retrieve details of a specific route by ID.
POST /routes: Add a new route.
PUT /routes/:id: Update details of an existing route.
DELETE /routes/:id: Delete a route by ID.

BOOKINGS

GET /bookings: Retrieve all bookings.
GET /bookings/:pnr: Retrieve details of a booking by PNR.
POST /bookings: Make a new booking.
PUT /bookings/:pnr: Update details of an existing booking.
DELETE /bookings/:pnr: Cancel a booking by PNR.

CUSTOMERS

GET /customers: Retrieve all customers.
GET /customers/:id: Retrieve details of a customer by ID.
POST /customers: Add a new customer.
PUT /customers/:id: Update details of an existing customer.
DELETE /customers/:id: Delete a customer by ID.
Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: PHP, MySQL
Payment Gateway: Stripe API

Contributors
Moses Ngugi
Muhammad Rabiu Usman

License
This project is licensed under the MIT License - see the LICENSE file for details.
