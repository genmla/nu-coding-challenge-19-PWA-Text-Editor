# PWA Text Editor
A Progressive Web Applicaiton Text Editor

## Description

This app is a progressive web application text editor. Users can input and edit text that persists across sessions. The app can also be installed to operate offline. Changes offline will persist for use in the browser online. We learned how to implement put and get logic to persist data in indexDB. We implemented logic for service-workers for offline installation, and primarly added plugins to the webpage file to build a user-end distribution file. 

## Table of Contents

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

To save the applicaiton locally, clone the repository with this command in the perferred location on your device: 
```md
git@github.com:genmla/nu-coding-challenge-19-PWA-Text-Editor.git
```

From the root of the cloned repository, run 

```md
npm i
```

Then once the packeage.json file is installed, run the following command: 

```md
npm run build
```

To install the text editor applicaiton, you can [follow this link to the deployed Heroku applicaiton](https://genmla-jate-text-editor.herokuapp.com/) and click the install butt at the top right corner

![Image demonstrating the location of the installation button](/assets/Install-Button.jpg)


## Usage

Users can type, edit, and access both online in the browser and offline in the downloaded app within the text editor. Click anywhere within the text editor after navigating to the deployed applicaiton or downloading the applicaiton to the local device and start typing. The text is colored to resemble a coding editor. 

Mock-Up: 

![Gif demonstrating the loading, usage, and installation of app](/assets/JATE%20Demo%20Gif.gif)

## Credits

N/a

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

