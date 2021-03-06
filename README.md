# React Atomic Structure
[![Build Status](https://travis-ci.org/Rulox/react-atomic-structure.svg?branch=master)](https://travis-ci.org/Rulox/react-atomic-structure) [![Dependency Status](https://gemnasium.com/badges/github.com/Rulox/react-atomic-structure.svg)](https://gemnasium.com/github.com/Rulox/react-atomic-structure)


Basic Structure for React app following Atomic Design.

This base project allows you to have a basic React App folder structure following the principles of [Atomic Design](http://bradfrost.com/blog/post/atomic-web-design/).
It contain some basic components that you can use. All the components are not (or minimally) stylized. The main objective
of this project is to have a basic structure, that is the reason we are not doing complex styles and/or adding many libs.

## Tools

Using these package, you will be able to start a new fresh React project with the basic folder and file structures.

This project uses ES6 in the JS side, and Sass for styles. It also uses BrowserSync, a tool that will create a
web server in your machine that automatically updates the code and the styles whenever the watcher detects a change.

## Features

* ES6 to JS Transpile
* SASS to CSS
* Auto watcher for JS and SCSS files
* Atomic design project structure
* Launch server that updates itself every time we change a file with browsersync
* JS Lint ( extending airbnb eslint styles )
* Styleint

## TODO List
* Tests
* Production build (minification, etc)

## Requirements
* nodejs v5.*
* npm v3.*


## Getting started

[Download the master branch](https://github.com/Rulox/react-atomic-structure/archive/master.zip)

**or**

Clone this repo (Be sure you delete the .git file, or move the files to your own project folder/repository)
```bash
git clone -b master --single-branch --depth 1 git@github.com:Rulox/react-atomic-structure.git
```

##### Install Gulp globally
```bash
npm install -g gulp
```

##### Install npm dependencies
```bash
npm install
```

##### Run the server
```bash
npm run start
```
A browser window should open, if not, open it manually and go to http://localhost:3000/ (or any other URL+PORT that your terminal says). You can start working right now in the code, and all the changes will be visible in the browser just opened.

## Predefined components
But first, [What is Atomic Design?](http://bradfrost.com/blog/post/atomic-web-design/)

These components are just an idea on how to develop your application following the Atomic Design. Feel free to upgrade/delete
them in order to do your own app!

#### Atoms (stateless component)
* Anchor
* Label
* Button
* Input
* Image
* Title
* Paragraph

#### Molecules
* Labeled input
* Content

#### Organisms
* Article
* Form
* Nav

#### Templates
* Home
* About

## Folder structure and explanation
WIP

## NPM Scripts
This project comes with the following scripts to help you.

```bash
npm run start
```
1. Create CSS and JS bundles from Sass and JS.
2. Launch a browsersync web server and open default browser.
3. Launch watchers on JS/CSS files.

## Contributions
Feel free to create a pull request or create an issue to add features or fix bugs.
