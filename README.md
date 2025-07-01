# snab_budget

<div align="center">
  <h1>
    <img src="assets/images/logo.png" width="80px"><br/>
    snab_budget
  </h1>
  <h3>Personal & Family Budget Management App</h3>
</div>

<p align="center">
    <a href="https://github.com/" target="_blank">
        <img alt="GitHub" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
    </a>
    <a href="APK/app-arm64-v8a-release.apk" target="_blank">
        <img alt="Download APK" src="https://img.shields.io/badge/Download-APK-green?style=for-the-badge&logo=android" />
    </a>
</p>

## 📌 Overview

**snab_budget** is a comprehensive budget management app built with Flutter. It helps individuals and families track income, expenses, debts, and savings, with powerful analytics, multi-currency support, PDF export, and notifications.

## 🚀 Tech Stack

- **Flutter** (Cross-platform UI Framework)
- **Provider** (State Management)
- **Firebase** (Authentication, Firestore, Cloud Messaging)
- **PDF Generation**
- **Image Processing**
- **Local Storage** (SQLite/Shared Preferences)

## 🔑 Key Features

- ✅ **Dashboard**: Overview of balances, income, and expenses
- ✅ **Multi-Account Support**: Track multiple accounts and categories
- ✅ **Expense & Income Tracking**: Add, edit, and categorize transactions
- ✅ **Budgets**: Set monthly/yearly budgets and monitor progress
- ✅ **Debt Management**: Track creditors and debtors
- ✅ **Analytics**: Visual charts and summaries
- ✅ **PDF Export**: Export reports and summaries
- ✅ **Notifications**: Reminders for bills, budgets, and more
- ✅ **Multi-Currency**: Choose and update your preferred currency
- ✅ **User Profiles**: Manage user info and settings
- ✅ **Cloud Sync**: Sync data with Firebase
- ✅ **Dark/Light Theme**

## 📸 Banners

<div align="center">
  <img src="screenshots/budget.png" alt="Budget Banner" width="300"/>
  <img src="screenshots/contrib_ss.png" alt="Web Contribution Banner" width="300"/>
</div>

## 📸 Screenshots

<div align="center">
  <img src="screenshots/splash.png" alt="Splash Screen" width="180"/>
  <img src="screenshots/login.png" alt="Login Screen" width="180"/>
  <img src="screenshots/signup.png" alt="Signup Screen" width="180"/>
  <img src="screenshots/dashboard.png" alt="Dashboard" width="180"/>
  <img src="screenshots/add_income.png" alt="Add Income" width="180"/>
  <img src="screenshots/Transactions(Daily).png" alt="Daily Transactions" width="180"/>
  <img src="screenshots/Transactions(montly).png" alt="Monthly Transactions" width="180"/>
  <img src="screenshots\Summary_fuilter.png" alt="Summary" width="180"/>
  <img src="screenshots/CREATE_PDF_REPORT.png" alt="PDF Report" width="180"/>
  <img src="screenshots/setting.png" alt="Settings" width="180"/>
  <img src="screenshots/profile.png" alt="Profile" width="180"/>
</div>

<summary><b>📱 Complete Screenshots</b></summary>

<div align="center">
  <img src="screenshots/basic_setting.png" width="180"/>
  <img src="screenshots/budget_monthly.png" width="180"/>
  <img src="screenshots/budget_yearly.png" width="180"/>
  <img src="screenshots/chaneg_email.png" width="180"/>
  <img src="screenshots/change_name.png" width="180"/>
  <img src="screenshots/choose_theme.png" width="180"/>
  <img src="screenshots/Choose_Your_Currency.png" width="180"/>
  <img src="screenshots/Choose_Your_Language.png" width="180"/>
  <img src="screenshots/confirm_Deletion.png" width="180"/>
  <img src="screenshots/daily_staties_drawer.png" width="180"/>
  <img src="screenshots/dashboard_drawer.png" width="180"/>
  <img src="screenshots/delete_all_data.png" width="180"/>
  <img src="screenshots/Depts.png" width="180"/>
  <img src="screenshots/Depts(Debit).png" width="180"/>
  <img src="screenshots/forget.png" width="180"/>
  <img src="screenshots/New_Creditor.png" width="180"/>
  <img src="screenshots/New_Deptor.png" width="180"/>
  <img src="screenshots/Notifications.png" width="180"/>
  <img src="screenshots/PDF_page.png" width="180"/>
  <img src="screenshots/PDF_page1.png" width="180"/>
  <img src="screenshots/PDF_page2.png" width="180"/>
  <img src="screenshots/PDF_page3.png" width="180"/>
  <img src="screenshots/profile_menu.png" width="180"/>
  <img src="screenshots/Scheduled_Transactions.png" width="180"/>
  <img src="screenshots/seect_cloude_space.png" width="180"/>
  <img src="screenshots/select_date.png" width="180"/>
  <img src="screenshots/Select_Image.png" width="180"/>
  <img src="screenshots/setting.png" width="180"/>
  <img src="screenshots/summary.png" width="180"/>
  <img src="screenshots/summary(with_graph).png" width="180"/>
  <img src="screenshots/Summary_fuilter.png" width="180"/>
  <img src="screenshots/Summary_fuilter(dept).png" width="180"/>
  <img src="screenshots/Summary(all).png" width="180"/>
  <img src="screenshots/Total_Balance.png" width="180"/>
  <img src="screenshots/Transaction_Details.png" width="180"/>
  <img src="screenshots/Transfer_Money.png" width="180"/>
  <img src="screenshots/walkscreen.png" width="180"/>
  <img src="screenshots/walkscreen1.png" width="180"/>
  <img src="screenshots/walkscreen2.png" width="180"/>
</div>


## 📁 Project Structure

```
lib/
├── clipper/                # Custom clippers
├── controller/             # State management providers
├── models/                 # Data models
├── Screens/                # UI screens (accounts, budget, dashboard, etc.)
├── utils/                  # Utility widgets and helpers
├── main.dart               # App entry point
```

## 📱 Download APK

You can download the latest APKs from the [APK folder](APK/) or use the links below:
- [app-arm64-v8a-release.apk](APK/app-arm64-v8a-release.apk)
- [app-armeabi-v7a-release.apk](APK/app-armeabi-v7a-release.apk)
- [app-x86_64-release.apk](APK/app-x86_64-release.apk)

## 🔧 Configuration

### Firebase Setup
1. Create a new Firebase project
2. Enable Authentication, Firestore, and Cloud Messaging
3. Download `google-services.json` and place it in `android/app/`

### Environment Variables
If needed, create a `.env` file in the root directory with your Firebase configuration:
```
FIREBASE_API_KEY=your_api_key
FIREBASE_PROJECT_ID=your_project_id
FIREBASE_MESSAGING_SENDER_ID=your_sender_id
FIREBASE_APP_ID=your_app_id
```

## 🚀 Features Overview

- **Multi-Account & Category Support**
- **Budgeting & Analytics**
- **Debt Tracking**
- **PDF Export**
- **Notifications**
- **Multi-Currency**
- **User Profiles**
- **Cloud Sync**
- **Dark/Light Theme**

## 👥 Contributors

<div align="center">
  <h3>Project Contributors</h3>
</div>

<table align="center">
  <tr>
    <td align="center">
      <img src="screenshots/contribution/usmandevx.jpeg" width="100px;" alt="usmandevx"/>
      <br />
      <sub><b>Muhammad Usman</b></sub>
    </td>
    <td align="center">
      <img src="screenshots/contribution/jamalihassan0307.jpeg" width="100px;" alt="jamalihassan0307"/>
      <br />
      <sub><b>ALI HASSAN</b></sub>
    </td>
    <td align="center">
      <img src="screenshots/contribution/muhammadarslanapax.jpeg" width="100px;" alt="muhammadarslanapax"/>
      <br />
      <sub><b>Muhammad Arslan</b></sub>
    </td>
    <td align="center">
      <img src="screenshots/contribution/MoheebTech.jpeg" width="100px;" alt="MoheebTech"/>
      <br />
      <sub><b>Muhammad Moheeb</b></sub>
    </td>
  </tr>
</table>

<div align="center">
  <h4>🌟 Special Thanks to All Contributors 🌟</h4>
  <p>This project wouldn't be possible without the dedication and expertise of our amazing team.</p>
</div>

---

<p align="center">
   Made with ❤️ by the 7 Skies solution Team using Flutter and Firebase
</p>
