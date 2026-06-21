# 💰 MyDuit - Personal Finance Tracker

[![Flutter](https://img.shields.io/badge/Flutter-3.41.0-blue?logo=flutter)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.11.0-blue?logo=dart)](https://dart.dev)
[![Firebase](https://img.shields.io/badge/Firebase-Latest-orange?logo=firebase)](https://firebase.google.com)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

**MyDuit** is a personal finance tracking application built with Flutter. It helps you manage your income and expenses effortlessly with a clean, modern interface and AI-powered assistance.

<p align="center">
  <img src="https://via.placeholder.com/800x400/0B646A/FFFFFF?text=MyDuit+Screenshot" alt="MyDuit App Screenshot" width="800">
</p>

---

## ✨ Features

### 📱 Core Features
- **Transaction Management** - Add, edit, and delete income/expense transactions
- **Asset Management** - Track your money across multiple assets (Bank, E-Wallet, Cash)
- **AI Assistant** - Powered by Cerebras AI to help you:
  - Record transactions via natural language
  - Analyze spending patterns
  - Get personalized financial advice
- **Beautiful Charts** - Visualize your income vs expense with interactive line charts
- **Category Breakdown** - See where your money goes with category analysis

### 🔐 Authentication & Data
- **Google Sign-In** - Secure authentication with Firebase
- **Cloud Sync** - Backup and restore your data across devices via Firestore
- **Local Storage** - All data stored locally with Hive for offline access
- **Multi-account Support** - Each user has their own isolated data

### 📊 Reporting & Export
- **Export to Excel** - Export your transactions and assets to `.xlsx` files
- **Export to PDF** - Generate beautiful financial reports with charts and summaries
- **Import from Excel** - Restore your data from Excel backups

### ⏰ Smart Features
- **Daily Reminder** - Get notified daily to record your transactions
- **Last Sync Date** - Track when you last backed up your data
- **Dark/Light Mode** - Choose your preferred theme
- **Color Palette** - Customize the app with your favorite accent color

### 🎨 UI/UX
- **Modern Design** - Clean, minimal, and intuitive interface
- **Responsive** - Works smoothly on all screen sizes
- **Smooth Animations** - Delightful micro-interactions
- **Grouped Transactions** - Transactions organized by date for better readability

---

## 🚀 Tech Stack

| Category | Technology |
|----------|------------|
| **Framework** | Flutter 3.41.0 |
| **Language** | Dart 3.11.0 |
| **State Management** | Provider |
| **Local Database** | Hive + SharedPreferences |
| **Authentication** | Firebase Auth (Google Sign-In) |
| **Cloud Storage** | Cloud Firestore |
| **AI Integration** | Cerebras API (gpt-oss-120b) |
| **Charts** | FL Chart |
| **PDF Generation** | pdf + printing |
| **Excel Export** | excel |
| **Notifications** | flutter_local_notifications |

---

## 📸 Screenshots

| Home Dashboard | Transactions | AI Assistant | Statistics |
|----------------|--------------|--------------|------------|
| ![Home](https://via.placeholder.com/200x400/0B646A/FFFFFF?text=Home) | ![Transactions](https://via.placeholder.com/200x400/14A3AD/FFFFFF?text=Transactions) | ![AI](https://via.placeholder.com/200x400/052F32/FFFFFF?text=AI) | ![Stats](https://via.placeholder.com/200x400/1A2D2F/FFFFFF?text=Stats) |

---
