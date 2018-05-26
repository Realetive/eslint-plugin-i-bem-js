ESLint environments for i-bem.js
================================

[![NPM Status][npm-img]][npm]
[![Travis Status][test-img]][travis]

[npm]:          https://www.npmjs.org/package/eslint-plugin-i-bem-js
[npm-img]:      https://img.shields.io/npm/v/eslint-plugin-i-bem-js.svg

[travis]:       https://travis-ci.org/realetive/eslint-plugin-i-bem-js
[test-img]:     https://img.shields.io/travis/realetive/eslint-plugin-i-bem-js.svg?label=tests

Install
-------

You'll first need to install `ESLint`:

```
$ npm install eslint --save-dev
```

**Note**: You may install ESLint globally using the `-g` flag.

Next, install `eslint-plugin-i-bem-js`:

```
$ npm install eslint-plugin-i-bem-js --save-dev
```

**Note**: If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-i-bem-js` globally.

A globally-installed instance of ESLint can only use globally-installed ESLint plugins. A locally-installed ESLint can make use of both locally- and globally- installed ESLint plugins.

Usage
-----

Add `i-bem-js` to the plugins section of your `.eslintrc` configuration file.

```json
{
    "plugins": [
        "i-bem-js"
    ]
}
```

**Note**: We omitted the `eslint-plugin-` prefix since it is automatically assumed by ESLint.

Add the `i-bem-js` environment to `.eslintrc`:

```json
{
    "env": {
        "i-bem-js": true
    }
}
```

License
-------

MIT © [Roman Ganin](https://github.com/Realetive)
