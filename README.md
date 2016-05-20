# Flat Site Boilerplate

This is a simple boilerplate for starting flat-file site.

This boilerplate does NOT have a grid system built in, as most of our landing pages are quite simple in design, and do not require a grid.

Duplicate this project directory, then cd into it and run `npm install` then run `grunt build` to compile all the files. 

Any time you add a new file to the js/vendor directory, you need to run `grunt build` to add the new library to our plugins.min.js file  

For dev, run `grunt` which will watch the `scss` and `js` directory and compile our scripts.min.js file

## File structure:

```
klick-landing-page-boilerplate/
|—— css/
|   |—— style.css
|   |—— style.min.css
|—— favicons/
|   |—— favicon icon/image files 
|—— fonts/
|   |—— Helvetica Neue font files 
|—— images/
|   |—— error-tab.png
|   |—— IMAGES (.png, .svg, .jpg)
|—— js/
|   |—— build/
|   |   |—— plugins.js
|   |   |—— plugins.js.map
|   |   |—— scripts.js
|   |   |—— scripts.js.map
|   |—— source/
|   |   |——.jshintrc
|   |   |——init.js
|   |   |——modal.js
|   |—— vendor/
|   |   |—— DrawSVGPlugin.min.js
|   |   |—— MorphSVGPlugin.min.js
|   |   |—— ScrollMagic.min.js
|   |   |—— TweenMax.min.js
|   |   |—— animation.gsap.min.js
|   |   |—— jquery.ScrollMagic.min.js
|   |   |—— jquery.debouncedresize.js
|   |—— plugins.min.js
|   |—— plugins.min.js.map
|   |—— scripts.min.js
|   |—— scripts.min.js.map
|—— scss/
|   |—— -modules/
|   |   |—— _main.scss
|   |—— base/
|   |   |—— extends/
|   |   |   |—— _ext-background-svg.scss
|   |   |   |—— _ext-helpers.scss
|   |   |—— _animations.scss
|   |   |—— _base.scss
|   |   |—— _buttons.scss
|   |   |—— _fonts.scss
|   |   |—— _footer.scss
|   |   |—— _form-elements.scss
|   |   |—— _header.scss
|   |   |—— _helper-classes-and-mixins.scss
|   |   |—— _layout.scss
|   |   |—— _lists.scss
|   |   |—— _media-queries.scss
|   |   |—— _normalize.scss
|   |   |—— _tables.scss
|   |   |—— _typography.scss
|   |   |—— _variables.scss
|—— .editorconfig
|—— .htaccess
|—— .travis.yml
|—— Gruntfile.js
|—— index.html
|—— package.json
|—— README.md
```