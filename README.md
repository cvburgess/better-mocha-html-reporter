# Better HTML Mocha reporter

An extensible HTML reporter for Mocha

## What it does

Creates an html fragment with better-mocha-html-reporter and generate an HTML file

## Install

`npm install better-mocha-html-reporter`

## Running

`mocha yourDir --reporter better-mocha-html-reporter > test.html && open test.html`

## Customizing

If you want to use or extend the HTML template provided,
copy `template.html` from `node_modules/better-mocha-html-reporter` into your project
and pass the path to that file into your mocha script as such:

`--htmlTemplate mytemplate.html`

using the example above:

`mocha yourDir --reporter better-mocha-html-reporter --htmlTemplate ./mytemplate.html  > test.html&& open test.html`

the `{{reportResult}}` is where the results from mocha get injected so be sure to keep that in tact!
