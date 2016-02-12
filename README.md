Radiodan Skeleton
====

A small skeleton application for getting started with Radiodan. It demonstrates:
- minimal setup and configuration
- how to control the player from the node app
- how to control the player from a web application
- playing a remote stream
- playing a local file

See the [Radiodan Client Library documentation](http://radiodan-client.readthedocs.org/en/latest/) for all the commands that you can use.

## Requirements

- mpd
- node.js / npm
- OS X / Pi 2 (arm7)

## Installation

    git clone https://github.com/radiodan/radiodan-skeleton.git
    cd radiodan-skeleton
    npm install

## Running

    npm start

This project includes the radiodan audio server and radiodan-broker that are installed via NPM.

You can see how to start these by looking in the Procfile.

You can install the server and broker separately if you need more flexibility.
