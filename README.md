FlindersTimetable
=================

## Project Brief

This project helps Flinders students find their ideal timetable for a semester.

### Prerequisites

To build the project, you'll need a modern version of Node.jsm, NPM and git in your classpath.

#### OS X

If you have homebrew installed, run

    brew install nodejs git

### Installation

    npm install -g grunt-cli karma bower
    git clone git@github.com:TobiasWooldridge/FlindersTimetable.git
    cd FlindersTimetable
    npm install
    bower install

### Development

#### Continuous Building

To build the software continuously, run

    grunt watch


This will start continuous builds for the project (rebuilding the project every time a file changes), and start a webserver pointing to these builds at http://localhost:1337/

A webserver is necessary if you wish to avoid browser security issues. IE still manages to break things because localhost 
is an intranet address, so you'll need to turn down IE's intranet security settings to test in IE.

### Building

To build FlindersTimetable's application, run

    grunt
    
in the root directory of the project and it'll compile the LESS/JS into the project's /bin directory 
