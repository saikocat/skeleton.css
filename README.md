# skeleton.css
NPM for skeleton.css

## Yet another npm for skeleton.css?
* The PR for NPM at the original is dated last Dec 2014
* Current NPM by other contributor is inline the whole file as string, while I want something similar to `normalize.css` npm
* My need to test jspm with it

## Fixes
* `package.json` - `author` field is a person not an array
* `package.json` - add `style` field
* `package.json` - add dependency for `normalize.css` version `>= 3.0.2`
* `index.js` - removed and follow `normalize.css` npm style
