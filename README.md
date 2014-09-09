Ice block skeleton
==================

[![Build Status](http://travis-ci.org/iceblocks/skeleton.svg)](http://travis-ci.org/iceblocks/skeleton)

## What is Ice Block

[Ice Block](http://github.com/iceblocks) is an HTML component library for some rapid development of website components.

## Approach and patterns

Our component library tries to use some consistent dependencies for the ease of learning and consistency. Packages are managed with [bower](http://bower.io).

### Typical dependencies

 - [CSSWizidary Grids](http://csswizardry.com/csswizardry-grids/) - Grid system
 - [Inuit CSS](http://inuitcss.com/) - CSS framework
 - [requirejs](http://requirejs.org/) - JS module management

#### Other recomended dependencies

 - [Bourbon](http://bourbon.io/) - SASS mixin library

### Patterns and conventions

 - SCSS to be written in [BEM](http://bem.info/) style

## Dependency management

All the component should be managed with [bower](http://bower.io) so that they and their dependencies can be pulled in.
