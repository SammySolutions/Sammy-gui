# Sammy-gui
## Sammy-gui is based on [RDash-angular](https://github.com/rdash/rdash-angular)

### Requirements
* [NodeJS](http://nodejs.org/) (with [NPM](https://www.npmjs.org/))
* [Bower](http://bower.io)
* [Gulp](http://gulpjs.com)

### Installation:
We'll start by installing npm:

- Ubuntu / Raspbian:   `sudo apt-get -y install nodejs npm node-semver `
- Fedora:   `sudo dnf -y npm`
- Arch:     `sudo pacman --noconfirm -S npm`

Then we'll use npm to install both bower and gulp globally
`sudo npm install -g bower gulp`

Next run:
`npm install && bower install`

Thats it! You've successfully installed Sammy-gui!
Run it with the `gulp` command.

### Development usage
1. Install the NodeJS dependencies: `npm install`.
2. Install the Bower dependencies: `bower install`.
3. Run the gulp build task: `gulp`.
4. App can be found in the "dist" folder

Continue developing the dashboard further by editing the `src` directory. With the `gulp` command, any file changes made will automatically be compiled into the specific location within the `dist` directory.

1. Run the gulp default task: `gulp`. This will build any changes made automatically, and also run a live reload server on [http://localhost:8888](http://localhost:8888).



