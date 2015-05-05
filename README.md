# skeleton.css
NPM for skeleton.css

## Yet another npm for skeleton.css?
* The PR for NPM at the original is dated last Dec 2014
* Current NPM by other contributor is inline the whole file as string, while I want something similar to `normalize.css` npm
* My need to test jspm with it
* Unlike Maven/Bintray, npmjs needs the package name to be unique (otherwise proceed to dispute), so I am sticking to github as registry

## Fixes
* `package.json` - `author` field is a person not an array
* `package.json` - add `style` field
* `package.json` - add dependency for `normalize.css` version `>= 3.0.2`
* `package.json` - jspm package override
* `index.js` - removed and follow `normalize.css` npm style

## Usage
* `jspm`:
    * `$ jspm install github:saikocat/skeleton.css@2.0.4`
    * In your code, `import 'saikocat/skeleton.css;'`

