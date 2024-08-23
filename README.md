# piano-app

## Overview

Welcome to the Piano App, a simple and interactive web-based piano. This app allows users to play musical notes by either clicking on the piano keys with a mouse or pressing specific keys on their keyboard. The application is built using HTML, CSS, and JavaScript.

## Features

- Interactive Piano Keys: Play notes by clicking on the keys or pressing the corresponding keys on your keyboard.
- Keyboard Controls: Use the keys z, x, c, v, b, n, and m for the white keys and s, d, g, h, j for the black keys.
- Realistic Sound: Each key triggers an audio file corresponding to the note it represents.
- Visual Feedback: The pressed key is highlighted when active to enhance the interactive experience.

## Installation

1. Clone the Repository:

```bash
Copy code
git clone https://github.com/JSONParseError69/piano-app
cd piano-app
```

2. Add Audio Files:

- Place the required .mp3 files for each note in a directory named notes.
- Ensure the files are named exactly as C.mp3, Db.mp3, D.mp3, Eb.mp3, E.mp3, F.mp3, Gb.mp3, G.mp3, Ab.mp3, A.mp3, Bb.mp3, B.mp3.

3. Open the HTML file:

- Open index.html in your preferred web browser to start playing.

## Usage

- Mouse Interaction: Click on any key on the piano to hear the corresponding note.

- Keyboard Interaction: Use the following keys on your keyboard to play the notes:

      - White Keys: z, x, c, v, b, n, m
      - Black Keys: s, d, g, h, j

When you press a key, the corresponding piano key will light up to indicate that it is being played.

## Customization

- Add More Notes: To add more notes, update the HTML file with additional keys and corresponding audio files.
- Change Key Bindings: To change the keyboard bindings, modify the WHITE_KEYS and BLACK_KEYS arrays in the JavaScript (script.js) file.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as you see fit.
