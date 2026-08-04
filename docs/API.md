API Documentation

Project

SafeAI – AI Powered Cybersecurity Platform

---

Purpose

This document defines the Application Programming Interfaces (APIs) used by SafeAI. It describes how the mobile application, backend services, AI engine, and database communicate securely.

---

API Design Principles

- RESTful API Design
- HTTPS Only
- JSON Request & Response
- Secure Authentication
- API Versioning
- Proper Error Handling
- Rate Limiting

---

Base URL

Production

https://api.safeai.app/v1/

Development

https://dev-api.safeai.app/v1/

---

Authentication APIs

Register

POST

/auth/register

Creates a new user account.

---

Login

POST

/auth/login

Authenticates a user.

---

Logout

POST

/auth/logout

Ends the current user session.

---

Refresh Token

POST

/auth/refresh

Refreshes the authentication token.

---

User APIs

Get Profile

GET

/user/profile

---

Update Profile

PUT

/user/profile

---

Delete Account

DELETE

/user/profile

---

AI APIs

Analyze Message

POST

/ai/message-analysis

Purpose:

Analyze suspicious SMS, email, or chat messages.

---

Analyze Website

POST

/ai/url-analysis

Purpose:

Analyze website safety.

---

Analyze QR Code

POST

/ai/qr-analysis

Purpose:

Check whether a QR code is safe before opening it.

---

Dashboard APIs

Security Score

GET

/dashboard/security-score

---

Scan History

GET

/dashboard/history

---

Settings APIs

GET

/settings

PUT

/settings

---

Notifications

GET

/notifications

PUT

/notifications/read

---

Response Format

Success

{
  "success": true,
  "message": "Request completed successfully",
  "data": {}
}

Error

{
  "success": false,
  "error": "Invalid request"
}

---

Security Requirements

- HTTPS
- Authentication
- Authorization
- Input Validation
- Rate Limiting
- Secure Logging

---

Future APIs

- Voice Assistant API
- Device Scanner API
- Browser Protection API
- Threat Intelligence API
- Family Dashboard API

---

API Version

Current Version

v1

---

Conclusion

The SafeAI API is designed to be secure, scalable, modular, and easy to maintain while supporting future enhancements.