Hospital Appointment System

Overview: This is a Hospital Appointment System frontend built with AngularJS (1.x) that allows patients to register, log in, and book appointments with doctors. The system also provides a view of upcoming appointments and doctors’ schedules. It is designed to work with a backend API connected to an SQL database (MySQL, PostgreSQL, etc.) for storing patient, doctor, and appointment data.

Key Features:

Patient Registration & Login: Secure registration and authentication for patients.

Book Appointments: Patients can select doctors, choose date and time, and provide reasons for appointments.

View My Appointments: List of upcoming appointments with status and cancel option.

Doctor Directory: View all doctors with specialty, availability, and schedule.

Dynamic UI with AngularJS: Real-time updates on booking, cancellation, and schedule viewing.

Responsive Design: Uses Bootstrap for mobile-friendly and clean layout.

Technologies Used:

Frontend: AngularJS 1.x, HTML5, CSS3, Bootstrap 4

Backend (optional): Node.js/Express (REST API) or PHP

Database: SQL (MySQL/PostgreSQL recommended)

Demo / Placeholder Data:

The HTML frontend includes demo data for doctors and appointments, so the UI can be tested even without a backend.

Backend API endpoints (REST) are required to save and fetch live data:

POST /api/patients – Register patient

POST /api/login – Login patient

GET /api/doctors – Get list of doctors

POST /api/appointments – Book an appointment

GET /api/patients/:id/appointments – Get patient appointments

GET /api/doctors/:id/appointments – Get doctor schedule

DELETE /api/appointments/:id – Cancel appointment

Screenshots / Usage:

Users can register or login to book appointments.

The dashboard shows the “My Appointments” table and doctor list.

Clicking “View Schedule” shows upcoming appointments for a doctor.

How to Run Locally:

Save the HTML file as index.html.

Open it directly in a browser for demo view (data is static).

For full functionality, implement a backend API connected to a SQL database and configure API endpoints.

Optionally, serve the frontend using a local server (e.g., python -m http.server 8000) to avoid browser restrictions.

Future Enhancements:

Role-based access (admin, staff, patient)

Real-time notifications for appointment updates

Integration with email/SMS reminders

Advanced search and filtering of doctors and appointments
