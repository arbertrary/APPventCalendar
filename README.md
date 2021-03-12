# AppventCalendar

A small Kotlin Android project in preparation of Christmas 2021.

Set to become a customized Advent Calendar for selected friends with login functionality and 24 custom doors for each of them.

Each door can contain:
- Notes by me
- Links to interesting/funny content
- Images
- ...


## Currently following

https://developer.android.com/codelabs/build-your-first-android-app-kotlin

# Usage

- User login
  - Custom Name (Name is associated to personalized "door" set)
  - Password? Should only needed ONCE after install; 
  - User needs to stay logged in else it's annoying
  - Option a) Preset Password by me.
  - Option b) User can set own password which gets hashed. How much more "difficult" would this be?
- 24 doors
  - Door can not be opened before date -> Message: "You tried to open before the day. This will get you on Santa's naughty list!" or something
  - Each person gets a different set of 24 doors
- Content:
  - Messages: Custom Text messages to the person
  - Images: Images that are packaged with the .apk and are shown on screen
  - Links: Links to be opened in a browser -> App needs to be able to open browser
- Reminder?
  - Should the app send a reminder each day? Is this too intrusive?

- Where should I store the .apk? Google Drive?

# Layout and design decisions

- Start page
  - Greeting and explanation
  - Login button
- Login page
- 24 Doors page: Scrollable grid of buttons
- Either
  - 7 rows of 3 squares with numbers 1-21
  - 1 row of 2 bigger squares (22 + 23)
  - 1 row with door 24
- Or:
  - 8 rows of 3 squares
- Button opens new "page" which shows the content or Link and a "back" button
- Doors have status:
  - locked (little lock symbol) if day hasn't come yet
  - unlocked but not yet opened
  - unlocked and already opened (no content preview)

# Installation Instructions

- How to download an .apk directly to android phone
- How to install it


