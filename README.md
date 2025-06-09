Budget App
Welcome to Budget App, your personal financial companion designed to help you manage your money effectively, track your spending, set financial goals, and gain valuable insights into your financial habits.

How It Works
Budget App is a comprehensive Android application built with Kotlin and XML for the user interface. It leverages Google Firebase for backend services, ensuring secure user authentication and real-time data storage.

Here's a breakdown of its core functionalities:

1. User Authentication
Registration: New users can easily create an account using their email and password.

Login: Existing users can securely log in to access their personalized financial data.

2. Dashboard
Upon logging in, you're greeted with a intuitive dashboard that provides quick access to key features:

Quick Actions: Quickly navigate to frequently used functions like adding expenses, categories, setting goals, and viewing expenses.

More Options: Access additional features such as uploading receipts, viewing spending graphs, checking your rewards, and finding financial tips.

3. Expense Management
Add New Expense: A dedicated screen allows you to record new expenses. You can:

Select an expense category from a predefined list.

Enter the amount spent.

Add an optional description.

Select the date and time (start/end) via easy-to-use pickers.

Optionally, add a photo (e.g., a receipt) for record-keeping.

View Expenses: See a clear list of all your recorded expenses. The list is designed to be easily scrollable and informative. You can also pull down to refresh the list to ensure you have the latest data.

Includes an empty state view to guide you if you haven't added any expenses yet.

4. Goal Setting
Set Monthly Goals: Define your financial targets by setting both minimum and maximum spending goals for the month. This helps you stay within your budget and track your progress.

View Current Goals: Easily see your currently set minimum and maximum spending goals directly on the screen.

5. Reward Store
Earn Points: As you use the app and achieve financial milestones (e.g., sticking to your budget, adding expenses consistently), you can earn reward points.

Redeem Rewards: Browse through a list of available rewards and redeem your accumulated points for exciting incentives. Your current points balance is prominently displayed.

6. Financial Tips & Insights
Financial Literacy: Access a dedicated section providing valuable tips and insights on various financial literacy topics, such as budgeting, saving, debt management, and investing. These tips are presented in an easy-to-read card format.

Technical Overview
Platform: Android (Kotlin, XML)

Backend: Firebase Realtime Database for storing user data, expenses, categories, goals, and rewards.

Authentication: Firebase Authentication for secure user sign-up and login.

UI/UX: Adheres to Material Design principles, providing a clean, intuitive, and modern user interface across all screens, with adaptive layouts for various device sizes.

Setup and Installation
To run this application, you'll need:

Android Studio: The official IDE for Android development.

Firebase Project: A Google Firebase project set up with:

Authentication: Email/Password method enabled.

Realtime Database: Configured for your data.

google-services.json: Downloaded and placed in your app/ module directory.

Dependencies: Ensure you have the necessary Material Design, Firebase, and other AndroidX libraries configured in your build.gradle files.

Once the project is set up in Android Studio and connected to Firebase, you can build and run the application on an emulator or a physical Android device.
