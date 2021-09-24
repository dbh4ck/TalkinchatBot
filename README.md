# TalkinchatBot
A Simple TypeScript to connect TalkinChat Group Bot using WebSocket

# Make Sure to RUN: "npm install" in project root directory in order to refresh packages required to run the bot.

- RUN Cmds: Please define the username and password for the bot in Client.ts file and execute below cmds step-wise: 
- tsc Client.ts
- node Client.js

# Requirements
- OS (Windows, Mac, Linux, Android, or any)
- NodeJs Installed
- Typescript Installed
- Dependencies (ws, youtube-search-without-api-key)
- Note: In order to run this NodeJs Bot from Android Device, you must install Termux from F-Droid.

# Features:

- Login using websocket
- Group Join
- Youtube Scrapping
- User Profile Search
- Send User Profile Image in Group
- Welcome & Spin Bot
- Admin, Member, Ban, Owner, None User in Group.
- Scrape Images from Google
- Text to Speech Make Bot Talk in Group


# List of Cmds:
- .s    -  SPIN the Bot
- m ID  -  Member ID
- k ID  -  Kick ID
- o ID  -  Owner ID
- a ID  -  Admin ID
- n ID  -  None ID
- b ID  -  Ban ID
- !yt keyword  -  Find relevant youtube video link
- !avi userId  -  Fetch User Avatar Pic
- !pro userId  -  Fetch User Profile
- !img keyword - Search Image From Google (by default. limited to 20 searches)
- !say message - Converts the given message to a Speech and send in group

# DB - b'cuz We Share :P
