#  Flight Management System (Oracle SQL Project)

A robust and modular flight crew management system built using Oracle SQL. This project aims to simplify airline operations by automating the management of flights, crew scheduling, and airport infrastructure.

##  Objective

To develop an efficient, scalable, and normalized database system for managing:
- Flight crew details and scheduling
- Airport runways and terminals
- Flights, passengers, and bookings
- Real-time validation and reporting using SQL queries, triggers, procedures, and cursors

##  Key Features

-  **Crew Management:** Insert and manage flight crew, hostesses, and airline staff with structured relationships.
-  **Flight Scheduling:** Relational mapping between airports, runways, terminals, and flights.
-  **Passenger Handling:** Simulate bookings, round trips, and passenger information.
-  **Data Automation:** Uses procedures and triggers to automate business logic (e.g., seat validation, unique constraints).
-  **Reports and Queries:** Includes analytics like busiest airports, flight distances, and crew assignments using advanced SQL.

##  Technologies Used

- **Database:** Oracle SQL
- **Tools:** SQL*Plus / Oracle Live SQL
- **Concepts:** 
  - ER Modeling and Relationship Mapping
  - 3NF/BCNF Normalization
  - SQL Joins, Views, Cursors
  - Triggers and Stored Procedures

##  Schema Overview

- `airlines`, `aeroplanes`, `airports`
- `flightcrew`, `flightcrewhostess`, `airlinecrew`
- `passengers`, `flightsgoing`, `terminals`, `runways`
- Many-to-many and one-to-many mappings for realistic data relationships

## Sample SQL Operations

- **Triggers:** Validate flight schedules and enforce constraints
- **Procedures:** Display crew & aircraft info
- **Cursors:** Fetch sequential crew data and airport details
- **Queries:** Top 5 busiest airports, round-trip passengers, flight availability

##  Outcomes

- Centralized and normalized schema in 3NF/BCNF
- Bulk data entry using modular insert scripts
- Highly scalable and ready for integration with front-end tools or APIs

## Future Scope

- Web-based UI for booking and admin dashboard
- Real-time data tracking via API integration
- Expansion to include cargo tracking and in-flight services

---

>  Developed by: Mitul Pabri (102303793)  
>  Thapar Institute of Engineering & Technology, 2025  
```

---

### To Use:

1. Create a repository on GitHub (e.g., `Flight-Management-System`).
2. Add your SQL scripts and ER diagram images.
3. Save the above content as `README.md` and push it to your repo.
