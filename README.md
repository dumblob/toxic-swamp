# Toxic Swamp

> CryptoNote/Aeon Web Miner add-on module for After Dark.

[![Latest NPM version](https://img.shields.io/npm/v/toxic-swamp.svg?style=flat-square)](https://www.npmjs.com/package/toxic-swamp)
[![NPM downloads per month](https://img.shields.io/npm/dm/toxic-swamp.svg?style=flat-square)](https://www.npmjs.com/package/toxic-swamp)
[![Minimum After Dark version](https://img.shields.io/badge/after%20dark->%3D%206.13.0-000000.svg?style=flat-square)](https://git.habd.as/comfusion/after-dark/)

## Screenshot

[![Screenshot of Toxic Swamp](https://jhabdas.keybase.pub/after-dark-v6.15.0-homepage-fs8.png "Toxic Swamp running on the After Dark v6.15.0 homepage")](https://after-dark.habd.as)

## Demo

A [live demo](https://after-dark.habd.as) is available on the After Dark website.

An earlier pre-recorded demo [is available](https://after-dark.habd.as/module/toxic-swamp/#demo) on the After Dark website.

## Setup

For Toxic Swamp to operate during the beta period you'll need to [create your own proxy](https://after-dark.habd.as/module/toxic-swamp/#create-your-own-proxy). Once the beta period has ended you may use [The Fire Swamp](https://after-dark.habd.as/module/toxic-swamp/#the-fire-swamp) unless you wish to maintain your own proxy server.

## Installation

1. Choose a module download source:
    - https://www.npmjs.com/package/toxic-swamp
    - https://www.jsdelivr.com/package/npm/toxic-swamp
    - https://git.habd.as/comfusion/toxic-swamp

2. Extract module contents into site `themes` directory:

    ```sh
    ├── static
    └── themes
        ├── after-dark
        └── toxic-swamp
    ```

3. Specify module in site config:

    ```toml
    theme = [
      "toxic-swamp", # sequence before "after-dark"
      "after-dark"
    ]
    ```

4. Miner now functional. Rebuild and serve your site to view the changes.

For release verification and additional information please see the [Toxic Swamp help docs](https://after-dark.habd.as/module/toxic-swamp/).

## License

Module code including anything under `data`, `layouts` and `static` licensed under the WTFPL. Please see source files in other directories for file-specific licensing considerations.
