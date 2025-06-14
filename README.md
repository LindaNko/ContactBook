# Contacts Application

## Overview
This repository contains a simple web application for managing contacts. The application allows users to view, add, and refresh contact information.

## Features
- **View Contacts**: Displays a list of contacts with their avatars, first names, and last names.
- **Add Contact**: Provides a form to add new contacts.
- **Refresh Contacts**: Refreshes the list of contacts.

## Technologies Used
- HTML
- CSS
- JavaScript

## File Structure
- `index.html`: Main page for viewing and refreshing contacts.
- `add-contact.html`: Page for adding new contacts.
- `style.css`: Stylesheet for the application.
- `config.js`: Configuration file containing necessary constants like `rootPath` and `apiKey`.

## Usage

### Viewing Contacts
1. Open `index.html` in your browser.
2. Contacts will load automatically.
3. Click the "Refresh" button to reload the contacts.

### Adding Contacts
1. Open `add-contact.html` in your browser.
2. Fill out the form with the contact's details.
3. Click the "Submit" button to add the contact.
4. Click the "Home" button to return to the main page.

## JavaScript Functions

### `fetchContacts()`
Fetches the list of contacts from the server and displays them in a table.

### `displayOutput(data)`
Formats and displays the contact data in a table.

### `addContact()`
Navigates to the `add-contact.html` page.

### `submitForm(e)`
Submits the contact form data to the server and handles the response.

### `homeLink()`
Navigates back to the `index.html` page.

## Event Listeners
- `refresh`: Calls `fetchContacts()` to refresh the contact list.
- `addContact`: Calls `addContact()` to navigate to the add contact page.
- `submitForm`: Calls `submitForm(e)` to submit the contact form.
- `homeLink`: Calls `homeLink()` to navigate back to the main page.

## Setup
1. Clone the repository.
2. Ensure you have a server running that can handle the endpoints specified in `config.js`.
3. Open `index.html` and `add-contact.html` in your browser to use the application.

## License
This project is licensed under the MIT License.

## Contact
For any questions or issues, please contact [Your Name] at [Your Email].

