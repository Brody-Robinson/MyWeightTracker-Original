# MyWeightTracker (Original)

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android%20Studio-green" alt="Platform">
  <img src="https://img.shields.io/badge/Database-SQLite-blue" alt="Database">
  <img src="https://img.shields.io/badge/Language-Java-orange" alt="Programming Language">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen" alt="Project Status">
</p>

<p align="center">
  MyWeightTracker is a user-friendly Android application designed to help users monitor and manage their weight effectively. It offers a seamless experience with features tailored to enhance user engagement and data tracking.
</p>

---

## 🚀 Overview

**MyWeightTracker** allows users to:
- **Record Daily Weight**: Keep track of your weight on a daily basis.
- **Manage User Profiles**: Create and personalize your user profile.
- **Set and Achieve Goals**: Receive notifications when you reach your weight goals.

### 🌟 Key Features
- **Daily Weight Tracking**: Easily log your daily weight and monitor your progress.
- **User Profile Management**: Customize your experience with personal profiles.
- **Goal Notifications**: Stay motivated with notifications upon reaching your weight goals.

## 🛠️ Technology Stack
- **Platform**: Android Studio
- **Database**: SQLite
- **Programming Language**: Java

## 💡 Artifact Description

This application was developed in Android Studio and serves as a practical demonstration of database management, user interface design, and notification handling in Android development. The original version of the app was created in 2023, with significant enhancements made to the SQLite database schema in July 2024.

### 📈 Key Enhancements
- **Database Management**: Added foreign key constraints to ensure data integrity, showcasing proficiency in relational database management.
- **CRUD Operations**: Updated DBHelper to handle complex data interactions with enhanced CRUD operations.
- **User Management**: Implemented sign-in functionality and profile management, demonstrating skills in user authentication and personalization.
- **Notifications**: Integrated Android’s notification system to send congratulatory messages when users achieve their weight goals.

## 🎯 Justification for Inclusion in ePortfolio

This project highlights:
- **Practical Application of Database Management**: Demonstrates the ability to manage relational databases and ensure data integrity.
- **User Interface Design**: Reflects the ability to create a user-friendly interface that enhances the user experience.
- **Notification Handling**: Shows proficiency in using Android’s notification system to engage users.

## 🔧 Improvements Included
- **DBHelper.java**:
  - Added `userId` as a foreign key in the `weightEntry` table.
  - Updated the `onUpgrade` method to add the foreign key in existing databases.
  - Modified methods to work with `userId` for adding and retrieving weight entries.

- **UserSessionManager.java**:
  - Added a new key `KEY_USER_ID` to store and retrieve the user's ID.
  - Updated `createUserSession` and `getUserId` methods to handle the user ID.

- **WeightEntry.java**:
  - Added a new field `userId` to represent the foreign key.
  - Updated constructors to include `userId`.

## 📚 Learning Outcomes
### What Was Learned:
- **Database Integrity**: Gained insights into the importance of foreign key constraints in maintaining data integrity.
- **Schema Management**: Improved skills in managing database schema changes and implementing upgrade strategies.
- **CRUD Operations**: Enhanced ability to handle relational data effectively.

### Challenges Faced:
- **Foreign Key Constraints**: Overcame challenges related to ensuring foreign key support in SQLite.
- **Database Upgrades**: Managed the complexity of implementing a database upgrade strategy without data loss.

## 📥 Installation

To run this project on your local machine:
1. Clone the repository: `git clone https://github.com/Brody-Robinson/MyWeightTracker-Original.git`
2. Open the project in Android Studio.
3. Build and run the project on an Android emulator or device.

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve this project.


---

<p align="center">
  <img src="https://img.shields.io/github/stars/Brody-Robinson/MyWeightTracker-Original?style=social" alt="GitHub Stars">
  <img src="https://img.shields.io/github/forks/Brody-Robinson/MyWeightTracker-Original?style=social" alt="GitHub Forks">
</p>
