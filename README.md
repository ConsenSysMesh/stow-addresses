# Linnia Addresses

This NPM Package contains a list of all the Linnia Smart Contracts addresses and their older versions.



## Install

### npm

This project is available through [npm](https://www.npmjs.com/). To install run

```
> npm install @linniaprotocol/linnia-addresses --save
```

### Use in Node.js

To create access the Linnia Protocol contract addresses:

```
const linnia_adresses = require('@linniaprotocol/linnia-addresses')

const linnia_hub_address = linnia_adresses.LinniaSmartContracts.ropsten.latest
const linnia_hub_address1.6 = linnia_adresses.LinniaSmartContracts.ropsten['v0.1.6']
const linnia_hub_address_rinkeby = linnia_adresses.LinniaSmartContracts.rinkeby.latest
const linnia_token = linnia_adresses.LinniaToken.ropsten.latest
```