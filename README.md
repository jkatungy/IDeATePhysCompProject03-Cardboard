# IDeATe Spring 2016 Physical Computing Studio: Project03 — Cardboard

In this project, you will create an augmented virtual reality. 

Using a Google Cardboard and a 3D world created in a web browser, you will design, build, sense, and actuate real-life physical responses to on-screen stimuli. For example, if the user passes a waterfall in the Cardboard, they may be sprayed by a water gun in real-life. If they open a window, they may feel a breeze on their face created by a fan.

### What you should learn
* Customizing open-source designs
* How to make a simple web server with Node/Express
* Basic web development using premade libraries and templates
* Creating a 3D world with found and made virtual objects
* Developing a game/story/environment
* Sharing code with GitHub

### Getting started
1. Go to [http://threejs.org/examples/](http://threejs.org/examples/) and look at some of the examples of things you can do with Three.js
1. Go to [the Three.js Documentation](http://threejs.org/docs/index.html#Manual/Introduction/Creating_a_scene) and follow the tutorial by building your own spinning cube
1. Fork this repository
1. Clone the new repo to your computer
1. `cd` into the repo and install the dependencies with `npm install`
1. Start the server with `npm start`
1. Open [http://localhost:3000](http://localhost:3000) in your browser (preferably Chrome) and explore the demo world

### This repo contains
* 'public/3D': A folder of demo OBJs (a plain-text 3D model filetype; it would be a good idea to open one up in your favorite text editor, and along with some [documentation](https://en.wikipedia.org/wiki/Wavefront_.obj_file), take a look around), and their companion MTLs (plain-text files defining the materials an OBJ should display). You cannot use any of the existing contents of this folder in your final submission.
* 'public/3D/textures': A folder containing all the texture files used by the OBJs and MTLs. You cannot use any of the existing contents of this folder in your final submission.
* 'cardboard/cardboard_v1.2.pdf': The official laser-cut version of Google Cardboard v1.2. You should edit this file for your personal phone and the supplied lenses.
* 'public/stylesheets/style.css': A CSS stylesheet that defines the characteristics about the site's style, including font choices, colors, margins, etc.
* 'public/javascripts/script.js': The backbone of the client side of your app. This contains pretty much all the user-written code that runs the webpage and 3D world from the browser.
* 'public/javascripts/threejs/': Contents of the Three.js library. You probably shouldn't edit this, but do take a look at its contents. If you need to add another Three.js module, add it here.
* 'app.js': The settings for Express.
* 'bin/www': The settings for starting up the server.
* 'README.md': This file. You should edit yours to explain your project in detail.