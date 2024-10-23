Discord Selfbot
A powerful Discord selfbot that lets you automate interactions in Discord with added functionality using the YouTube API.

Prerequisites
To use this selfbot, you'll need the following:

Node.js installed on your system
Discord Token (for selfbot authorization)
YouTube API Key (for YouTube-related commands)
Setup Instructions
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/selfbot.git
cd selfbot
Install Dependencies: After cloning the repository, install the required npm packages listed in index.mjs:

bash
Copy code
npm install
Create settings.json File: Create a settings.json file in the root of the project folder. The structure of the file should look like this:

json
Copy code
{
   "token": "your-discord-token",
   "youtubeApiKey": "your-youtube-api-key"
}
How to Get Your Discord Token
Note: Using a selfbot on Discord is against Discord's Terms of Service. Proceed at your own risk.

Open your browser and go to the Discord website.
Log in to your account.
Press Ctrl+Shift+I to open the Developer Tools (or right-click and choose "Inspect").
Go to the Network tab.
In Discord, press Ctrl+R to reload the page.
Look for a request named applications, library, or messages. Click on it.
In the Headers tab of the request, scroll down until you find the Authorization field.
Copy the value after Authorization. This is your Discord token.
How to Get a YouTube API Key
To interact with YouTube’s API, you need to generate an API key. Here's how:

Go to the Google Cloud Console.
Create a new project (or select an existing project).
From the left-hand menu, go to APIs & Services and click Library.
Search for "YouTube Data API v3" and enable it for your project.
Go to APIs & Services > Credentials.
Click on Create Credentials and choose API Key.
Copy the generated API key.
Usage
Once you have the required token and API key, you can start the bot by running:

bash
Copy code
node index.mjs
Features
Custom automation for Discord interactions.
YouTube API integration for commands related to videos or music.
Disclaimer
Using selfbots on Discord violates Discord's Terms of Service. This project is for educational purposes only. By using this code, you accept full responsibility for any actions taken with this bot.
