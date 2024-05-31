# Admin Panel Application

## Overview

This project is a web-based admin panel application built with React. It is designed to provide different levels of access to users based on their roles (admin and regular users). The admin users have additional functionalities such as viewing all users, managing user roles, and performing transactions.

## Technologies Used

- **React JS**: Frontend.
- **Firebase**: Authentication and Database.
- **FontAwesome**: UI Icons.
- **Bootstrap**: Responsive Layouts.
- **CSS**: Custom styling.

## Features

1. **User Authentication**:
   - Login functionality using Firebase Authentication.
   - Display user-specific content based on their role.

2. **Role-Based Access Control**:
   - Admin users can access all functionalities.
   - Regular users have limited access.

3. **Responsive Design**:
   - Sidebar navigation for desktop screens.
   - Hamburger menu for mobile screens.
   - Mobile navigation that slides in from the right.

4. **User Management**:
   - Admin can view all users.
   - Manage activated and deactivated users.
   - Admin profile management.
   - Add transactions (Admin feature).

## Project Structure

- **src/components**: Contains all the React components.
  - `Sidebar.js`: Sidebar navigation component for desktop.
  - `MobileNav.js`: Sidebar navigation component for mobile.
  - `GetAdmin.js`: Main admin panel component.
  - `NotAdmin.js`: Component for non-admin users.

- **src/components/users**: Contains all the components for logged in admin users.
   - `AllUsers.js`: Contains a list of all the registered users.
   - `UserInfo.js`: This renders information about a selected user.
   - `AddTransactions.js`: Handles the process to add new transactions for users.
   - `TransactionLog.js`: This displays all the log for the transactions with an edit and delete option.


- **src/firebase.js**: Firebase configuration and initialization.
- **src/App.css**: Custom CSS for styling the application.

## Getting Started

### Prerequisites

- Node.js

- Install all dependencies `npm install`

- Start project `npm start`

### Usage
- Login: Enter your email and password to log in. Only admin users have access to the full admin panel.

- Navigation: Use the sidebar on desktop or the hamburger menu on mobile to navigate through the admin functionalities.

- Logout: Click the logout button to sign out from the application.

- Add firebase information to connect to your project.
- Edit user information and transactions.

## Future Upgrades
- Different Currencies.
- Upgrading to Blaze Plan to deploy functions for proper admin usage.
- Nested Admin functions.
