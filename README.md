# CS-312-MiniProject-2: Cocktail Recipe Website

This is a web application built with Node.js, Express.js, Axios, and EJS that fetches and displays random cocktail recipes from the CocktailDB API. The app is styled with Bootstrap and custom CSS for a responsive design.

## Features
- Displays a random cocktail with name, image, ingredients, and instructions.
- Handles API errors with a user-friendly error page.
- Responsive design for desktop and mobile devices.

## Setup
1. Clone the repository: `git clone https://github.com/kgaffney/CS-312-MiniProject-2.git`
2. Navigate to the directory: `cd CS-312-MiniProject-2`
3. Install dependencies: `npm install`
4. Start the server: `npm start`
5. Visit `http://localhost:3000` in your browser.

## Files
- `app.js`: Main server file with Express routes and API integration.
- `public/styles.css`: Custom CSS for styling.
- `views/index.ejs`: Homepage template.
- `views/error.ejs`: Error page template.
- `package.json`: Project dependencies and scripts.

## Challenges
- Fixed `npm start` error by adding "start" script to `package.json`.
- Resolved `not a git repository` error with `git init`.
- Fixed Git remote typo (`orgin` to `origin`).
- Ensured responsive design using Bootstrap and media queries.
- Handled API errors with a dedicated error page.
