# Pahina
Pahina is a Bootstrap 4 Starter Theme with SaSS

# About
Bootsrap theming made easier using SaSS

# Installation
Run: `$ git clone https://github.com/joseph-lariosa/pahina-private.git`

Or download as zip and extract everything to your project folder.

# Installing Dependencies
Make sure you have installed Node.js and Browser-Sync (optional) on your computer globally
Then open your terminal and browse to the location of your UnderStrap copy

Run: `$ npm install`

# Running
To work with and compile your Sass files on the fly start:

`$ gulp watch`

Or, to run with Browser-Sync:

First change the browser-sync options to reflect your environment in the file /gulpconfig.json in the beginning of the file:

`{
    "browserSyncOptions" : {
        "proxy": "localhost/*", // <----- CHANGE HERE
        "notify": false
    },
    ...
};`

then run: `$ gulp watch-bs`

# Licenses & Credits
Font Awesome: http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
Bootstrap: http://getbootstrap.com | https://github.com/twbs/bootstrap/blob/master/LICENSE (Code licensed under MIT documentation under CC BY 3.0.) and of course
jQuery: https://jquery.org | (Code licensed under MIT)
