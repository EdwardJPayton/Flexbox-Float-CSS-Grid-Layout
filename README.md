# Flexbox-Float-CSS-Grid-Layout
An awesome Flexbox CSS Grid layout with a Float fallback for legacy browsers. It works, you can't go wrong.

<strong><a href="http://edwardjpayton.github.io/Flexbox-Float-CSS-Grid-Layout/" target="_blank">DEMO</a></strong>



I want to use Flexbox now, but I've got to support old browsers.

This is an awesome Flexbox CSS Grid layout with a Float fallback. It works, you can't go wrong.




## Features
- Compatible with all modern browsers - when compiled with Auto-Prefixer it includes all Flexbox syntaxes - old and new.

- Float fallback for non Flexbox compatible browsers - using Modernizr for feature detection and it automatically fallsback to the Float grid.

- Clean and simple to use - no extra html classes needed to fallback to float, code your HTML and off you go.

- Using extendable, chainable BEM syntax, you can adjust the gutters, padding, and alignment easily (read more about chainable BEM syntax here - http://webuild.envato.com/blog/chainable-bem-modifiers/)




## Why not just use a float based grid?
Flexbox has many powerful features that are just not possible / insanely complicated with older CSS layout methods. Vertical alignment and centering to name two.

Floats were never meant for creating complex layouts, it's just they were the least hacky of all that was available.

Now we have Flexbox, a proper layout solution.



## Bug list
This is the first stage release and includes a couple of niggles which are actively being worked on.
### Flexbox layout
+ On grids without gutters, leaves a 1px wide gap between items on nested grids
### Float layout
+ Gutters are not correctly calculated on nested grids
### Responsive (Flexbox) layout
+ Margins are not correctly maintained on nested grids in demo

