💳 Wallet Pay

Wallet Pay is a robust, middle-level fintech application built with Flutter. Inspired by popular payment solutions, this project demonstrates scalable architecture, secure state management, and cloud-based transaction handling.

✨ Core Features

Secure Authentication: Phone number login via Firebase Auth (OTP).

Smart Dashboard: Real-time wallet balance and quick-action carousel.

P2P Transfers: Seamless money transfers between users by phone number.

Utility Payments: Mobile, internet, and utility bill payments with strict validation.

Transaction History: Detailed feed of past operations with status tracking.

🛠 Tech Stack & Architecture

This project strictly follows the Feature-First Architecture, ensuring that each domain of the app is isolated, testable, and scalable.

Framework: Flutter

State Management: flutter_bloc

Routing: go_router

Dependency Injection: get_it

Backend as a Service: Firebase (Auth, Cloud Firestore)

Folder Structure

lib/
├── core/               # Routing, DI, Theme, Network client, Constants
├── features/           # Isolated feature modules
│   ├── auth/           # Authentication UI & Logic
│   ├── dashboard/      # Main screen and balance display
│   └── transfers/      # P2P and utility payment logic
└── main.dart           # App entry point


🚀 Getting Started

Follow these steps to run the project locally.

Prerequisites

Flutter SDK installed (version 3.10+)

Firebase CLI installed

Installation

Clone the repository

git clone https://github.com/yourusername/wallet_pay.git
cd wallet_pay


Install dependencies

flutter pub get


Configure Firebase
Run the FlutterFire CLI to connect your Firebase project:

flutterfire configure


Run the App

flutter run


📱 Screenshots

(Placeholders for future UI screenshots)

Designed and developed as a portfolio showcase project.