# Responsive Web Applications with Container Queries
Jonathan Snook

There's no actual spec for container queries

* React
* JavaScript - detect component size and trigger on resize
* Declare in
    - CSS
    - HTML
    - JavaScript

## CSS
* JS parses the CSS
* JS and CSS need to be on same domain or set up CORS

## HTML
* Add as custom data- attribute
* Requires consistency of implementation

## JS
* At Shopify, they created a JSON file with all element queries
* Very consistent across platforms
* There's a discernable delay in execution (JS has to compute before reflow)

It's not about the properties, it's about the purpose.
Don't worry about duplicating properties; it GZips fairly well.

Avoid too much on the horizontal axis.

At Xero, they used React

*Make the right things easy and the wrong things hard*

## CSS in lieu of Media Queries
* `flex-wrap: wrap;` - can reconfigure a line that is too long for the current container
* `flex-basis` is used to establish the basis for the size of flex content
* `display: grid` with `auto-fit` and `minmax()` in `grid-template-columns`

## Wrapping it up
* Designers should think responsive before they need to
* Container queries enable faster development
* Use techniques to avoid media or container queries altogether (grid module, flex box)

[ricg.io](http://ricg.io)