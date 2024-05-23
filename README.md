# GitHub Tracker

Live Demo: [GitHub Tracker](https://git-track.vercel.app/))

## Description

GitHub Tracker is a web application that allows users to enter a GitHub username and retrieve information about the user's GitHub profile, such as total contributions, total repositories, and more. This project utilizes the GitHub API to fetch the data and display it in a user-friendly interface.

## Features

- **User Profile Information:** Retrieve and display GitHub user profile details such as name, bio, location, and avatar.
- **Total Contributions:** Display the total number of contributions made by the user.
- **Total Repositories:** Show the total number of public repositories.
- **Repository Details:** List the names and descriptions of the user's repositories.
- **Responsive Design:** The application is responsive and works well on different screen sizes.

## Files

- `index.html`: The main HTML file containing the structure of the application.
- `style.css`: The CSS file for styling the application.
- `app.js`: The JavaScript file containing the logic for fetching and displaying GitHub user data.

## How to Run

1. Clone the repository to your local machine using:
    ```bash
    git clone https://github.com/yourusername/github-tracker.git
    ```

2. Navigate to the project directory:
    ```bash
    cd github-tracker
    ```

3. Open the `index.html` file in your browser to use the application.

## Code Overview

### HTML

The HTML file contains the structure of the GitHub Tracker application, including the input field for the GitHub username and sections for displaying user information and repositories.

### CSS

The CSS file provides the styling for the application, ensuring a clean and user-friendly interface.

### JavaScript

The JavaScript file contains the logic for fetching data from the GitHub API and updating the DOM to display the retrieved information.

## Future Improvements

- Add more detailed statistics such as the most popular repositories, followers count, and following count.
- Implement pagination for repositories if the user has many repositories.
- Enhance error handling for invalid usernames or network issues.

## Contributing

Contributions are welcome! If you have any ideas for improvements or have found bugs, please create an issue or submit a pull request.
