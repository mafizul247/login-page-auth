# Login registration Page with Authentication

This project implements a login and registration page with authentication and validation features.

## Features

- **Tailwind CSS**: For designing the user interface.
- **Firebase Authentication**: For handling user login and registration.
- **Password Validation**: Using regular expressions to ensure strong passwords.
- **Context API**: For state management across the application.
- **Private Routes**: To protect routes that require authentication.

## Technologies Used

- **Frontend**: React, Tailwind CSS
- **Backend**: Firebase Authentication
- **Routing and State Management**: React Router, Context API

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/mafizul247/login-page-auth.git
    ```
2. Navigate to the project directory:
    ```bash
    cd login-page-auth
    ```
3. Install dependencies:
    ```bash
    npm install
    ```

### Running the Application

1. Start the development server:
    ```bash
    npm start or npm run dev
    ```
2. Open your browser and navigate to `http://localhost:3000`.

## Deployment

The live version of this application is deployed on Netlify. You can access it [here](https://guileless-meringue-90f6e0.netlify.app/).

## Authentication

- **Firebase**: This project uses Firebase for user authentication. Make sure to set up your Firebase project and replace the Firebase configuration in the project with your own.

## CSS Framework

- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.

## Validation

- **Password Validation**: Passwords are validated using regular expressions to ensure they meet the required criteria (e.g., minimum length, uppercase letters, numbers, etc.).

## Usage

- **Login/Registration**: Users can register by providing their email and password. Once registered, they can log in with their credentials.
- **Protected Routes**: Certain routes are protected and can only be accessed by authenticated users. 


## Links

- **GitHub Repository**: [login-page-auth](https://github.com/mafizul247/login-page-auth)
- **Live Site**: [Netlify Deployment](https://guileless-meringue-90f6e0.netlify.app/)


