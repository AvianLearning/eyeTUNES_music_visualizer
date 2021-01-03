# eyeTunes - Music visualizer

Art For Everyone.

Our aim is to create an online space that allows inclusive access to the creation of art and music through your computer’s keyboard and/or mouse. 

Users should not require any musical or artistic background in order to get audio or visual feedback while they interact with the app. It should be a playful, exploratory experience


## MVP

The user should be able to:

- Play a piano-type instrument that generates notes with computer keyboard
- Create a visualisation - colours/shapes change in response to audio created
- Save, delete and view a collection of songs


## Example Extensions

- Song tempo slider
- Enable user to customise colors and keyboard
- Be able to use the keyboard on screen
- Select different animations and instruments to play


## API, Libraries, Resources
- [Tone.js](https://tonejs.github.io/) - Web Audio framework for creating interactive music in the browser.
- [anime,js](https://animejs.com/) - Lightweight JavaScript animation library
- [styled-components](https://styled-components.com/)


## Setup
Install dependencies in both the client and the server folders:
```
cd client
npm install

cd server
npm install
```

Seed the database.  Within the server folder:
```
npm run seeds
```

Run express (leave running in a terminal window).  Within the server folder:
```
npm run server:dev
```

Run React development environment (leave running in a terminal window).  Within client folder:
```
$ npm start
```

