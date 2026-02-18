# Simple Node.js App for AWS EC2

This is a simple Node.js application using Express, designed to be deployed on an AWS EC2 instance.

## Running Locally

1.  Install dependencies:
    ```bash
    npm install
    ```
2.  Start the server:
    ```bash
    node index.js
    ```
3.  Open your browser and navigate to `http://localhost:3000`.

## Deployment

To deploy on AWS EC2:

1.  Launch an EC2 instance.
2.  SSH into the instance.
3.  Install Node.js and npm.
4.  Clone this repository or copy the files.
5.  Install dependencies (`npm install`).
6.  Start the server (`node index.js` or using a process manager like PM2).
