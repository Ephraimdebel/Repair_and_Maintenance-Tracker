# Repair and Maintenance Tracker
---

## Team Members
| Name            | ID.NO       | Section |
|----------------|------------|---------|
| Ruth Ambaw     | UGR/8802/15 | 4       |
| Alpha Degago   | UGR/4592/15 | 3       |
| Saron Tadesse  | UGR/5471/15 | 4       |
| Ephraim Debel  | UGR/0640/15 | 4       |

---

## Project Overview
Repair & Maintenance Tracker is a mobile application built with Jetpack Compose that enables users to log, track, and manage repair requests and maintenance schedules for personal items such as electronics, vehicles, or home appliances. The app ensures secure authentication and operates with a local backend using Node.js and MySQL, following a structured CRUD-based approach.

The system includes two business features, authentication and authorization, a backend REST API to serve the frontend, and thorough testing, including widget, unit, and integration testing.

---

## Features

### Repair Requests Management (CRUD)
- **Create:** Users can log a repair request with details like item name, issue description, and date.
- **Read:** View a list of logged repair requests with filtering options.
- **Update:** Modify repair requests, such as changing the status to "In Progress" or "Completed."
- **Delete:** Remove a repair request if it is no longer needed.

### Maintenance Schedule Management (CRUD)
- **Create:** Users can schedule maintenance tasks (e.g., "AC Cleaning" or "Car Oil Change").
- **Read:** View and filter upcoming maintenance schedules.
- **Update:** Modify the details or timing of maintenance tasks.
- **Delete:** Remove completed or unnecessary maintenance tasks.

### Authentication & Authorization
- **User Registration & Login:** Secure user authentication using JWT-based authentication.
- **Role-based Access Control:** Ensures users can only access and manage their own data.
- **Session Management:** Secure token storage and expiration handling.

### Backend & API
- **REST API:** Built with Node.js and Express to serve the frontend.
- **Database:** MySQL for storing repair requests, maintenance schedules, and user data.

### Testing
- **Widget Testing:** Ensures UI components function correctly.
- **Unit Testing:** Verifies the correctness of individual functions and components.
- **Integration Testing:** Ensures seamless interaction between frontend and backend.

---

## Tech Stack
- **Frontend:** Jetpack Compose (Kotlin)
- **Backend:** Node.js with Express (REST API)
- **Database:** MySQL (Local Storage)
- **Authentication:** JWT-Based Authentication




