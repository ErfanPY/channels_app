#  - Chat app
[![GitHub Stars](https://img.shields.io/github/stars/ErfanPY/channels_app.svg)](https://github.com/ErfanPY/channels_app/stargazers) [![GitHub Issues](https://img.shields.io/github/issues/ErfanPY/channels_app.svg)](https://github.com/ErfanPY/channels_app/issues)
<!-- [![Live Demo](https://img.shields.io/badge/demo-online-green.svg)](https://igorantun.com/chat) -->

Simple chat app created by django channels, that "will" provides the main functions you'd expect from a chat, such as emojis, private messages, an admin system, etc..

<!-- What was your motivation?\
Why did you build this project?\
What problem does it solve?\
What did you learn?\
What makes your project stand out? If your project has a lot of features, consider adding a "Features"  section and listing them here.\ -->

## Technologies
---
Project is created with:
* Django version: 3.2.9
* Channels version: 3.0.4

## Features
---
* Group chat
* Real-time communication with WebSocket

## Install
---
   ```sh
   git clone https://github.com/ErfanPY/channels_app.git
   cd channels_app
   pip install -r requirements.txt
   ```

## Usage
---
   ```sh
   cd chatproj
   python3 manage.py runserver
   ```

<!-- Add some images -->

## TODO
---
 - [X] Group chat
 - [ ] Authentication
 - [ ] Chats list
 - [ ] Front-end for group chat
 - [ ] Emoji support
 - [ ] User @mentioning
 - [ ] Private messaging
 - [ ] Message deleting (for admins)
 - [ ] Ability to kick/ban users (for admins)
 - [ ] See other user's IPs (for admins)