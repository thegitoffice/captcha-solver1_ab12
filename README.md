# Github User Info

## Description
This HTML application allows users to input a GitHub username and an optional token to retrieve the account creation date of the specified user.

## Features
- Input field for GitHub username
- Optional input field for token
- Button to fetch and display account creation date
- Error handling for failed data retrieval
- Caching of last successful lookup in localStorage
- Form repopulation on page load based on cached data

## Round 2 Updates
- Cached data from the last successful lookup is stored in localStorage under 'github-user-${seed}'
- The form is repopulated on page load with the cached username and token data

## Installation
Simply open the HTML file in a web browser to run the application.

## Usage
1. Enter the GitHub username in the designated field.
2. Optionally, provide a token in the corresponding field.
3. Click on the "Get Account Creation Date" button to retrieve and display the account creation date.

## Technologies Used
- Bootstrap v5.1.3 (https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css)
- Bootstrap JS Bundle v5.1.3 (https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js)

## License
MIT