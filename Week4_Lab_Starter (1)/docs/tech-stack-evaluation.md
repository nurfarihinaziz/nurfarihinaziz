# Tech Stack Evaluation

## Project
AI Healthcare Appointment Assistant – An AI-powered web application that helps patients search for doctors, book and manage healthcare appointments, and receive assistance through an intelligent chatbot.

## Requirements that drive the decision

The following requirements are based on the project's `docs/requirements.md`.

- **FR1:** The system shall allow patients to register, log in, and manage their personal profiles securely.
- **FR2:** The system shall allow patients to search for doctors, healthcare services, and available appointment slots.
- **FR3:** The system shall allow patients to book, reschedule, and cancel healthcare appointments online.
- **FR4:** The system shall provide an AI-powered chatbot to answer common appointment-related questions and assist patients with the appointment booking process.
- **NFR1:** The system shall display search results and appointment availability within 3 seconds under normal operating conditions.
- **NFR2:** The system shall protect patient information through secure authentication and encrypted data transmission.
- **NFR3:** The system shall provide a user-friendly and responsive interface that supports desktop computers, tablets, and mobile devices.

## Options

- **Option A:** Static website using HTML, CSS and JavaScript hosted on GitHub Pages.
- **Option B:** Python web application using Flask, SQLite/MySQL database and an AI chatbot API.
- **Option C:** PHP web application using HTML, CSS, JavaScript, MySQL database and an AI chatbot API.

## Decision Matrix

Weight: 1 = Low importance, 5 = High importance.
Score: 1 = Poor, 5 = Excellent.
Weighted score = Weight × Score.

| Criterion | Weight | A Score | B Score | C Score |
|---|---:|---:|---:|---:|
| Fits my requirements | 5 | 2 | 4 | 5 |
| Skills I already have | 5 | 4 | 2 | 5 |
| Time to build before my deadline | 5 | 5 | 3 | 4 |
| Free hosting and tools | 4 | 5 | 3 | 4 |
| Performance and security needs | 4 | 2 | 4 | 4 |
| Room to grow later | 3 | 2 | 4 | 4 |
| **Total (weighted)** | | **89** | **85** | **114** |

## Decision Record

- **Context:** The AI Healthcare Appointment Assistant requires a web application that supports patient registration, doctor searches, appointment management and AI chatbot assistance. The project must be developed within a limited academic timeframe and budget. The technology should also be manageable for a student and support database integration.

- **Decision:** Option C – PHP, MySQL, HTML, CSS, JavaScript and an AI chatbot API.

- **Reasons:**
  1. PHP and MySQL support essential system functions such as patient registration, login, doctor information and appointment booking.
  2. These technologies are familiar and suitable for student-level web development, reducing the learning time and development effort.
  3. JavaScript and an AI chatbot API can be integrated to provide interactive chatbot assistance and improve the patient experience.

- **Consequences:** PHP and MySQL make it easier to develop database-driven features, manage patient records and implement appointment scheduling. JavaScript supports a responsive and interactive user interface. However, integrating an AI chatbot requires additional API configuration, internet access and potentially API usage costs.

- **Risks and Next Review:** Potential risks include database security issues, unauthorised access to patient information, chatbot API limitations and hosting costs. Security measures such as password hashing, input validation, secure authentication and encrypted communication should be implemented. The technology decision will be reviewed after the initial system prototype is developed to ensure that the selected stack meets the project requirements.
