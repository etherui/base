# API for EtherUi.net (v1)

The entry point https://etherui.net/api/v1/{methodName}

For understanding authorization mechanic, please learn https://github.com/kahmali/meteor-restivus#default-authentication

## Functions

<dl>
<dt><a href="#smartcontract/_network/_address/_func">smartcontract/:network/:address/:func()</a></dt>
<dd><p>Api for getting data from Smart contract</p>
</dd>
<dt><a href="#smartcontractnewui">smartcontractnewui(address, contract_name, abi, arguments)</a></dt>
<dd><p>Api for a creating new smart contract UI</p>
</dd>
<dt><a href="#balance/_network/_address">balance/:network/:address()</a></dt>
<dd><p>Api for getting a balance by an address</p>
</dd>
</dl>

<a name="smartcontract/_network/_address/_func"></a>

## smartcontract/:network/:address/:func()
Api for getting data from Smart contract

**Kind**: global function  
**Summary**: <br/>
Api for getting data from Smart contract  
**Authrequired**: no  
**Urlparam**: <code>String</code> :network - Ethereum network name, for example "mainnet"  
**Urlparam**: <code>String</code> :address - Smart contract address  
**Urlparam**: <code>String</code> :address - Static function name  
**Example**  
```js
GET
curl https://etherui.net/api/v1/smartcontract/mainnet/0x27bf1f282ee96cdb4bb921c961fe081f397e03e4/name -X GET
```
<a name="smartcontractnewui"></a>

## smartcontractnewui(address, contract_name, abi, arguments)
Api for a creating new smart contract UI

**Kind**: global function  
**Summary**: <br/>
Api for a creating new smart contract UI <br/>
You can send abi with an address to create new UI  
**Authrequired**: yes  

| Param | Type | Description |
| --- | --- | --- |
| address | <code>String</code> | Smart contract address |
| contract_name | <code>String</code> | Smart contract name |
| abi | <code>String</code> | Smart contract abi |
| arguments | <code>String</code> | Smart contract arguments in JSON format |

**Example**  
```js
POST
curl https://etherui.net/api/v1/smartcontractnewui -X POST -H "X-Auth-Token: f2KpRW7KeN9aPmjSZ" -H "X-User-Id: fbdpsNf4oHiX79vMJ" -d "address=0x27bf1f282ee96cdb4bb921c961fe081f397e03e4&contract_name=ESCBToken&abi={}&arguments=[123,\"My String\",[\"0x0\",\"0x1\",\"0x2\"]]"
```
<a name="balance/_network/_address"></a>

## balance/:network/:address()
Api for getting a balance by an address

**Kind**: global function  
**Summary**: <br/>
Api for getting a balance by an address  
**Authrequired**: no  
**Paramurl**: <code>String</code> :network - Ethereum network name, for example "mainnet"  
**Paramurl**: <code>String</code> :address - Smart contract address  
**Example**  
```js
GET
curl https://etherui.net/api/v1/balance/mainnet/0x93f36930f94fbb5afc5fb506d3f7abb9179a4e4e -X GET
```

* * *

&copy; Viktorov Konstantin and contributors https://etherui.net
