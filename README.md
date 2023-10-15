# Form Validation and Password Retrieval

This is a simple web application that demonstrates form validation for username and password fields. It also includes a "Remember Me" feature that stores user details in local storage and allows for password retrieval.

## Features

- **Username Validation**: The username must start with an uppercase letter, contain at least 8 characters, and include at least one special character or number.

- **Password Validation**: The password must contain at least 8 characters, one special character, and one number.

- **Remember Me**: If the "Remember Me" checkbox is checked during login, the user's details are stored in local storage.

- **Password Retrieval**: Users can retrieve their password by entering their username, but only if "Remember Me" was checked during the initial login.

- **Clear Data and Reload**: The "Cancel" button clears form data and reloads the page.

## Usage

1. **Username and Password Entry**:
   - Enter a username and password in the respective input fields.
   - Click the "Login" button to submit the form.
   - Check the "Remember Me" checkbox to remember your login details.

2. **Password Retrieval**:
   - Click on "Forgot Password?" to initiate the password retrieval process.
   - Enter your username in the new popup window.

3. **Clear Data and Reload**:
   - Click the "Cancel" button on the main UI to clear form data and reload the page.

## Local Storage

User login details and remembered usernames are stored in local storage. If you need to reset the stored data, you can clear your browser's local storage.

## Technologies Used

- HTML
- CSS
- JavaScript

## Contributions

Contributions to this project are welcome! Feel free to open issues and pull requests.
