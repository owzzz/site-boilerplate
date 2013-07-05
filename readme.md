# Site Boilerplate
> A complete site boilerplate for @andismith&#x27;s personal projects

[![Build Status](https://travis-ci.org/andismith/site-boilerplate.png?branch=master)](https://travis-ci.org/)
Version 0.2.2

## Getting Started
This boilerplate requires Grunt `~0.4.0`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide.

## Installation
1. [Fork the repo](https://github.com/andismith/site-boilerplate/fork)
1. `git clone https://github.com/andismith/site-boilerplate.git`
1. `cd base-web-project`
1. Install project dependencies with `npm install`
1. Make sure you have the Grunt command-line interface with `npm install -g grunt-cli`
1. Install SASS 3.3.0 with `gem install sass --pre` for Source Maps
1. Run Grunt with `grunt` for development build, watch and server
1. Run Grunt with `grunt` [`dev` | `prod`] for development/production build

## Features
* Seperate source `src` and distribution `dist` folders
* Watches files and runs a partial compliation on the files that have changed
* Runs on `localhost:3000`
* Assemble Templating - With Handlebars
* Styles - Autoprefixing and SASS compliation
* JavaScript - JSHint, Source Maps and Uglification
* JSON - Linting
* Images - Image Minification
* Latest jQuery, Modernizr, RequireJS and lodash
* Version updating
* Gruntfile hinting
* Production build tasks with `grunt prod`

## Roadmap
* Add Common Styles
* Require JS
* Jasmine Testing

## Issues and Feedback
Found an issue, have an idea? [github.com/andismith/site-boilerplate/issues](https://github.com/andismith/site-boilerplate/issues)