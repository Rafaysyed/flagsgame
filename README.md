# Country Flags Game

This project is a fun and educational web-based game built using PostgreSQL and Express.js, where users test their knowledge of country flags. The game presents users with a random country flag, and they have to correctly identify the country by typing its name. The game records scores and tracks performance over time.

## Features
- **Random Flag Selection**: The game randomly selects a country flag from the database for each round.
- **Real-time Feedback**: Users receive immediate feedback on whether their answer is correct or not.
- **Score Tracking**: The application tracks the user's score and displays it at the end of each game session.
- **PostgreSQL Integration**: Flags and country data are stored in a PostgreSQL database for efficient querying.

## Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap (for responsive design)
- **Backend**: Node.js, Express.js (handling API and game logic)
- **Database**: PostgreSQL (storing country data and scores)
- **Version Control**: Git and GitHub for code management

## Installation and Setup
1. Clone the repository.
    ```bash
    git clone https://github.com/yourusername/country-flags-game.git
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Set up PostgreSQL database and configure environment variables for database connection.
4. Run the application:
    ```bash
    npm start
    ```
5. Access the game at `http://localhost:3000`.

## Future Enhancements
- Add multiple difficulty levels.
- Include country hints or additional information after a wrong answer.
- Expand flag dataset to include regions or historical flags.

Feel free to contribute by opening issues or submitting pull requests.
