# Sound Board README

Welcome to the Sound Board project! This fun web app allows users to play a variety of pre-loaded sounds by clicking on buttons, creating a unique audio experience. Check out the live demo at: https://sonnymay.github.io/Sound-Board/

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Customization](#customization)
- [Adding Sounds](#adding-sounds)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)

## Features

- Variety of pre-loaded sounds
- Easy to use interface
- Customizable button layout
- Responsive design

## Getting Started

1. Clone the repository or download the ZIP file:

   ```sh
   git clone https://github.com/sonnymay/Sound-Board.git
   ```

   Or download the ZIP file [here](https://github.com/sonnymay/Sound-Board/archive/refs/heads/master.zip).

2. Extract the files and include them in your project folder.

3. Open the `index.html` file in your browser to see the app in action.

## Usage

1. Click on any of the buttons to play the associated sound.
2. Combine different sounds by clicking multiple buttons.
3. Have fun experimenting with different sound combinations!

## Customization

You can customize the appearance and behavior of the Sound Board app by modifying the `style.css` and `main.js` files. Here are some common properties you might want to change:

- `body` - Modify the background color, font size, and other general properties.
- `button` - Adjust the button size, color, font, and hover effects.

## Adding Sounds

To add more sounds to the Sound Board, follow these steps:

1. Add your sound file (preferably in MP3 format) to the `sounds` folder.
2. Modify the `main.js` file to include your new sound. Add a new entry to the `sounds` array:

   ```javascript
   {
       name: 'Your Sound Name',
       file: 'sounds/your-sound-file.mp3'
   }
   ```

3. Add a new button in the `index.html` file with the appropriate `data-sound` attribute:

   ```html
   <button class="sound-button" data-sound="Your Sound Name">Your Sound Name</button>
   ```

4. Refresh the page, and your new sound should be available on the Sound Board.

## Browser Support

The Sound Board app is compatible with the following browsers:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

Please note that the Sound Board app may not work correctly on older browsers or those that do not support modern JavaScript features and HTML5 audio.

## Contributing

We welcome contributions to the Sound Board project. Feel free to submit issues, fork the repository, and create pull requests.

## License

The Sound Board app is released under the MIT License. See the [LICENSE](https://github.com/sonnymay/Sound-Board/blob/master/LICENSE) file for more information.
