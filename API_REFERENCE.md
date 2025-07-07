HEALS ERP offers a robust API layer for integration with third-party systems, apps, and medical devices. The platform includes **RESTful endpoints** with **FHIR-compliant** and **custom APIs** for advanced integrations.

### 🧾 Authentication

* OAuth2 (Password and Client Credentials Grant)
* JWT tokens for session-based validation
* API key support for internal services

### 🧑‍⚕️ Patient & Clinical APIs

* `GET /api/v1/patients/` — List all patients
* `POST /api/v1/patients/` — Create a new patient
* `GET /api/v1/appointments/` — Upcoming appointments
* `POST /api/v1/diagnosis/` — Add clinical diagnosis
* `GET /api/v1/vitals/{patient_id}` — Retrieve vitals

### 🧪 Lab & Imaging APIs

* `POST /api/v1/labs/order/` — Place lab test order
* `GET /api/v1/labs/results/{patient_id}` — View lab results
* `GET /api/v1/radiology/images/{study_id}` — Fetch PACS images

### 💳 Billing & Finance APIs

* `POST /api/v1/invoices/` — Generate new invoice
* `GET /api/v1/payments/` — View payments by date
* `GET /api/v1/claims/insurance/` — Insurance claim tracking

### 🧠 AI & Decision Support APIs

* `POST /api/v1/ai/diagnose/` — AI diagnosis from symptoms
* `GET /api/v1/ai/triage/{patient_id}` — AI triage priority score

### 📦 Inventory & Pharmacy APIs

* `GET /api/v1/pharmacy/stock/` — Available medicines
* `POST /api/v1/pharmacy/dispense/` — Record medication issue

### 📅 HR & Staff APIs

* `GET /api/v1/hr/employees/` — Staff directory
* `POST /api/v1/hr/attendance/` — Record punch-in/out

### 📡 FHIR API Endpoints (Samples)

* `GET /fhir/Patient` — Retrieve FHIR patient resources
* `POST /fhir/Observation` — Submit FHIR vital signs
* `GET /fhir/Condition` — View diagnoses by code

### 📘 API Documentation

Interactive Swagger / Redoc available at:

* `/docs/swagger/`
* `/docs/redoc/`

Postman collection available on request.

> 🔒 Note: All API access is subject to role and permission validations.
