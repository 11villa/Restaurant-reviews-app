# Table of Contents

* [Instructions](#instructions)
* [Dependencies](#dependencies)

## Instructions

1. Clone or download this project on your computer.
2. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

    * In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8080`. For Python 3.x, you can use `python3 -m http.server 8080`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
   * Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.
3. With your server running, visit the site: `http://localhost:8080` to access to the   restaurant reviews app.


## Dependencies

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/) to see the map on the site. Mapbox is free to use, and does not require any payment information.