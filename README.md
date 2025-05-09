# ticket-booking-api-automation
This repository contains automated Postman tests for the Ticket Booking API, covering user login, authorization, booking creation, updating bookings, fetching booking details by ID, and pinging the service for availability.
# 🎟️ Ticket Booking API Automation

This repository contains automated API tests for the **Ticket Booking System**, created using **Postman**. The project validates key functionalities of the API including user authentication, booking creation, retrieval, updating, and health checks.

---

## 📁 Project Structure

| File/Folder       | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `ticketbookingpostman_collection.json` | Postman collection containing all the test cases across API endpoints. |
| `TicketBookingAPIReport.html`             | Exported HTML report showing the results of test executions.            |

---

## ✅ Features Tested

- 🔐 **User Login & Authorization**
- 📥 **Create New Booking**
- 📤 **Update Existing Booking**
- 🔍 **Get Booking by ID**
- 🔄 **Get All Bookings**
- 🩺 **Ping Service (Health Check)**

Each test case includes proper status code validation, field validation, and negative test scenarios.

---

## 🚀 How to Run the Tests

1. **Install Postman** (if not already):  
   [Download Postman](https://www.postman.com/downloads/)

2. **Import the Collection**:
   - Open Postman.
   - Click on `Import` > `Upload Files`.
   - Select `TicketBookingAPI.postman_collection.json`.

3. **Run the Tests**:
   - Use the `Collection Runner` in Postman.
   - Select the collection and run all tests.
   - Optionally export the report.

---

## 📊 Reporting

- HTML report: `TicketBookingAPIReport.html`
- Contains summary, detailed test results, and assertion outcomes.

---

## 🛠️ Tools Used

- **Postman** – For API test design and execution
- **Newman** (optional) – To run tests from CLI and generate advanced reports

---

## 📌 Notes

- Make sure the API base URL and authentication details (if required) are correctly configured in the environment.
- The tests are designed for demonstration purposes and follow standard API testing practices.

---

## 🧑‍💻 Author

**Ayesha Sajid**  
GitHub: [@ayeshaasajid](https://github.com/ayeshaasajid)

---


