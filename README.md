# My CRM App - Flutter

A CRM application with GST billing for Indian businesses.

## Features Built So Far

### ✅ Phase 1 (Complete)
- Dashboard with stats overview
- Client Management (Add, Edit, Delete, Search)
- Local SQLite database
- Beautiful UI with Indian business focus

### 🔄 Coming Soon
- Phase 2: Quotations with GST
- Phase 3: GST Invoices (CGST/SGST/IGST)
- Phase 4: Sales & Expense Reports
- Phase 5: PDF generation & sharing

---

## Setup Instructions (For Developer)

### Prerequisites
- Flutter SDK (3.0+): https://flutter.dev/docs/get-started/install
- Android Studio or Xcode
- A Mac is required for iOS builds

### Steps to Run

1. **Install Flutter** from https://flutter.dev

2. **Clone/Copy** this project folder

3. **Open terminal** in the project folder and run:
   ```bash
   flutter pub get
   ```

4. **Run on Android:**
   ```bash
   flutter run
   ```

5. **Run on iOS (Mac only):**
   ```bash
   flutter run
   ```

6. **Build APK for Android:**
   ```bash
   flutter build apk --release
   ```

---

## Project Structure

```
lib/
├── main.dart                    # App entry point
├── models/
│   └── client.dart              # Client data model
├── screens/
│   ├── dashboard/
│   │   └── dashboard_screen.dart
│   └── clients/
│       ├── clients_screen.dart
│       ├── add_edit_client_screen.dart
│       └── client_detail_screen.dart
├── services/
│   └── database_service.dart    # SQLite database
└── utils/
    └── app_theme.dart           # Colors & theme
```

---

## Customizing Your Company Details

Open `lib/utils/app_theme.dart` and update:
```dart
static const String companyName = 'YOUR COMPANY NAME';
static const String companyAddress = 'YOUR ADDRESS';
static const String companyGSTIN = 'YOUR GSTIN';
static const String companyPhone = 'YOUR PHONE';
static const String companyEmail = 'YOUR EMAIL';
```

---

## Tech Stack
- **Flutter** (Cross-platform iOS & Android)
- **SQLite** (Local database via sqflite)
- **Google Fonts** (Poppins font)

---

Built with ❤️ for Indian businesses
