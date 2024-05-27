# Music-Player
# Music Player Project

This project is a simple music player web application built using HTML, CSS, and JavaScript. It allows users to play, pause, and navigate through a list of songs. The player displays the song's cover image, title, and artist, and includes a progress bar to show the current playback time.

![image](https://github.com/LakinduNimesh/Music-Player/assets/149768006/e09cfff0-0c6f-4271-b2c7-9ab7e7e3a3ed)


## Features

- Play and pause music
- Navigate to the next or previous song
- Display song details (cover image, title, artist)
- Show and update the progress bar for the current song
- Click on the progress bar to jump to a specific time in the song

## Project Structure

The project consists of the following files:

- `index.html`: The main HTML file that contains the structure of the music player.
- `style.css`: The CSS file that styles the music player.
- `script.js`: The JavaScript file that adds functionality to the music player.
- `assets/`: A folder containing the song files and cover images.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/LakinduNimesh/Music-Player.git
   cd Music-Player
   ```

2. Open `index.html` in your web browser to see the music player in action.

## Usage

1. Use the play button to start or pause the music.
2. Use the forward and backward buttons to navigate through the list of songs.
3. The progress bar shows the current playback time. Click on the progress bar to jump to a specific time in the song.

## Dependencies

This project uses Font Awesome for the player controls icons. The necessary CSS file is included in the `<head>` section of `index.html`:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

## Customization

To customize the list of songs:

1. Add your song files and cover images to the `assets/` folder.
2. Update the `songs` array in `script.js` with the paths to your song files and cover images:

   ```javascript
   const songs = [
    {
        path: 'assets/1.mp3',
        displayName: 'Song 01',
        cover: 'assets/1.jpg',
        artist: 'Artist 01',
    },
    {
        path: 'assets/2.mp3',
        displayName: 'Song 02',
        cover: 'assets/2.jpg',
        artist: 'Artist 02',
    },
    {
        path: 'assets/3.mp3',
        displayName: 'Song 03',
        cover: 'assets/3.jpg',
        artist: 'Artist 03',
    }
];
   ```

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements

- Icons by [Font Awesome](https://fontawesome.com/)
- Fonts by [Google Fonts](https://fonts.google.com/)

