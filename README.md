# Secret Sharing App (Live at [Secret Sharing App](https://secret-sharing-app.onrender.com)

This is a web application that demonstrates user authentication using Passport.js, an authentication middleware for Node.js. The application allows users to register, log in, and access a secrets page if authenticated. It also provides an option to authenticate using a Google account.

## Technologies Used

The application is built using the following technologies and frameworks:

- **Node.js**: A JavaScript runtime environment for server-side development.
- **Express.js**: A web application framework for Node.js that provides a robust set of features for building web applications and APIs.
- **PostgreSQL**: A powerful, open-source relational database used for storing user information, authentication data, and application secrets.
- **node-postgres (pg)**: A PostgreSQL client for Node.js that enables efficient querying and interaction with the database.
- **EJS (Embedded JavaScript)**: A templating engine used for generating dynamic HTML content on the server side.
- **Passport.js**: An authentication middleware for Node.js that provides a flexible and modular authentication system, supporting strategies such as local authentication and OAuth.
- **passport-local**: A Passport.js strategy for handling username and password authentication.
- **passport-google-oauth20**: A Passport.js strategy for authenticating users via Google using OAuth 2.0.
- **express-session**: A middleware for managing user sessions and maintaining authentication state across requests.
- **dotenv**: A module for securely loading environment variables from a `.env` file into `process.env`.
- **body-parser**: A middleware for parsing incoming request bodies in Express.js (now built into Express but still commonly referenced).


## Functionality

The application provides the following functionality:

1. Home Page ("/"): Serves as the landing page for the application.

2. Registration Page ("/register"): Allows users to register for a new account by providing a username and password.

3. Login Page ("/login"): Allows registered users to log in using their username and password.

4. Google Authentication: Provides the option to authenticate using a Google account by clicking the "Sign in with Google" button on the login page. This feature utilizes Google OAuth 2.0.

5. Secrets Page ("/secrets"): A protected route accessible only to authenticated users. If a user is not logged in, they will be redirected to the login page.

6. Logout ("/logout"): Allows users to log out of their accounts.

## Security Enhancements (Branches)

The project was built enhancing the security sequentially showcasing different security enhancements made to the application. These are:

1. `encryption`: Demonstrates the use of encryption techniques to secure sensitive user information.

2. `Password_Hashing`: Showcases password hashing, a secure method for storing and comparing passwords.

3. `Salting`: Demonstrates the use of password salting, an additional security measure for password hashing.

4. `Cookies_and_Session`: Introduces the use of cookies and sessions to enhance the user authentication process. This branch is live and hosted on for reviewing purposes.


## Repository

The app's source code and branches can be found on the GitHub repository at [`Secret_Sharing`](https://github.com/Han9128/Secret_Sharing-App/tree/master). Feel free to explore the different branches to review the security enhancements and implementation details.

## Live Demo

For a live demonstration of the app with the latest security enhancements, you can visit [Secret Sharing App](https://secret-sharing-app.onrender.com)

Please note that this is a demo environment, and it may not be suitable for production use.
