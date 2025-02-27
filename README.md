# Bankist App

This project is a simulation of a basic online banking application, Bankist. It allows users to log in, view their account balance and transaction history, transfer funds, request loans, and close their accounts.

## Features

* **User Authentication:** Secure login system with username and PIN verification.
* **Account Overview:** Displays the current account balance, income, expenses, and interest.
* **Transaction History:** Shows a list of all transactions with dates, amounts, and types (deposit/withdrawal).
* **Fund Transfers:** Allows users to transfer funds between accounts.
* **Loan Requests:** Enables users to request loans based on their account history.
* **Account Closure:** Provides functionality to close user accounts.
* **Sorting Transactions:** Users can sort their transactions in ascending or descending order.
* **Date Formatting:** Transactions and login dates are formatted based on the user's locale.
* **Currency Formatting:** Account balances and transaction amounts are formatted according to the user's currency and locale.
* **Logout Timer:** Automatically logs out users after a period of inactivity.

## Technologies Used

* **HTML:** For the structure of the application.
* **CSS:** For styling the application.
* **JavaScript:** For the application logic and functionality.
* **Intl API:** For internationalization features (date and currency formatting).

## How to Use

1.  **Open the Application:** Open the `index.html` file in your web browser.
2.  **Login:** Enter the username and PIN for one of the provided accounts:
    * **Account 1:**
        * Username: `js`
        * PIN: `1111`
    * **Account 2:**
        * Username: `jd`
        * PIN: `2222`
3.  **Explore:** Use the various features of the application, such as viewing transactions, transferring funds, or requesting a loan.

## Account Data

The application uses the following account data:

* **Account 1 (Jonas Schmedtmann):**
    * Currency: EUR
    * Locale: pt-PT
* **Account 2 (Jessica Davis):**
    * Currency: USD
    * Locale: en-US

## Functionality Details

* **Usernames:** Usernames are generated from the account owner's name (e.g., "Jonas Schmedtmann" becomes "js").
* **Transaction Dates:** Transaction dates are stored and displayed in a user-friendly format.
* **Loan Requests:** Loans are granted if the user has at least one deposit that is 10% or more of the requested loan amount.
* **Logout Timer:** The application automatically logs out users after 2 minutes of inactivity.

## Notes

* This is a simplified banking application for educational purposes.
* The application uses local data and does not interact with a real banking system.
* The data and functionality are implemented using JavaScript and the DOM.
