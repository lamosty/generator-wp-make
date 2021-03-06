# WP-Make

WP-Make is a [Yeoman generator](http://yeoman.io) for quickly creating new WordPress projects based on some established template designs currently used by [10up](http://10up.com).

Briefly, WP-Make can be used to create a new theme, child theme, plugin, or library project - complete with unit tests - in seconds!

## Getting Started

If you need it, install Yeoman through npm:

```
$ npm install -g yo
```

To install generator-wp-make clone this repository and link it to npm:

```
$ git clone git@github.com:10up/generator-wp-make.git
$ npm link
```

Finally, in the desired project directory, initiate the generator:

```
$ yo wp-make
```

## Project Types

WP-Make ships with four default project types, each invoked with a subgenerator.

For each project type you get:

- Composer to manage server-side dependencies
- Bower to manage front-end dependencies
- NPM to manage development dependencies (like Grunt)
- Grunt to streamline development
- phpunit, paratest, and [WP_Mock](https://github.com/10up/wp_mock) for PHP unit testing
- Qunit for JS unit testing
- A fully-fleshed out, namespaced setup for WordPress plugin development

### Plugin

This subgenerator scaffolds out a standard WordPress plugin.
 
The project even includes some basic unit test examples to help get you started!

### Theme

This subgenerator scaffolds out a standard WordPress theme.
 
The project even includes some basic unit test examples to help get you started!

### Child Theme

This subgenerator scaffolds out a standard WordPress child theme.
 
The project even includes some basic unit test examples to help get you started!

### Library

This subgenerator scaffolds out a WordPress library. Libraries are a bit different from plugins in that they're meant to be included via Composer and embedded directly into a theme or a plugin. 

## License

MIT
