# Code 301, day 1

### Responsive design:
Most of this we had touched on in 201, covered some more detail today.  Talked about how to think mobile first.  Not necessary to aim for specific size screen, ok to break up when the page needs it for design or aesthetics.

### SMACSS
Covered kind of briefly, rules to help layout css so it doesn't end up a horrible jungle.
Divide css rules into five categories:
- Base: usually single element selectors, how that kind of element appears anywhere on a page.
- layout: how you divide up your page, layouts hold modules.
- Module: reusable 'module' parts of design.  callouts, sidebars, product lists etc.
- State: describe how modules look in specific states, on a certain width of screen, is-active, is-on-fire, is-collapsed
- Theme: defines colors/images to give your look and feel. not needed separately for every site, but if it is separate lets you change styles for alternate themes; nav on left, colorblind mode, etc.

### Rabbit hole
Found out that if you don't define a height on an element radial-gradients won't work properly.
