# Twitter-Api-Writeup
A write up of how I got the Twitter API to get data


# Twitter API v2 Node.js Example

This example demonstrates how to use the Twitter API v2 with Node.js. Follow the steps below to set up your environment and execute the code.

## Prerequisites

1. Install the latest version of Node.js:
   - For Windows, download the installer from the [official Node.js website](https://nodejs.org/en/download/).
   - For macOS and Linux, use the following command:
``` curl -fsSL https://install-node.now.sh | bash  ```

## Set Environment Variables

### Windows

1. Press `Win` + `X`, and choose "System".
2. Click "Advanced system settings".
3. Click "Environment Variables".
4. Under "User variables", click "New".
5. Enter the variable name as `CONSUMER_KEY`, and the value as your Twitter API Consumer Key.
6. Click "OK".
7. Repeat steps 4-6 for `CONSUMER_SECRET`, using your Twitter API Consumer Secret as the value.

### macOS and Linux

1. Open a terminal window.
2. Run the following commands, replacing `<your_consumer_key>` and `<your_consumer_secret>` with your Twitter API Consumer Key and Secret: ```export CONSUMER_KEY='<your_consumer_key>'
export CONSUMER_SECRET='<your_consumer_secret>'```


## Install Dependencies

1. Create a new directory and navigate to it in your terminal.
2. Run `npm init -y` to create a `package.json` file.
3. Install the required dependencies using the following command: ```npm install got crypto oauth-1.0a querystring readline```


## Run the Code

1. Save the provided code to a file named `twitter-api-v2.js` in the same directory as your `package.json`.
2. In your terminal, navigate to the directory containing `twitter-api-v2.js`.
3. Run the following command to execute the code: ```node --experimental-modules twitter-api-v2.js```


4. Follow the prompts to authorize the application and enter the provided PIN.

After successful execution, you should see the requested data printed to the console.
