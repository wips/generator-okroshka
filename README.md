# generator-okroshka [![Build Status](https://secure.travis-ci.org/kucherenko/generator-okroshka.png?branch=master)](https://travis-ci.org/kucherenko/generator-okroshka)

## Getting Started

### What is generator okroshka?

Generator okroshka is a generator for [Yeoman](http://yeoman.io).

### What is okroshka?

Okroshka is traditional Russian cold soup with boiled potatoes, eggs, cucumbers, spring onions, other vegetables, meat and kefir or kvass.

### Why Yeoman needs okroshka?

Generator okroshka is a easy way to start project with AMD, TDD and BDD.
Generator okroshka include:
 - CoffeeScript - I don't like phrase "syntax sugar", CoffeeScript is syntax meat for JS, okroshka needs meat;
 - [Cucumber.js](https://github.com/cucumber/cucumber-js) - the popular Behaviour-Driven Development tool;
 - Mocha & chai & sinon - popular frameworks for TDD and unit testing;
 - RequireJS - implementation of AMD;
 - Twitter Bootstrap - sleek, intuitive, and powerful mobile first front-end framework for faster and easier web development;
 - backbone & underscore & handlebars - flexible framework for frontend development;
 - jquery - just jquery;

All of this pieces make generator okroshka delicious thing for Yeoman.
Structure of project created with okroshka include examples of application on Backbone with AMD made on CoffeeScript, include example of environment for unit testing with mocha, chai & sinon with codecoverage, include example of BDD features with cucumber.js, include grunt file for developmnet and production builds.

To install generator-okroshka from npm, run:

```
$ npm install -g generator-okroshka
```

Finally, initiate the generator:

```
$ yo okroshka
```

### Usage

Run mocha tests:
```
$ grunt test
```

Run cucumber.js:
```
$ grunt e2e
```

Start development server:
```
$ grunt server
```
Development server watching for changes in your folders, reload you project after changes, run tests and generate code coverage.

Also you can run tests in browser if you dev server is working, tests located at [http://localhost:9000/test/](http://localhost:9000/test/). Code coverage report located at [http://localhost:9000/test/coverage.html](http://localhost:9000/test/coverage.html)

Build you project for production:
```
$ grunt build
```

Start server for productiuon code:
```
$ grunt server:dist
```

### What is Yeoman?

Trick question. It's not a thing. It's this guy:

![](http://i.imgur.com/JHaAlBJ.png)

Basically, he wears a top hat, lives in your computer, and waits for you to tell him what kind of application you wish to create.

Not every new computer comes with a Yeoman pre-installed. He lives in the [npm](https://npmjs.org) package repository. You only have to ask for him once, then he packs up and moves into your hard drive. *Make sure you clean up, he likes new and shiny things.*

```
$ npm install -g yo
```

### Yeoman Generators

Yeoman travels light. He didn't pack any generators when he moved in. You can think of a generator like a plug-in. You get to choose what type of application you wish to create, such as a Backbone application or even a Chrome extension.

### Getting To Know Yeoman

Yeoman has a heart of gold. He's a person with feelings and opinions, but he's very easy to work with. If you think he's too opinionated, he can be easily convinced.

If you'd like to get to know Yeoman better and meet some of his friends, [Grunt](http://gruntjs.com) and [Bower](http://bower.io), check out the complete [Getting Started Guide](https://github.com/yeoman/yeoman/wiki/Getting-Started).


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
