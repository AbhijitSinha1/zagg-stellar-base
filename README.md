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

# build the code
gulp build

#Install all dependencies
bundle install

#Generate js from xdr
yarn xdr
```

## Publishing on npm

- Make changes in code
- Update the version in package.json.
```
npm login
npm version minor --force
npm publish
```

