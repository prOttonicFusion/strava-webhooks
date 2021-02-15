# Strava Webhooks
Test Strava API webhooks using ngrok

## Setup
1. Install dependencies:
    ```
    npm i
    ```
1. Sign up for a ngrok account and install the ngrok command line tool.
1. Get a authtoken (`MY_TOKEN`) from your ngrok dashboard and run
    ```
    ngrok authtoken MY_TOKEN
    ```

## Usage
1. Start this script using 
    ```
    npm run start
    ```
1. Open a new terminal tab and start ngrok at port 80 with 
    ```
    ngrok http 80
    ```

You can now use the url `https://<YOUR_NGROK_USERNAME>.ngrok.io/webhook` as the callback url for setting up a new Strava webhook subscription for testing purposes.

https://developers.strava.com/docs/webhookexample/
