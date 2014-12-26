# [atom](https://atom.io/)-[jscrambler](https://jscrambler.com/)

[JScrambler](https://jscrambler.com/) is a JavaScript obfuscation tool.

Obfuscate and minify your HTML5 and [Node.js](http://nodejs.org/) applications.

## Usage

* Hit Ctrl+Shift+S to scramble the currently active file
* Hit Ctrl+Shift+Alt+S to scramble the entire project

You can also find this options in the contextual and packages menus.

## Configuration
You can either use your `atom` configuration or place a `.jscramblerrc` file as
described in [here](https://github.com/jscrambler/node-jscrambler#rc-configuration).
The `atom` configuration can be set in your Settings view or directly into
your `config.cson` file.

    'jscrambler':
      # Must be relative to the project
      'filesDest': './dist'
      'keys':
        'access': ''
        'secret': ''
      'params':
  	    'expiration_date': '2199-01-01'
  	    'rename_local': '%DEFAULT%'
  	    'whitespace': '%DEFAULT%'

This configuration must be placed in your Atom's `config.cson` file (under Atom -> Open Your Config). You can find all parameters documentation in [here](https://github.com/auditmark/node-jscrambler).
