Folder Structure

Project

SafeAI – AI Powered Cybersecurity Platform

---

Purpose

This document defines the official folder structure for the SafeAI project. A consistent structure improves maintainability, collaboration, and scalability.

---

Root Directory

SafeAI/
├── android/
├── ios/
├── web/
├── linux/
├── macos/
├── windows/
├── lib/
├── assets/
├── test/
├── docs/
├── scripts/
├── .github/
├── README.md
├── LICENSE
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── pubspec.yaml
└── analysis_options.yaml

---

lib/

The main Flutter source code.

lib/
├── core/
├── config/
├── shared/
├── features/
├── services/
├── models/
├── repositories/
├── providers/
├── routes/
├── utils/
├── widgets/
└── main.dart

---

core/

Application-wide components.

core/
├── constants/
├── errors/
├── exceptions/
├── themes/
├── localization/
└── security/

---

config/

Application configuration.

config/
├── app_config.dart
├── api_config.dart
├── firebase_config.dart
└── environment.dart

---

features/

Every feature has its own folder.

features/
├── authentication/
├── dashboard/
├── message_scanner/
├── website_checker/
├── qr_scanner/
├── security_score/
├── settings/
└── profile/

Each feature may contain:

feature_name/
├── screens/
├── widgets/
├── controllers/
├── models/
├── services/
└── repository/

---

services/

Shared services.

services/
├── ai_service.dart
├── auth_service.dart
├── database_service.dart
├── network_service.dart
├── notification_service.dart
└── storage_service.dart

---

models/

Application data models.

Examples:

- user_model.dart
- scan_result.dart
- security_score.dart
- notification_model.dart

---

repositories/

Repository layer for data access.

Examples:

- auth_repository.dart
- scan_repository.dart
- profile_repository.dart

---

providers/

State management providers.

Examples:

- auth_provider.dart
- dashboard_provider.dart
- settings_provider.dart

---

widgets/

Reusable UI components.

Examples:

- custom_button.dart
- custom_card.dart
- loading_indicator.dart
- app_bar.dart

---

assets/

Application assets.

assets/
├── icons/
├── images/
├── fonts/
├── animations/
├── illustrations/
└── sounds/

---

test/

Project testing.

test/
├── unit/
├── widget/
├── integration/
└── mocks/

---

docs/

Project documentation.

Contains all Markdown documents related to planning, architecture, security, and development.

---

scripts/

Automation scripts.

Examples:

- build.sh
- deploy.sh
- setup.sh

---

.github/

GitHub configuration.

.github/
├── workflows/
├── ISSUE_TEMPLATE/
└── PULL_REQUEST_TEMPLATE.md

---

Benefits

- Easy navigation
- Modular development
- Scalable architecture
- Improved maintainability
- Better collaboration
- Consistent organization

---

Conclusion

This folder structure is the official project organization for SafeAI and should be followed throughout development.