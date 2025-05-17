Hospital Management System
Overview
SQL Database implementation to manage hospital workflows including patient, employee, appointment, billing, lab tests, and feedback management.

Database Specification
Purpose
Maintain patient and hospital employee records (doctors, nurses, lab assistants, admins).

Track patient appointments, billing details, lab tests, and disease history.

Store patient feedback linked to hospital employees.

Generate reports for data visualization and decision-making.

Business Rules
Employee table records all hospital employees with login info and hierarchy of who created whom.

Employee roles include Admin, Doctor, Nurse, Lab Assistant.

Patients have demographic and multiple address records.

Departments represent hospital units like Dental, Pediatric, Emergency, etc.

Doctors and patients can have multiple appointments.

Multiple attendants may attend a patient visit.

Patient visits are registered, and multiple visits are possible.

Feedback is linked from patients to employees.

Billing supports multiple transaction types per patient visit (Insurance, Attendant, Lab, etc.).

Design Requirements
Crow’s Foot Notation used for ERD.

Primary keys explicitly specified.

Relationships indicated with one and many symbols.

ER Diagram
(Insert ER Diagram image or link here)

