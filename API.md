# API for EtherUi.net (v1)

The entry point https://etherui.net/api/v1/{methodName}

For understanding authorization mechanic, please learn https://github.com/kahmali/meteor-restivus#default-authentication

## Functions

<dl>
<dt><a href="#Get data from Smart contract">Get data from Smart contract(Network, Address, Func)</a></dt>
<dd><p>REST GET function without mandatory authentication</p>
</dd>
<dt><a href="#Create new UI for Smart contract">Create new UI for Smart contract(address, contract_name, abi, arguments)</a></dt>
<dd><p>REST POST function with mandatory authentication</p>
</dd>
<dt><a href="#Get balance for account">Get balance for account(Network, Address)</a></dt>
<dd><p>REST GET function api without mandatory authentication</p>
</dd>
</dl>

<a name="Get data from Smart contract"></a>

## Get data from Smart contract(Network, Address, Func)
REST GET function without mandatory authentication

**Kind**: global function  
**Summary**: Api for getting data from Smart contract  

| Param | Type | Description |
| --- | --- | --- |
| Network | <code>String</code> | The name of network |
| Address | <code>String</code> | The address of Smart contract |
| Func | <code>String</code> | The name of static function |

<a name="Create new UI for Smart contract"></a>

## Create new UI for Smart contract(address, contract_name, abi, arguments)
REST POST function with mandatory authentication

**Kind**: global function  
**Summary**: Api for a creating new smart contract UI - get all and save
You can send abi with an address to create new UI  

| Param | Type |
| --- | --- |
| address | <code>String</code> | 
| contract_name | <code>String</code> | 
| abi | <code>String</code> | 
| arguments | <code>String</code> | 

<a name="Get balance for account"></a>

## Get balance for account(Network, Address)
REST GET function api without mandatory authentication

**Kind**: global function  
**Summary**: Api for getting a balance by an address  

| Param | Type | Description |
| --- | --- | --- |
| Network | <code>String</code> | The name of network |
| Address | <code>String</code> | The address for getting a balance |


* * *

&copy; Viktorov Konstantin and contributors https://etherui.net
