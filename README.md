# ts-clean-prime

[![npm](https://img.shields.io/npm/v/ts-clean-prime.svg)](https://www.npmjs.com/package/ts-clean-prime)
[![npm](https://img.shields.io/npm/l/ts-clean-prime.svg)](https://www.npmjs.com/package/ts-clean-prime)

## Overview

> A Tool For Cleaning Up JavaScript File Built By TypeScript. Forked from ts-clean, originally coded by koa-next: https://github.com/koa-next/ts-clean.

## Install

```sh
npm install ts-clean --save-dev
```

or

```sh
yarn add ts-clean --dev
```

## Usage

> package.json

```json
{
  ...
  "script": {
    ...
    "clean": "ts-clean"
  }
  ...
}
```

## Options

| Option  | Description                                                 | default                   |
| ------- | ----------------------------------------------------------- | ------------------------- |
| d       | the dir path you need to clean                              | pwd                       |
| e       | the file extension you need to clean                        | .js,.js.map,.jsx,.jsx.map |

## Example

- clean all .js, .js.map files built by TypeScript in the current directory

```sh
ts-clean
```

- clean all js files built by TypeScript in the app1 and app2 directory

```sh
ts-clean -d app1, app2
```

- clean all js files built by TypeScript in the app directory

```sh
ts-clean -d app -e .js
```

## Help

If you installed ts-clean in the global installation environment, you can use `ts-clean --help` for help.

## LICENSE

MIT
