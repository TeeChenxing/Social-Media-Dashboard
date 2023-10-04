# Functional Requirements and Notes

## Setting Up Gulp Workflow

- Install gulp to be able to run .scss files since browsers can only read .css and not .scss. To do this go to the terminal and run these commands:
  <br>
  ↳ `npm install gulp-cli`
  <br>
  ↳ `npm install gulp -g` (install gulp globally)
  <br>
  ↳ `npm -init -y` (setting up package.json file)
  <br>
  ↳ `npm install @babel/core @babel/preset-env postcss autoprefixer browser-sync cssnano sass dart-sass gulp gulp-babel gulp-postcss gulp-sass gulp-terser`<br>
  ↳`npm audit fix` (potential fixes for package vulnerabilities)

## Light/Dark Mode Toggle

- What HTML Markup --> https://scottaohara.github.io/a11y_styled_form_controls/src/radio-button--switch/
- Use fieldset, legend, radio inputs
- Switching between light/dark mode via JS and Prefers-color-scheme media query --> https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme
- Three options toggle: light/dark/system preference --> https://codepen.io/renddrew/pen/bRomab?editors=1100
- Takes system preference by default, but can be overriden with toggle

## CSS Variables (Custom Properties)

- https://css-tricks.com/updating-a-css-variable-with-javascript/

## Accessibility

- Use correct headings tags
- Screenreader-only text for card titles/usernames --> https://www.accessibility-developer-guide.com/examples/hiding-elements/visually/
