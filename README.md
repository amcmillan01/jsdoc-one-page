# jsdoc-one-page

[![npm version](https://badge.fury.io/js/jsdoc-one-page.svg)](https://badge.fury.io/js/jsdoc-one-page)
[![Build Status](https://travis-ci.org/amcmillan01/jsdoc-one-page.svg?branch=master)](https://travis-ci.org/amcmillan01/jsdoc-one-page)

A one page jsdoc template based on the default jsdoc template.

## Getting Started

- npm install jsdoc-one-page
- jsdoc1p -t ./node_modules/jsdoc-one-page -r JS_SOURCE_DIR_OR_FILE -d OUTPUT_DIR
    - `JS_SOURCE_DIR_OR_FILE` = the name of the directory or file the process
    - `OUTPUT_DIR` = the directory where the generated docs will be saved

## Reference

- http://usejsdoc.org/

## Deploy Process

- npm version patch 
- git fetch
- git rebase
- git push
- git push origin --tags
- check the [travis build](https://travis-ci.org/amcmillan01/jsdoc-one-page)

## License

Licensed under The MIT License (MIT)

For the full copyright and license information, please view the LICENSE.txt file.