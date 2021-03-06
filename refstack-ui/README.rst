=======================
Refstack User Interface
=======================

User interface for interacting with the Refstack API.

Setup
=====

Create a config.json file and specify your API endpoint inside this file:

:code:`cp app/config.json.sample app/config.json`

You can start a development server by doing the following:

Install NodeJS and NPM:

:code:`curl -sL https://deb.nodesource.com/setup | sudo bash -`

:code:`sudo apt-get install nodejs`

From the Refstack project root directory, move into the UI folder: 

:code:`cd refstack-ui`

Install dependencies and start the server:

:code:`npm start`

Doing this will automatically perform :code:`npm start` and :code:`bower install`
to get all dependencies.

By default, as noted in package.json, the server will use 0.0.0.0:8080.

Test
====

To run unit tests, simply perform the following:

:code:`npm test`
