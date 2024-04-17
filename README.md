# DJ Days - Walkthrough

This repository has the base code for the walkthrough of the following project:

Welcome to **DJ Days**, a dynamic single-webpage application designed to bring music lovers and collectors a virtual DJ booth at their fingertips. **DJ Days** allows users to see which album is currently playing, browse through a comprehensive list of albums, add new albums to their collection, and select any album to be the "now playing" music.

## Features

- **Now Playing Display**: The top section of the app showcases the album that is currently playing, displaying its cover art, title, and artist.
- **Album List**: A comprehensive list of all albums available in your collection. Users can scroll through and select any album to play next.
- **Add New Album**: Users can add new albums to the list by entering the album's details, including its title, artist, genre, and cover art URL.
- **Dynamic Selection**: Click on any album from the list to make it the "now playing" album, updating the display automatically.
- **Library Stock Check**: 
    - If there are less than 10 albums: show a message to say you need more albums to play a full set.
    - If there are 10 albums or more, show a message to say you're ready to start playing your DJ set.
- **JSON File**: A JSON file with 5 albums already added in it.

## Technologies Needed

- **HTML**: To structure the content of your application, providing the framework for the dynamic features to come alive.
- **CSS**: To style your application, ensuring a visually appealing and intuitive user interface.
- **JavaScript (JS)**: To power the interactive features of the app, such as adding new albums, selecting an album to play, and dynamically updating the now playing display.
- **Node.js**: To manage the application dependencies and run server-side scripts.
- **JSON**: To store an initial list of 5 albums, making it easy to add, retrieve, and update the collection. This project will need an `albums.json` file that serves as the initial database for the application.

## Getting Started

Make sure to fork this project into your own Github account, and clone it down to start working on it!

To run the application and install all required dependencies, ensure you have Node.js installed and then run:

```zsh
npm install
```

### Commands to Remember: Saving your work

```zsh
git add .
git commit -m "Add your commit message"
git push
```

