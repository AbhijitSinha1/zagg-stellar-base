## Overview

This is the core library to interact with ZaggProtocolCore. `zagg-stellar-sdk` uses this library internally.

## Installation

```
npm i zagg-stellar-base
```

## Bundling and Generating stellar-xdr_generated.js from XDRs

```
# install 
yarn install

#
gulp build

#Install all dependencies
bundle install

#Generate js from xdr
yarn xdr
```

## Publishing on npm

- Make changes in code
- Update the version in package.json.
- `npm login`
- `npm version major` or `npm version minor` or `npm version patch` depending upon types of changes.
- `npm publish`

