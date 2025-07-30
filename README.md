# Cinema Booking System using PLSQL

### Overview

The Cinema Booking System is a ticket booking application developed using Oracle PL/SQL. The system allows users to book movie tickets, 
select available showtimes, and perform various other operations such as seat reservations, payments, and activity logging. The system also validates
registered users, prevents access for unregistered users, and ensures that users cannot delete their profiles if they have booked tickets.

### Features

- **User Registration**: Allows users to register and validate their identity before booking tickets.
- **Ticket Booking**: Enables users to book movie tickets by selecting from available seats and showtimes.
- **Seat Reservation**: Ensures no conflicts in seat allocation by checking available seats.
- **Payment Processing**: Calculates the total payment for the tickets and processes the payment.
- **Booking Logs**: Keeps a record of all booking activities for audit and review.
- **Prevention of Unauthorized Deletion**: Prevents deletion of users who have existing bookings.


![ER-diagram](/cinema booking.png)
