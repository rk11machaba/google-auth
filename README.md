# Google OAuth Application

## Overview

This application demonstrates how to implement Google OAuth 2.0 authentication in a web application. It allows users to log in using their Google account, providing a secure and convenient way to authenticate users.

## Features

- Google OAuth 2.0 authentication
- Secure user login
- Access to basic user profile information

## Prerequisites

- Node.js installed
- A Google Cloud project with OAuth 2.0 credentials

## Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/google-auth.git
   cd google-auth
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Create a `.env` file in the root directory and add your Google OAuth credentials:
   ```
   GOOGLE_CLIENT_ID=your-client-id
   GOOGLE_CLIENT_SECRET=your-client-secret
   GOOGLE_CALLBACK_URL=http://localhost:3000/auth/google/callback
   ```

4. Start the application:
   ```sh
   npm start
   ```

5. Open your browser and navigate to `http://localhost:3000`.

## Usage

- Click on the "Login with Google" button to authenticate using your Google account.
- Upon successful authentication, you will be redirected to the home page with your profile information displayed.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact

For any questions or support, please contact [machabarotshidzwakaizer@gmail.com](machabarotshidzwakaizer@gmail.com).
