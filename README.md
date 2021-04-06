# Tidal Patterns in javascript

This is a working repo for exploring [tidal.pegjs](https://github.com/gibber-cc/tidal.pegjs), a javascript port of the [Tidalcycles](https://tidalcycles.org/) pattern language. There are two examples, one using the [WebDirt](https://github.com/dktr0/WebDirt) audio library, and the other using the [Tonejs](https://tonejs.github.io/) audio library. You'll need to grab the wonderful [Dirt-Samples](https://github.com/tidalcycles/Dirt-Samples) to hear any sounds. It's included as a submodule. Just follow the initialization instructions below to download those. [P5js](https://p5js.org/) is used for the visual element.

## Usage

### Initialization
Clone the repo to your computer: `git clone https://github.com/aaronsherwood/tidalPatternsJS.git`

Grab submodules:
* `git submodule init`
* `git submodule update`

### Python Simple Server
You need to serve the static HTML files to get around CORS restrictions on loading the audio:
* If Python version is 3.X start your server by: `python3 -m http.server`
* If Python version is 2.X start your server by: `python -m SimpleHTTPServer`

### Examples 
* The main index.html file uses WebDirt for the audio. Navigate to http://localhost:8000/
* Naviagate to http://localhost:8000/tonejs.html for the tonejs version.
