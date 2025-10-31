# simple-nodejs-app on Ubuntu

Simple-nodejs-app is a simple web application created using [Node.js](https://github.com/nodejs/node). It uses [MediaWiki - Wikipedia's Search API](https://www.mediawiki.org/wiki/API:Opensearch) to search for anything entered by the user and parses the result in a JSON format. The infobox of the Wikipedia page is parsed using [wiki-infobox-parser](https://github.com/0x333333/wiki-infobox-parser).

Install Node.js 16.x (LTS)
# Update package index
sudo apt update

# Add NodeSource repository for Node.js 16.x
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -

# Install Node.js and npm
sudo apt install -y nodejs

# Verify installation
node -v
npm -v
## Download and Installation

- Clone the repo ```https://github.com/Shaik-DevOpsLucky/simple-nodejs-app```

## Usage

- After installation, run ```npm install``` to download and install all the required dependencies.
- Run ```npm start``` to run the web application.

## Live Preview

To view a live preview of this application, click [here](https://desolate-coast-53201.herokuapp.com/)
