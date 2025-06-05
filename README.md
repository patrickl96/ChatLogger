# Chat Logger (BakkesMod plugin)
Automatically save Rocket League chats to a local JSON file

Useful for anyone wanting to do data science on the RL chats they come across

Record the toxicity 🙃

## Features
- Easily enable/disable logging for different types of chats:
  
  <img src="https://i.imgur.com/uTcsPXm.png">

- Logs useful information about each chat:
  -  Player name
  -  Chat
  -  Date/time
  -  Chatter's relation to user (teammate/opponent/spectator/etc.)
  -  Chatter's platform (PlayStation/Xbox/Steam/Epic/etc.)
    
- Option to minify JSON files

- Clear chat logs with one press of a button

## Usage

Chats will be stored in the `Chat Logs` folder inside your BakkesMod `data` folder

### Toggle saving chats

<img src="https://i.imgur.com/wsouPJU.png">

  - If you happen to enable `Save chats` mid-match, this has the added benefit of also saving any chats that were sent *before* you toggled the setting (no chats are lost)
  - Enabling `Clear chats` effectively turns the plugin off, but you still keep the above benefit

## Installation

Install from the official [BakkesPlugins page](https://bakkesplugins.com/plugins/view/417)

or find the latest version in [Releases](https://github.com/sslow-dev/ChatLogger/releases)


>[!NOTE] 
>It can take while for the latest version of the plugin to show up on the BakkesPlugins page. So install from here if you need the latest version.

## View your saved chats!

This fork is simply to include an HTML page for a user-friendly chat viewer. For example, you want to share your in-game chats with friends or via Discord etc. Download the [chatlog_viewer.html file](https://github.com/patrickl96/ChatLogger/blob/main/chatlog_viewer.html) and you can visualise your chat logs intuitively
