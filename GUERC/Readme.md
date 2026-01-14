# Global Uzbek Education Research Center (GUERC) Portal

A secure, multi-lingual educational platform and administrative dashboard designed for scalability and data integrity.

## 🏗️ Architecture & DevSecOps Focus
This project was built with a "Security by Design" mindset, essential for modern DevSecOps workflows:

- **Identity & Access Management (IAM)**: Leverages Firebase Authentication with mandatory SMTP-based email verification gates for administrative privileges.
- **Database Hardening**: Firestore Security Rules implement a "Least Privilege" model, separating public `write` (applications) from administrative `read/write` (content management).
- **Domain Whitelisting**: Restricted OAuth redirects and API calls to authorized production domains only.
- **Data Portability**: Integrated sanitization logic for CSV exports to ensure Excel-compatibility and data backup reliability.

## 🚀 Technical Specifications
- **Frontend**: Vanilla JS (ES6+), Tailwind CSS (JIT Engine).
- **Backend**: Firebase Cloud Firestore (NoSQL), Firebase Hosting.
- **UI/UX**: Responsive glassmorphism design, multi-language state management (UZ, EN, TR).

## 🛠️ Installation & Deployment
1. Clone the repository.
2. Initialize Firebase CLI: `firebase init`.
3. Deploy Security Rules: `firebase deploy --only firestore:rules`.
4. Deploy Hosting: `firebase deploy --only hosting`.

---
*Developed with a focus on secure deployment pipelines and administrative efficiency.*