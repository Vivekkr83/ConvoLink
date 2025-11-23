# ConvoLink

A Video Calling application. Replica of google Meet.

## About the project

This Project is like Gmeet where we can organise a meeting on a particular date and time, And this application will notify you by sending email on the account by which you have logged in, to join the Meet and in the meeting there will be a chatting option and also a whiteboard feature for all the participants.

## What I used

### Frontend

1. Tailwind.

2. Bootstrap.

### Backend

1. Google Authentication.

2. PeerJs for connecting to different IDs.

3. WebRTC to capture and optionally stream audio and/or video media.

## How to Set Up locally

1. Clone this repository to your local system.

2. Create a .env file in the project root and add your Google OAuth credentials:
    ```.env
    GOOGLE_CLIENT_ID=your_client_id
    GOOGLE_CLIENT_SECRET=your_client_secret
    ```


3. To install dependencies, in the terminal run the command:
    ```sh
    npm install
    ```

4. To start the server, run
    ```
    npm start
    ```
    The terminal will show
    ```
    Server is running on PORT 3000
    ```
    Now open your browser and visit: `localhost:3000`.
    Your app should now be running 🎉
