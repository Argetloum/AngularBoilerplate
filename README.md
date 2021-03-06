# AngularBoilerplate [![Build Status](https://travis-ci.org/Argetloum/AngularBoilerplate.png)](https://travis-ci.org/Argetloum/AngularBoilerplate) <img src="http://img.shields.io/badge/Built%20with-Gulp-red.svg" />

Quick Front-End Boilerplate using AngularJS, Sass and Gulp.

Built for the modern developer. Encouraging a better workflow. JavaScript task running, build processes, autominification and file concatenation, wrapped with an enhanced HTML5 boilerplated.

* Source: [github.com/Argetloum/AngularJSBoilerplate](http://github.com/Argetloum/AngularJSBoilerplate)


## Jump start

Get started with the boilerplate:

1. Clone the git repo — `git clone https://github.com/Argetloum/AngularJSBoilerplate.git` and checkout the tagged release you need.
2. Execute in the shell `sudo npm install` to install each node.js dependencies, needed for [Gulp.](http://gulpjs.com/)
3. Execute in the shell `bower install` to install each front-end dependencies.
4. Execute in the shell `gulp` to generate the stylesheets and scripts files in the `app/assets/` folder.

## Features

Here are some of the main features of the boilerplate:

* AngularJS framework with routing and base folders
* HTML5 semantics
* Baseline HTML5 features, DNS prefetching, responsive meta
* Encourages one-file CSS/JS in the view (HTML) for performance
* Includes Modernizr and HTML5 Shiv
* Google Universal Analytics snippet
* Open source workflow with Gulp running on Node.js
* Pre-setup Sass/SCSS files and folders for baseline project structure and imports
* Standard .gitignore to ignore minified files and standard ignorables such as .DS_Store
* JSHint .jshintrc file for configuring JavaScript linting

## Scaffolding

````
├── app
│   ├── assets
│   │   ├── css
│   │   ├── fonts
│   │   ├── img
│   │   └── js
│   ├── layouts
│   │   ├── header.html
│   │   └── footer.html
│   ├── partials
│   │   └── home.html
│   ├── apple-touch-icon-precomposed.png
│   ├── favicon.ico
│   └── index.html
├── src
│   ├── js
│       ├── controllers
│       ├── directives
│       ├── factories
│       ├── filters
│       ├── services
│   │   └── app.js
│   └── scss
│       ├── mixins
│       ├── modules
│       ├── partials
│       ├── vendor
│       └── style.scss
├── package.json
├── README.md
├── bower.json
├── gulpfile.js
├── .gitignore
├── .bowerrc
├── .jshintrc
````
