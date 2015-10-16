# Jison Workshop - JSConf Colombia 2015

This is a repository for Jison workshop, it's intended to be blank/a guide and used as getting started base. Don't expect this generate a languaje itself.

## What you need

* Node.js `nodejs.org`
* NPM `npmjs.org`
* Gulp `npm install -g gulp`
* Jison `npm install -g jison`

## How to compile

First, to avoid problems, run clean command:

`gulp clean`

Then, install dependencies:

`npm install`

Finally compile everything with this command:

`gulp`

## How to test your progress

First run `npm install` to install all the required NPM dependencies. Then run:

`./bin/main.js examples/file_of_your_languaje`

Good luck!

## Publishing to NPM

First, create an account at `npmjs.org`, then in you project/work folder run this command:

`npm publish`

## How to use it after publish it

Install: `npm install you_languaje_name --global`

Run: `your_languaje_name {{file.your_languaje_name}}`

It will produce two files:

* Compiled javascript: `file.your_languaje_name.js`
* Source Map javascript: `file.your_languaje_name.js.map`

