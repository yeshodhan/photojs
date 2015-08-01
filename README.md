# PhotoJS

A simple app for photographers or developers who are building tools for photographers to manage their photos and portfolio. Includes a responsive web portal + Ionic Framework based Android and iOS app.
  
## Pre-requisites

This section describes installation details about the prerequisites to run the program. Please note these instructions are for MacOSX based development machine.  
Please refer to the individual website of the prerequisites for installation on a specific platform. 

### 1. Install NodeJS. 
```bash
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew update
brew install node
```
  
For more information on how to install NodeJS for your platform, please visit [NodeJS Website](https://nodejs.org/download/)

### 2. Install Grunt, Bower, Yeoman

npm install -g bower grunt grunt-cli yo

## Installation 

Make sure you are at the project root directory. Run the below commands. This may take about 2-3 minutes depending upon your connection speed.

```bash
echo "setup: installing node dependencies using npm"
npm install
echo "setup: installing client dependencies using bower
bower install
```

## Run

```bash
grunt serve
```

To use a different port, use:
```bash
PORT=9030 grunt serve
```

