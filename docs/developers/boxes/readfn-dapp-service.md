
readfn-dapp-service
====================






## Service Documentation
[LiquidLens](../../services/readfn-service.md)
## Dependencies
### Boxes
* [`dapp-services`](dapp-services.md)
* [`seed-utils`](seed-utils.md)
* [`mocha`](mocha.md)
* [`hooks-cpp-contracts`](hooks-cpp-contracts.md)



## Contracts
* [`readfnservice`](https://github.com/liquidapps-io/zeus-sdk/tree/master/boxes/groups/services/readfn-dapp-service/contracts/eos/dappservices/_readfn_impl.hpp)

## Install
```bash
zeus unbox readfn-dapp-service
```



## Zeus Command Extensions
* ```zeus readfn  --help```





### Model Instances
#### [services/readfn.json](https://github.com/liquidapps-io/zeus-sdk/tree/master/boxes/groups/services/readfn-dapp-service/models/dapp-services/readfn.json)
```json
{
  "name": "readfn",
  "port": 13141,
  "contract": "readfndspsvc",
  "prettyName": "LiquidLens",
  "stage": "Alpha",
  "version": "0.9",
  "description": "Read Functions Service",
  "commands": {
    "rfnuse": {
      "blocking": false,
      "request": {},
      "callback": {
        "size": "uint64_t"
      },
      "signal": {
        "size": "uint64_t"
      }
    }
  }
}
```
## Tests 
* [readfnconsumer.spec.js](https://github.com/liquidapps-io/zeus-sdk/tree/master/boxes/groups/services/readfn-dapp-service/test/readfnconsumer.spec.js)
## [Source](https://github.com/liquidapps-io/zeus-sdk/tree/master/boxes/groups/services/readfn-dapp-service)