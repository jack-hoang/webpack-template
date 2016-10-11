# webpack-template
Template project for webpack, karma, jasmine

## Prerequisites
1. Install Git
2. Install NodeJS & NPM

## Getting started
1. Clone project to local directory (this directory will be referred to as `$project.root`)
2. Go into `$project.root`
3. Run `npm install`
4. Run `npm run-script package` to package the JS files
5. Run `npm start` to start the server
 
## Unit Testing with Karma/Jasmine
1. Run `npm test`

## Integration Testing with Nightwatch
1. Install Nightwatch `npm install -g nightwatch`
2. Install Selenium `npm install selenium-standalone@latest`
3. Install Selenium Server `npm run-script selenium-install`
4. Run `npm run-script test:browser`
