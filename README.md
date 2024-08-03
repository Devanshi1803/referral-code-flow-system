# referral-code-flow-system
A web application designed to manage user registrations, referral rewards, and authentication using React, Node.js, and PostgreSQL. This system supports user sign-up via Twitter OAuth and MetaMask wallet connect, validates referral codes, and allocates points to referrers.

## Features
- **User Registration**: Sign up using Twitter OAuth or MetaMask wallet connect.
- **Referral Codes**: Enter and validate referral codes to award points to referrers.
- **Dashboard Access**: Navigate between the home page and user dashboard post-authentication.
- **Token Management**: Handles access and refresh tokens securely.
- **Notifications**: Displays toast messages for success and error feedback.

## Technologies
- **Frontend**: React
- **Backend**: Node.js
- **Database**: MongoDB or PostgreSQL
- **Authentication**: Twitter OAuth, MetaMask

## Getting Started

### Prerequisites
- Node.js and npm installed on your machine.
- MongoDB or PostgreSQL database setup.

### Frontend Setup
1. Navigate to the `frontend` directory:
    ```bash
    cd frontend
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Start the development server:
    ```bash
    npm start
    ```

### Backend Setup
1. Navigate to the `backend` directory:
    ```bash
    cd backend
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Start the server:
    ```bash
    npm start
    ```

### Database Setup
1. Refer to the `database/README.md` for schema setup and migration instructions.
