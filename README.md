# stylelint-config-crishpeen

[![NPM version](http://img.shields.io/npm/v/@crishpeen/stylelint-config-crishpeen.svg)](https://www.npmjs.org/package/@crishpeen/stylelint-config-crishpeen)
[![Build Status](https://travis-ci.org/crishpeen/stylelint-config-crishpeen.svg?branch=master)](https://travis-ci.org/crishpeen/stylelint-config-crishpeen)
[![dependency Status](https://david-dm.org/crishpeen/stylelint-config-crishpeen/status.svg)](https://david-dm.org/crishpeen/stylelint-config-crishpeen)
[![peerDependency Status](https://david-dm.org/crishpeen/stylelint-config-crishpeen/peer-status.svg)](https://david-dm.org/crishpeen/stylelint-config-crishpeen?type=peer)
[![devDependency Status](https://david-dm.org/crishpeen/stylelint-config-crishpeen/dev-status.svg)](https://david-dm.org/crishpeen/stylelint-config-crishpeen?type=dev)
[![Downloads per month](https://img.shields.io/npm/dm/@crishpeen/stylelint-config-crishpeen.svg?style=flat)](https://npmcharts.com/compare/@crishpeen/stylelint-config-crishpeen)

> Crishpeen' shareable config for [Stylelint](https://github.com/stylelint/stylelint).

Extends [stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard) with
more strict rules and giving preference to indentation with 4 spaces.

To see the rules that this config uses, please read the [config itself](./index.js).

## Installation

Install [Stylelint](https://github.com/stylelint/stylelint) and this config:

```bash
$ npm install --save-dev stylelint @crishpeen/stylelint-config-crishpeen
```

## Usage

Apply the config in your `.stylelintrc` file:

```json
{
  "extends": "@crishpeen/stylelint-config-crishpeen"
}
```

### Suggested Extension

To further extend control over coding style of your stylesheets, you can also check for rules order
using [stylelint-order](https://github.com/hudochenkov/stylelint-order) plugin along with our config
[@crishpeen/stylelint-config-crishpeen-order](https://github.com/crishpeen/stylelint-config-crishpeen-order).
