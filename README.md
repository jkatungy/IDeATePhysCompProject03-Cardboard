# IDeATe Spring 2016 Physical Computing Studio: Project03 — Cardboard

In this project, you will create an augmented virtual reality. 

Using a Google Cardboard and a 3D world created in a web browser, you will design, build, sense, and actuate real-life physical responses to on-screen stimuli. For example, if the user passes a waterfall in the Cardboard, they may be sprayed by a water gun in real-life. If they open a window, they may feel a breeze on their face created by a fan.

### What you should learn
* Customizing open-source designs
* How to make a simple web server
* Basic web development using premade libraries and templates
* Creating a 3D world with found and made virtual objects
* Developing a game/story/environment
* Sharing code with GitHub

### Getting started
1. Go to [http://threejs.org/examples/](http://threejs.org/examples/) and look at some of the examples of things you can do with Three.js
1. Go to [the Three.js Documentation](http://threejs.org/docs/index.html#Manual/Introduction/Creating_a_scene) and follow the tutorial by building your own spinning cube
1. Fork this repository
1. Clone the new repo to your computer
1. `cd` into the repo and start a server with `python -m SimpleHTTPServer 8080`, where 8080 is the port number you want to use
1. Open [http://localhost:8080](http://localhost:8080) in your browser (preferably Chrome) and explore the demo world

### This repo contains
* '3D': A folder of demo OBJs (a plain-text 3D model filetype; it would be a good idea to open one up in your favorite text editor, and along with some [documentation](https://en.wikipedia.org/wiki/Wavefront_.obj_file), take a look around), and their companion MTLs (plain-text files defining the materials an OBJ should display). You cannot use any of the existing contents of this folder in your final submission.
* '3D/textures': A folder containing all the texture files used by the OBJs and MTLs. You cannot use any of the existing contents of this folder in your final submission.
* 'cardboard/cardboard_v1.2.pdf': The official laser-cut version of Google Cardboard v1.2. You should edit this file for your personal phone and the supplied lenses.
* 'css/style.css': A CSS stylesheet that defines the characteristics about the site's style, including font choices, colors, margins, etc.
* 'js/script.js': The backbone of your app. This contains pretty much all the user-written code that runs the webpage and 3D world.
* 'js/threejs/': Contents of the Three.js library. You probably shouldn't edit this, but do take a look at its contents. If you need to add another Three.js module, add it here.
* 'index.html': The website's markup. This is what the browser uses to determine what goes where. It also contains metadata about the page.
* 'README.md': This file. You should edit yours to explain your project in detail.

### Marking your progress
You should make frequent commits to your forked repo, as it will be your final submission (in addition to a blog post). Standard operation procedure for using GitHub correctly should be followed (see [here](https://guides.github.com/activities/hello-world/) or [here](https://try.github.io/levels/1/challenges/1) if you're unsure).
