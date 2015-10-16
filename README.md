# unit-synonyms-electric-current

[![Build Status](https://travis-ci.org/javiercejudo/unit-synonyms-electric-current.svg)](https://travis-ci.org/javiercejudo/unit-synonyms-electric-current)
[![Coverage Status](https://coveralls.io/repos/javiercejudo/unit-synonyms-electric-current/badge.svg?branch=master)](https://coveralls.io/r/javiercejudo/unit-synonyms-electric-current?branch=master)
[![Code Climate](https://codeclimate.com/github/javiercejudo/unit-synonyms-electric-current/badges/gpa.svg)](https://codeclimate.com/github/javiercejudo/unit-synonyms-electric-current)

Electric current units synonyms

## Install

    npm i unit-synonyms-electric-current

## Units

- [Ampere](https://en.wikipedia.org/wiki/Ampere)
- [Abampere](https://en.wikipedia.org/wiki/Abampere)

## Usage

```js
var synonyms = require('unit-synonyms-electric-current').synonyms;

synonyms['amp']; // => ampere
synonyms['biots']; // => abampere
```

## Related projects

- [linear-presets](https://github.com/javiercejudo/linear-presets): linear presets for common units.
- [linear-converter](https://github.com/javiercejudo/linear-converter): flexible linear converter.
