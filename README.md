h1. Requirements
* Node.js
** npm
* PhantomJS somewhere in your path.

h1. Installation
* Install requirements (Node+npm, Phantom).
* Run `npm install` in the root directory to install required packages (Karma, Jasmine, assorted support).

h1. Usage

The app can be found in the extension directory (i.e. select this directory when using "load unpacked extension" in Overwolf dev tools).

Running `karma start` will run a karma test server in the background. By it is configured to run Jasmine tests in PhantomJS by default whenever an HTML or JS file is saved.

A rough example of a test can be found in spec/qqSpec.js. Tests must be named "*Spec.js"
