# Brunch with Banana Pancakes (modified)

Banana Pancakes is a [Brunch](http://brunch.io/) skeleton that utilizes [Bootstrap](http://twitter.github.com/bootstrap/), [Backbone](http://backbonejs.org/), [Handlebars](http://handlebarsjs.com/), and [LESS](http://lesscss.org/) / [SASS](http://sass-lang.com/). It also includes [Backbone.Mediator](https://github.com/chalbert/Backbone-Mediator) for Pub/Sub patterns.

## Application example

 * [askalyuk/pay-periods-remaining](https://github.com/askalyuk/pay-periods-remaining)
 * [ppr-askaliuk.rhcloud.com](http://ppr-askaliuk.rhcloud.com/)

## Getting started

Make sure to have [Brunch.io](http://brunch.io) installed.

Create your project using Banana Pancakes with:

	brunch new <your-project-name> -s github://askalyuk/brunch-banana-pancakes

Or simply copy the repository to your hard drive and rename it.

## Credit
This fork was spawned from original [Brunch with Banana Pancakes](https://github.com/Anaphase/brunch-banana-pancakes).

## Difference
 * Improve application structure to use modules
 * Each module is separated set of models, views, styles, templates etc.
 * Add common module with basic classes
 * Use single application.js as initializer
 * Remove view dependency from application. Now only router "knows" about views
 * Lint fixes (remove trailing spaces etc.)
