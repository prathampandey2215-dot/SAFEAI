Database Design

SafeAI Database Documentation

Overview

The SafeAI database is designed to securely store user information, scan history, security settings, AI analysis results, and application data. The design focuses on scalability, security, and minimal data collection.

---

Database Architecture

SafeAI uses a modular database structure where each collection/table has a specific purpose.

---

Users

Stores user account information.

Fields

- userId
- fullName
- email
- profilePhoto
- accountCreated
- lastLogin
- accountStatus
- preferredLanguage

---

User Settings

Stores user preferences.

Fields

- userId
- theme
- notificationsEnabled
- language
- autoScanEnabled
- privacyMode
- biometricEnabled

---

Scan History

Stores every completed security scan.

Fields

- scanId
- userId
- scanType
- scanContent
- scanDate
- riskLevel
- resultSummary
- recommendation

---

Website Analysis

Stores website scan results.

Fields

- websiteId
- url
- scanTime
- httpsAvailable
- domainAge
- reputationScore
- aiAnalysis
- finalVerdict

---

QR Code Analysis

Stores QR scan information.

Fields

- qrId
- extractedContent
- destinationUrl
- riskLevel
- aiAnalysis
- scanTime

---

Message Analysis

Stores AI message scan results.

Fields

- messageId
- messageText
- detectedThreat
- confidenceScore
- explanation
- recommendation
- scanTime

---

Security Score

Stores user security information.

Fields

- userId
- score
- lastUpdated
- completedScans
- securityLevel

---

Notifications

Stores security alerts.

Fields

- notificationId
- userId
- title
- description
- notificationType
- createdAt
- isRead

---

AI Logs

Stores AI processing records.

Fields

- logId
- requestType
- processingTime
- modelVersion
- status
- timestamp

---

Privacy Principles

- Collect only required data.
- Encrypt sensitive information.
- Never store passwords in plain text.
- Protect user privacy.
- Allow users to delete their data.

---

Scalability

The database is designed to support:

- Millions of users
- Large scan histories
- AI model improvements
- Future security modules
- Multi-device synchronization

---

Future Collections

- Family Accounts
- Device Management
- Threat Intelligence
- Community Reports
- Enterprise Organizations

---

Conclusion

The SafeAI database is designed to be secure, scalable, efficient, and ready for future expansion while protecting user privacy.