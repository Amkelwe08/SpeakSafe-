SpeakSafe

Document it. Report it. Be heard.

SpeakSafe is a private, encrypted web platform designed to empower women students and staff to document abuse, report incidents safely, preserve evidence, and understand their rights.

The platform provides a safe space for individuals experiencing sexual, verbal, or online abuse, helping them take control of their experiences and access support when they are ready.

Problem Statement

Many women students and staff experience different forms of abuse but hesitate to report them because of:

- Fear of not being believed or facing retaliation.
- Uncertainty about their rights and reporting procedures.
- Difficulty preserving evidence and remembering incident details.
- Concerns about privacy and confidentiality.

SpeakSafe aims to address these challenges through accessible technology.

Key Features

1. Incident Reporting

- Submit reports directly to Student Wellness.
- Describe incidents and attach up to three photographs.
- Receive a unique serial code for tracking.
- Receive a PDF copy of the submitted report.

2. Private Incident Journal

- Record incidents privately.
- Attach up to five photographs per entry.
- Encrypt journal entries using a key derived from the user's number and password.
- Export journal entries as text.

3. Know Your Rights

- Access information about different forms of abuse.
- Understand your rights.
- Find guidance on available support and reporting options.

4. Emergency Exit Button

- Quickly hide the website using one click or the Escape key.
- Automatically sign the user out.
- Redirect to a weather page to protect privacy if someone enters the room.

Privacy and Security

SpeakSafe is designed with privacy and security as important considerations.

- AES-GCM Encryption: Protects private journal entries and account information.
- RSA Encryption: Seals the user's identity in submitted reports using Student Wellness' public key.
- GPS Metadata Removal: Removes location metadata from uploaded photographs.
- Serial Code Reporting: Allows Student Wellness to respond using a unique report reference instead of displaying the user's identity.

Important: SpeakSafe provides confidential reporting, not complete anonymity. Student Wellness can identify the individual through the protected identity information using its private key. Users are informed and must consent before submitting a report.

Technologies Used

- HTML5
- CSS3
- JavaScript
- AES-GCM Encryption
- RSA Encryption
- PDF Report Generation

Target Users

- Women Students and Staff: A private way to document incidents, understand their rights, and report abuse.
- Student Wellness: Receives structured reports with evidence and serial codes.
- Educational Institutions: Provides an additional channel for addressing abuse and supporting affected individuals.

Deployment and Adoption

SpeakSafe is designed as a lightweight web application.

- No additional server installation is required for the current prototype.
- No software installation is required for users.
- Institutions can adopt the platform by updating one configuration file.

The initial target institution is Rosebank College.

Future Improvements

Planned improvements include:

- An institutional dashboard for managing reports and responding through serial codes.
- Student verification through institutional Single Sign-On (SSO) or an approved student database.
- Synchronisation of private journals across multiple devices.
- Support for additional languages.
- Partnerships with non-governmental organisations (NGOs).

Project Team

Developed by:

- Abulele Nkabi
- Musa Boltina
- Mvuyisi Sokabo
- Somila Notshoba
- Amkelwe Tuta

Hackathon Theme: Empower Women Through Technology.

Project Mission

SpeakSafe exists to create a safer environment where women can document their experiences, report abuse when they are ready, understand their rights, and have their voices heard.

SpeakSafe: Safe to document. Safe to report. Safe to be heard.

SpeakSafe/
│
├── README.md
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
└── assets/
