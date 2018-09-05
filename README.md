# guld-random-cli

[![source](https://img.shields.io/badge/source-bitbucket-blue.svg)](https://bitbucket.org/guld/tech-js-node_modules-guld-random-cli) [![issues](https://img.shields.io/badge/issues-bitbucket-yellow.svg)](https://bitbucket.org/guld/tech-js-node_modules-guld-random-cli/issues) [![documentation](https://img.shields.io/badge/docs-guld.tech-green.svg)](https://guld.tech/cli/guld-random-cli.html)

[![node package manager](https://img.shields.io/npm/v/guld-random-cli.svg)](https://www.npmjs.com/package/guld-random-cli) [![travis-ci](https://travis-ci.org/guldcoin/tech-js-node_modules-guld-random-cli.svg)](https://travis-ci.org/guldcoin/tech-js-node_modules-guld-random-cli?branch=guld) [![lgtm](https://img.shields.io/lgtm/grade/javascript/b/guld/tech-js-node_modules-guld-random-cli.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/b/guld/tech-js-node_modules-guld-random-cli/context:javascript) [![david-dm](https://david-dm.org/guldcoin/tech-js-node_modules-guld-random-cli/status.svg)](https://david-dm.org/guldcoin/tech-js-node_modules-guld-random-cli) [![david-dm](https://david-dm.org/guldcoin/tech-js-node_modules-guld-random-cli/dev-status.svg)](https://david-dm.org/guldcoin/tech-js-node_modules-guld-random-cli?type=dev)

Cryptographically secure random number generator using `/dev/urandom` with fallback to node's `crypto` and finally to `window.crypto || window.mscrypto`.

### Install

##### Node

```sh
npm i -g guld-random-cli
```

### Usage

##### CLI

```sh
guld-random --help

  Usage: guld-random [options] [command]

  Cryptographically secure random number generator using `/dev/urandom` with fallback to node's `crypto` and finally to `window.crypto || window.mscrypto`.

  Options:

    -V, --version                  output the version number
    -h, --help                     output usage information

  Commands:

    string|str [length]            Generate a random string of the given length (default 256).
    number|num [max]               Generate a random integer between 0 and max. (default 255)
    run [options] <cmd> [args...]  Randomly choose whether to run command with args.

```

### License

MIT Copyright isysd
