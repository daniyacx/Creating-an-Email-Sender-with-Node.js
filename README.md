# Node.js Email Sender

This is a simple Node.js application that enables users to send emails through a web-based contact form. It utilizes Express.js for routing, nodemailer for sending emails, and express-validator for server-side validation of form inputs.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Features

- Server-side form validation for name, email, subject, and message fields.
- Sends emails using nodemailer.
- Provides feedback to the user about the success or failure of sending an email.

## Prerequisites

Before running this application, ensure you have the following installed:

- [Node.js](https://nodejs.org) installed on your machine.
- A Gmail account for sending emails.

## Installation

1. Clone the repository:

    ```bash
    git clone (https://github.com/daniyacx/Creating-an-Email-Sender-with-Node.js)
    ```

2. Navigate to the project directory:

    ```bash
    cd node-email-sender
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

## Configuration

1. Set up Gmail credentials:

   - Open `app.js` file.
   - Replace `'aubakirovadania@gmail.com'` and `'ckllplhkfbqdtdin'` with your Gmail username and password respectively in the `transporter` object.

## Usage

1. Start the application:

    ```bash
    npm start
    ```

2. Open your web browser and navigate to `http://localhost:3000`.

3. Fill out the contact form with your name, email, subject, and message.

4. Click on the "Send Message" button to send the email.

5. You will receive feedback indicating whether the email was sent successfully or if there were any validation errors.

## License

This project is licensed under the [MIT License](LICENSE).
