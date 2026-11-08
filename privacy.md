# Privacy Policy for SM Type Test

**Effective Date:** November 8, 2026

### 1. Overview
SM Type Test ("the Application") is a desktop typing practice and evaluation tool developed by Bonanto. This Privacy Policy explains how the Application handles data. Our core philosophy is strict user privacy: all personal data, typing progress, and user-generated content remain strictly local to your device. 

### 2. Data Collection and Local Storage
The Application does not collect, transmit, or store any personal data on external servers. All user data is stored locally on your machine within the `.smtt` directory in your user profile. This includes:
* Typing test results and historical progress (stored in a local SQLite database).
* Custom exam profiles, scoring rules, and app settings.
* Hardcopy passages and locally processed OCR data.

You retain full control over this data. You may delete it at any time by removing the `.smtt` folder.

### 3. Network Usage and Updates
The Application does not feature telemetry, usage tracking, or crash analytics reporting to the developer. The only network activity performed by the Application is an optional update check. 
* **Update Checks:** If enabled in settings, the Application pings the public GitHub API to check for new releases, updated passages, or OCR engine updates. This request only transmits standard, anonymized HTTP headers (such as your IP address and user agent) inherent to standard web requests. This data is processed by GitHub in accordance with their privacy policy and is not logged, stored, or accessible by the developer of this Application.

### 4. Third-Party Components
The Application utilizes third-party open-source components (including Tesseract OCR, Qt/PySide6, and Python runtimes) which execute entirely offline and do not transmit personal data.

### 5. Changes to This Policy
If significant changes are made to how the Application handles data in future updates, this policy will be updated accordingly. The date of the latest revision will always be displayed at the top of this page.

### 6. Contact
If you have any questions regarding this Privacy Policy or your data, please open an issue on the official GitHub repository at `https://github.com/bonanto/smtt/issues`.
