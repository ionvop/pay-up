# pay-up
A simple payment tracking app

## Project Title: People Who Need to Pay Up

This project provides a simple web application to track individuals and their bills. Users can add people, record bills, and monitor payments by month.

### Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

### Features

- **Responsive Design**: The application is designed to work on various screen sizes using a mobile-first approach.
- **Monthly Tracking**: Users can select a month to view associated individuals and their bills.
- **Add/Remove People**: Easily add new individuals and their bills or remove them as needed.
- **Import/Export Functionality**: Import data from JSON files or export current data for backup.
- **Bill Tracking**: Track bill payments, including amounts paid and total bill amounts per person.

### Technologies Used

- **HTML**: Structure of the web application.
- **CSS**: Styling and layout of the application, using inline styles for simplicity.
- **JavaScript**: Functionality that enables interactive features, data management, and state persistence through Local Storage.
- **Service Worker**: Supports basic offline capabilities and improves performance.

### Usage

1. **Select a Month**: Use the dropdown to select a month.
2. **Add a Person**: Enter a person's name in the input field and click the add button.
3. **Manage Bills**: For each person, you can add bills, update payment amounts, and delete bills.
4. **Import/Export Data**: Click the import button to upload a JSON file, or export current data to a JSON file.