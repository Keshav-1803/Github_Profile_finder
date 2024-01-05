# GitHub Account Finder

## Overview

This React project is a simple GitHub Account Finder, designed to fetch and display GitHub profiles based on the provided username or email. The application utilizes the GitHub API to retrieve user information and presents the results in a clean and user-friendly interface.

## Project Structure

The project structure is organized into components and follows a modular approach:

- **`App.js`**: The main component that handles user input, interacts with the GitHub API, and renders the search results.

- **`components/user-card/user-card.js`**: A reusable component responsible for displaying individual user cards with essential information.

## Usage

1. Enter a GitHub username or email in the search input field.
2. Click the "Search" button to initiate the search.
3. View the results displayed below the search form.

## Getting Started

To run the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/github-account-finder.git
   ```

2. Navigate to the project directory:

   ```bash
   cd github-account-finder
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Open your browser and visit `http://localhost:3000` to view the application.

## Dependencies

- `react`: JavaScript library for building user interfaces.
- `react-dom`: React package for working with the DOM.
- `react-scripts`: Configuration and scripts for Create React App.

## API Usage

The application uses the GitHub API to search for user accounts based on the provided query. The API endpoint used is:

```
https://api.github.com/search/users?q=${query}
```

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Thanks to GitHub for providing the GitHub API that powers this application.

Feel free to explore, contribute, and enhance the GitHub Account Finder! If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request.