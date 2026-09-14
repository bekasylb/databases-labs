# Database — Laboratory Work 1

## ERD Diagram — International Airport

This repository contains Laboratory Work 1 for the Databases course.

### Contents
- `Laboratory_Work_1_International_Airport.pdf` — ERD diagram, entities and attributes, relationships, constraints, legend, and textual description.

### Main Entities
1. Airport
2. Airline
3. Flight
4. Passenger
5. Booking
6. BookingChange
7. BoardingPass
8. Baggage
9. BaggageCheck
10. SecurityCheck

### Main Relationships
- Airline 1:N Flight
- Airport 1:N Flight (departure)
- Airport 1:N Flight (arrival)
- Passenger 1:N Booking
- Flight 1:N Booking
- Booking 1:1 BoardingPass
- Booking 1:N Baggage
- Booking 1:N BookingChange
- Booking 1:N BaggageCheck
- Passenger 1:N BaggageCheck
- Passenger 1:N SecurityCheck
