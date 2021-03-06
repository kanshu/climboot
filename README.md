# Climboot
## *Drupal 8 Theme w/ Pattern Lab*

This is simple Drupal 8 theme with [Pattern Lab](http://patternlab.io) conveniently integrated. The theme relies on Bootstrap 4 as the underlining front-end framework (Requires jQuery 3). Composer is used to manage the PHP edition of Pattern Lab. Node is used for the theme's asset compiling, as well as managing pattern generation.

#### Build Prereqs
- PHP 5.4+
- [Composer](https://getcomposer.org/doc/00-intro.md)
- [npm](http://blog.npmjs.org/post/85484771375/how-to-install-npm)
- [Grunt](http://gruntjs.com/getting-started)

**Following commands should be ran from the theme's directory**

### Quick-start Guide :rocket:

`npm run start`

_Issues install commands, as well as kicks off the Grunt task that compiles, generates and serves up the theme's Pattern Lab instance._

### Not so Quick-start Guide :bullettrain_side:

##### Install Pattern Lab dependencies
`composer install -d components`

_Install Pattern Lab dependencies inside the components directory_

##### Install node dependencies

`npm install`

_Install node dependencies_

##### Grunt Commands

`grunt`

_(Default) Simple asset compiling and pattern generation with Grunt_

`grunt pl:watch`

_Compile and generate, while watching for changes_

`grunt pl:serve`

_Compile and generate, while watching for changes, but serve it up on 3000_
