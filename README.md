![logo-stash-it-color-dark 2x](https://user-images.githubusercontent.com/1819138/30385483-99fd209c-98a7-11e7-85e2-595791d8d894.png)

# stash-it-adapter-mongo

[![build status](https://img.shields.io/travis/smolak/stash-it-adapter-mongo/master.svg?style=flat-square)](https://travis-ci.org/smolak/stash-it-adapter-mongo)
[![Coverage Status](https://coveralls.io/repos/github/smolak/stash-it-adapter-mongo/badge.svg?branch=master)](https://coveralls.io/github/smolak/stash-it-adapter-mongo)

MongoDB adapter for [stash-it](https://www.npmjs.com/package/stash-it).

It's build in **ES6** so if you need to run it in an older environment,
you will need to transpile it.

## Installation

```sh
npm i stash-it-adapter-mongo --save
```

## Usage

```javascript
import { createCache } from 'stash-it';
import createMongoAdapter from 'stash-it-adapter-mongo';

const adapter = createMongoAdapter();
const cache = createCache(adapter);
```

And that's it. You are ready to go.

For available methods, check [adapters API section](https://stash-it.gitbook.io/stash-it/api/adapter) (all adapters have the same API).
