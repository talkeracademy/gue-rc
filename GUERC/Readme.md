# GUERC - Professional Education Portal

A high-performance, secure education management platform built for GUERC. This project features a multi-lingual frontend and a custom-built administrative dashboard.

## 🚀 Key Features
- **Dynamic Content Management**: Admin can update Courses, Camps, and Articles in real-time.
- **Tri-lingual Support**: Full support for English, Uzbek, and Turkish.
- **Application Tracking**: Integrated CRM to manage student inquiries and program applications.
- **Data Portability**: One-click CSV export for external data analysis.

## 🛡️ DevSecOps & Security Highlights
- **Firestore Security Rules**: Implemented granular access control (Public: Read-only/Create | Admin: Full Access).
- **Authentication**: Firebase Auth with mandatory Email Verification for administrative access.
- **Authorized Domains**: Strict domain whitelisting to prevent unauthorized API calls.
- **Environment Safety**: Front-end validation for all user input fields to prevent injection.

## 🛠️ Tech Stack
- **Frontend**: HTML5, Tailwind CSS, JavaScript (ES6+).
- **Backend-as-a-Service**: Firebase (Firestore, Authentication, Hosting).
- **Libraries**: FontAwesome, SortableJS (for drag-and-drop management).

## 📂 Project Structure
- `index.html`: Main landing page for students.
- `admin.html`: Protected dashboard for staff.
- `firebase-rules.json`: Security logic for database protection.