# Stow Addresses

This NPM Package contains a list of all the Stow Smart Contracts addresses and their older versions.



## Install

### npm

This project is available through [npm](https://www.npmjs.com/). To install run

```
> npm install @stowprotocol/stow-addresses --save
```

### Use in Node.js

To create access the Stow Protocol contract addresses:

```
const stow_adresses = require('@stowprotocol/stow-addresses')

const stow_hub_address = stow_adresses.ropsten.StowSmartContracts.latest
const stow_hub_address1.6 = stow_adresses.ropsten.StowSmartContracts['v0.1.6']
const stow_hub_address_rinkeby = stow_adresses.rinkeby.StowSmartContracts.latest
const stow_token = stow_adresses.ropsten.StowToken.latest
```