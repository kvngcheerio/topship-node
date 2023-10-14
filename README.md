# Topship

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]

A NodeJS Wrapper for [Topship](https://www.topship.africa)

## Overview
This project provides an easy-to-use object-oriented API to access endpoints delineated at https://api-topship.com/shipping/docs#/

## Getting Started

>Install from the NPM Registry

```bash

    $ npm i --save topship-node

```

# Usage

```js

let Topship = require('topship-node')

let APIKEY = '2hWyQ6HW73jS8p1IkXmSWOlE4y9Inhgyd6g5f2R7'
const environment = process.env.NODE_ENV

const topship = new Topship(APIKEY, environment)

```


## API Resources

>Each method expects an object literal with both **route parameters** and **request parameters (query / body)**. Please, go through the _src/endpoints_ folder to see the specific items that should make up the object literal for each method


# License

MIT

# Credits

- [Omozue Gregory](https://twitter.com/kvngcheerio)

# Contributing

See the [CONTRIBUTING.md](https://github.com/kvngcheerio/topship-node/blob/master/CONTRIBUTING.md) file for info


## Support 

**Coolcodes** is a non-profit software foundation (collective) created by **Oparand** - parent company of StitchNG, Synergixe based in Abuja, Nigeria. You'll find an overview of all our work and supported open source projects on our [Facebook Page](https://www.facebook.com/coolcodes/).

>Follow us on facebook if you can to get the latest open source software/freeware news and infomation.

Does your business depend on our open projects? Reach out and support us on [Patreon](https://www.patreon.com/coolcodes/). All pledges will be dedicated to allocating workforce on maintenance and new awesome stuff.