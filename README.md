# Express.js Backend Project

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Environment Variables](#environment-variables)

## Introduction
This project is a backend service built using [Express.js](https://expressjs.com/). It provides a set of RESTful APIs for handling various tasks such as user authentication, data management, and more.

## Prerequisites
- Node.js (>= 14.x)
- npm (>= 6.x) or yarn

## Usage
1. Clone the repository:
   \```sh
   git clone https://github.com/DaniilShamanov/KiwiAnimationBackend.git
   cd KiwiAnimationBackend
   \```

2. Install dependencies:
   \```sh
   npm install
   # or
   yarn install
   \```

3. Set up environment variables:
   Create a `.env` file in the root directory and add the necessary environment variables. Refer to the [Environment Variables](#environment-variables) section for more details.

4. Start the development server:
   \```sh
   npm run dev
   # or
   yarn dev
   \```

## Environment Variables
The following environment variables are required to run the project:

- `PORT` - Port number for the server (default: 5000)
- `TWILIO_ACCOUNT_SID` - Twilio account SID 
- `TWILIO_AUTH_TOKEN` - Twilio authorization token
- `TWILIO_SERVICE_SID` - Twilio Verify service id
- `NODEMAILER_EMAIL` - Email which will be used for sending emails
- `NODEMAILER_EMAIL_PASS` - Email service pass
- `NODEMAILER_PORT` - Port number for nodemailer (default: 587)
- `NODEMAILER_TARGET_EMAIL` - Email which will receive emails