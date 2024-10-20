# Sales Management Web Application

## Project Overview

This project is a simple web application that allows users to record daily sales, view sales statistics, and generate reports. It also includes basic user authentication (login/signup). The project is developed under the **Industry Innovation and Infrastructure** theme and includes encryption mechanisms for securing sensitive user data.

## Features

- **User Authentication**: Login and signup functionality for users.
- **Record Sales**: Users can log daily sales with the item name, quantity, and price.
- **Sales Statistics**: Users can view sales summaries and statistics over time.
- **Generate Reports**: Users can generate and download simple reports of their sales data.
- **Profile Settings**: Users can update their profile information and change their password.

## Pages

### 1. Login Page (`login.html`)
- **Purpose**: This page allows users to log in to their accounts. It includes fields for the user's email and password.
- **Functionality**: 
    - Users enter their credentials and submit the form to access their dashboard.
    - A link is provided to redirect new users to the signup page.

### 2. Signup Page (`signup.html`)
- **Purpose**: This page enables new users to create an account by providing their email and password.
- **Functionality**: 
    - Users enter their email and password to create an account.
    - After successful signup, users are redirected to the login page.

### 3. Dashboard Page (`dashboard.html`)
- **Purpose**: The dashboard serves as the home page after login, providing a summary of sales statistics.
- **Functionality**:
    - Displays a quick summary of sales for the current day (total sales, number of items sold).
    - Navigation links to other sections like recording sales, viewing statistics, generating reports, and updating profile information.

### 4. Record Sales Page (`record-sales.html`)
- **Purpose**: This page allows users to record new sales transactions.
- **Functionality**:
    - Users can input the item name, quantity sold, and price per item.
    - After submitting the form, the sale is saved in the database.

### 5. Sales Statistics Page (`statistics.html`)
- **Purpose**: This page displays visual representations of the user's sales data.
- **Functionality**:
    - Users can select a time period (daily, weekly, or monthly) to view sales trends.
    - A chart (implemented using Chart.js) is displayed to show sales statistics.
    - The chart provides insights into sales performance over time.

### 6. Generate Reports Page (`reports.html`)
- **Purpose**: This page allows users to generate sales reports based on a selected time period.
- **Functionality**:
    - Users can choose to generate daily, weekly, or monthly reports.
    - Reports can be downloaded as PDF files for offline viewing.

### 7. Profile Page (`profile.html`)
- **Purpose**: This page allows users to manage their profile information, including updating their email and changing their password.
- **Functionality**:
    - Users can edit their email address and change their password.
    - Any changes made are saved to the user's account.

## Encryption

Sensitive user data (such as passwords) is encrypted using the **Simplified DES (S-DES)** algorithm to ensure data privacy and security. This encryption is applied before storing data in the database.

## File Structure

- `login.html`: Login page.
- `signup.html`: Signup page.
- `dashboard.html`: User dashboard with navigation.
- `record-sales.html`: Page for recording new sales transactions.
- `statistics.html`: Page for viewing sales statistics with charts.
- `reports.html`: Page for generating and downloading sales reports.
- `profile.html`: Page for updating user profile information.
- `styles.css`: CSS file for styling the web pages.
- `README.md`: This documentation file.

## How to Run

1. Clone or download the project to your local machine.
2. Open the project folder and run the application using a web server or open the `.html` files directly in a browser.
3. Navigate between pages using the links provided on the dashboard.

## Future Improvements

- Implement a real database to store user data and sales information.
- Add more advanced features like filtering statistics, exporting data in different formats, and detailed user roles.
- Improve the encryption technique or introduce more secure options like AES.
