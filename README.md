# Keythm - Type in high-fidelity

Keythm is a mechanical keyboard typing simulator that recreates the sound and feel of typing on a variety of custom keyswitches, with a simple one-minute typing test. It supports 10+ switches, keyboard layouts, and case colors for a customizable, satisfying typing experience.

This project is a fork of [kbsim](https://github.com/tplai/kbsim) by [Thomas Lai](https://github.com/tplai), used and rebranded here under its MIT license — see `LICENSE.md`, which keeps the original copyright notice as the license requires. Full credit to Thomas for the original build; this fork is maintained by Segun Ajakaiye.

## Features
- Unique sounds for specific keys
- 1 minute English typing test
- Wide selection of case colors and layouts
- Dark mode

## Currently Supported Switches
- NovelKeys Creams
- Holy Pandas
- Turqoise Tealios
- Gateron Black Inks
- Cherry MX Blacks
- Cherry MX Browns
- Cherry MX Blues
- Kailh Box Navies
- Buckling Spring
- SKCM Blue Alps
- Topre

## Currently Supported Layouts
- Fullsize
- Tenkeyless
- 75%
- 65%
- HHKB

# Developers

## Setup
To run this application locally, use:

```bash
npm install
npm start
```

## Project structure
    .
    ├── src                                           # Source files
    │   ├── assets                                    # audio and image assets
    |   |   ├── audio  
    |   |   └── images
    │   ├── features                                  # components and modules
    |   |   ├── header, footer, key, keySimulator, ...
    │   ├── public                                    # robots.txt
    |   |   └── robots.txt
    |   ├── App.test.js                               # starter React test file
    |   ├── index.css                                 # index styling
    |   ├── index.html                                # meta tags
    |   ├── index.js                                  # React entry point
    |   └── serviceWorker.js                          # basic offline usage serviceWorker
    ├── .babelrc                                      # babel transpiler config
    ├── LICENSE.md                                    # MIT license (original copyright retained)
    ├── README.md                                     # you're reading this!
    ├── package.json                                  # dependency file
    ├── webpack.config.js                             # webpack config file
    └── yarn.lock                                     # yarn dependency lockfile
