# TinyLink
A lightweight, self-hosted URL shortener.
This repository contains the full source code for running a local instance of the TinyLink service available at
**[tinylink.pvsolutions.dev](https://tinylink.pvsolutions.dev/)**.
Both versions provide the same core functionality, but the public site uses a different UI.

## Features
* Fast and lightweight URL shortening
* Fully local, self-contained environment
* Simple Flask backend
* JSON-based storage (no external database required)
* Easy to modify, extend, and deploy

## Version Numbering Scheme
TinyLink follows a **[semantic versioning](https://semver.org/)** approach to indicate changes and compatibility:

* **Major version (`X.0.0`)** — major changes  
* **Minor version (`0.X.0`)** — minor changes  
* **Patch version (`0.0.X`)** — patches  

## Requirements
* Python **3.13.7** (developed and tested on this version)
* Dependencies listed in `requirements.txt`

## Installation
Clone the repository:
```bash
git clone https://github.com/pvsolutions-dev/TinyLink-Public.git
cd TinyLink-Public
```
Install dependencies:
```bash
pip install -r requirements.txt
```
Run the application:
```bash
python app.py
```
The server will start at:
```
http://127.0.0.1:5000
```
## Notes
* The public TinyLink service may receive updates sooner than this open-source version.
* Issues and suggestions are welcome—feel free to open an issue in this repository.
