# Privacy Policy

**Last Updated:** February 7, 2025

**Effective Date:** February 7, 2025

---

## Introduction

Welcome to "ExpenseTracker" (hereinafter referred to as "the App"). We understand the importance of privacy to our users and are committed to protecting your personal information. This Privacy Policy explains how the App collects, uses, stores, and protects your data.

By using this App, you agree to the terms of this Privacy Policy. If you do not agree to these terms, please do not use the App.

---

## 1. Information We Collect

### 1.1 Information You Provide

**Financial Transaction Data**
- Income and expense amounts
- Transaction date and time
- Transaction categories (dining, transport, shopping, etc.)
- Transaction descriptions (text notes you enter)
- Transaction currency type
- Exchange rate snapshot data

**User Settings**
- Default currency preference
- Monthly budget settings

### 1.2 Information Automatically Collected

**Location Information**
- When you choose to add a location, the App collects transaction geographic location (latitude and longitude coordinates)
- Location information is used solely for recording transaction location and is not used for any other purpose

**Voice Input Data**
- When you use the voice input feature, your voice data is sent to Apple's speech recognition service for conversion
- Voice data is used only to convert to text; original voice recordings are not saved after conversion

**Usage Data**
- App crash logs and performance data (used to improve app stability)

---

## 2. How We Use Your Information

### 2.1 Primary Purposes

- **Expense Tracking**: Record, manage, and analyze your income and expenses
- **Data Synchronization**: Synchronize your data across your devices via iCloud
- **AI Recognition**: Use natural language processing to convert text or voice input into structured expense records
- **Currency Conversion**: Obtain and calculate real-time exchange rates for multi-currency expense tracking
- **Data Export**: Allow you to export your personal financial data

### 2.2 We Will Not

- Sell your personal information
- Use your data for advertising targeting
- Sell your financial data to third parties
- Use your data for purposes other than those described without your explicit consent

---

## 3. Data Storage and Security

### 3.1 Local Storage

- All your data is stored locally on your device (SQLite database)
- Data file location: `~/Library/Application Support/todo_database.sqlite`
- Local data is protected by iOS system security mechanisms

### 3.2 Cloud Storage (iCloud)

- The App uses Apple's CloudKit service for data synchronization
- Data is stored in your **iCloud Private Database**
- Only you can access data stored in iCloud
- Apple provides end-to-end encryption protection
- Data is transmitted via encrypted connections during synchronization

### 3.3 Data Security Measures

- Industry-standard encryption technology to protect data
- Following Apple iOS security best practices
- Regular app updates to fix security vulnerabilities

---

## 4. Third-Party Services

This App uses the following third-party services:

### 4.1 Apple CloudKit (iCloud Sync)

- **Purpose**: Synchronize data across your devices
- **Data Processing**: Data is stored in your iCloud account
- **Privacy Policy**: [Apple Privacy Policy](https://www.apple.com/privacy/)

### 4.2 Apple Speech Framework (Speech Recognition)

- **Purpose**: Convert voice to text
- **Data Processing**: Voice data is sent to Apple servers for recognition
- **Privacy Policy**: [Apple Speech Recognition Privacy](https://www.apple.com/privacy/)

### 4.3 DeepSeek API (AI Text Recognition)

- **Purpose**: Understand natural language and convert to expense records
- **Data Sent**: Text descriptions you enter
- **Data Processing**:
  - Text is used only for AI recognition and is not used to train AI models
  - Does not include sensitive information such as financial amounts (only descriptive text)
  - Transmitted via HTTPS encrypted connection
- **Privacy Policy**: [DeepSeek Privacy Policy](https://www.deepseek.com/privacy)

### 4.4 Exchange Rate API (open.er-api.com)

- **Purpose**: Obtain real-time exchange rate information
- **Data Sent**: No personal data is sent; only requests for public exchange rate data
- **Data Source**: European Central Bank public exchange rate data

---

## 5. Data Sharing

We **do not** sell, rent, or trade your personal information to third parties.

Data is shared only in the following circumstances:

- **With Your Consent**: You have explicitly authorized data sharing
- **Legal Requirements**: Required by law or government authorities
- **Protect Rights**: To protect our rights, property, or safety
- **Service Providers**: Only to third parties necessary for providing App functionality (such as CloudKit, speech recognition services)

---

## 6. Your Rights

You have the following rights regarding your data:

### 6.1 Right to Access

- You can view all expense records in the App at any time

### 6.2 Right to Delete

- You can delete any individual expense record
- Through the "Data Management" feature in the App, you can delete all local data

### 6.3 Right to Export

- The App supports exporting your data in CSV format
- Export feature is located in "Profile" → "Data Export"

### 6.4 Right to Opt Out of iCloud Sync

- You can disable iCloud sync for this App in iOS Settings
- After disabling, data will be stored only on your local device

---

## 7. Data Retention

- **Expense Records**: Stored locally permanently until you actively delete them
- **iCloud Data**: Follows Apple iCloud data retention policy
- **Voice Data**: Not stored on devices or servers
- **Exported Files**: Stored in the location you choose for export

---

## 8. Children's Privacy

This App is intended for users aged 13 and above. We do not knowingly collect personal information from children under 13. If you discover that we have inadvertently collected information from a child, please contact us and we will take steps to delete this information.

---

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we make significant changes, we will notify you by:

- Posting a notification within the App
- Updating the "Last Updated" date on this page

Continued use of the App after changes indicates your acceptance of the updated Privacy Policy.

---

## 10. Contact Us

If you have any questions, comments, or complaints about this Privacy Policy, please contact us:

- **App Name**: ExpenseTracker
- **Email**: [your-email@example.com]
- **Feedback**: App Store reviews or [GitHub Issues](https://github.com/your-repo/issues)

---

## 11. Applicable Law

This Privacy Policy is governed by the laws of the People's Republic of China.

---

## Appendix: Technical Data Flow

```
User Input → Local Processing → Local SQLite Storage
                ↓
          iCloud CloudKit (Encrypted Sync)
                ↓
          User's Other Devices

Voice Input → Apple Speech API → Text → Local Storage
Text Input → DeepSeek API → Structured Data → Local Storage
Exchange Rate Request → open.er-api.com → Exchange Rate Data → Local Cache
```

---

**Version**: 1.0

**Language**: English

---

