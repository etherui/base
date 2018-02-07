# About
Base repository for description, roadmap, issues for [Etherui.net](https://etherui.net)

# Features
- The dynamic creating of user interface based on ABI as for static functions, so and as for executable functions. Just paste ABI with a contract address and you will get high quality UI for an interaction and exploring any smart contract.
- The wallet creating  with new address or unlocking the wallet based on JSON/UTC3 file format.
- The interaction with blockchain via unlocked/created wallet for test/main/local networks.
- The sending of ETH amount on a smart contract, which provides payable interface.
- The search by address, transaction hash, block number.
- The dynamic definition a metamask extension.
- The deploying smart contract based on Truffle JSON file with custom constructor arguments.
- API for an external getting of data from static functions and a balance of address (https://github.com/etherui/base/blob/master/API.md).
- The events/transactions inspecation for a smart contract with UI.
- The integration with Shapeshift for a quckly exchange any available crypto currency on ETH.
- The tool for creating UI from truffle cli (https://www.npmjs.com/package/etherui-deploy).

# Roadmap
- [x] create API for a receiving results for static functions
- [x] mark an execution method if it is payable
- [ ] add a saving of personal bookmarks and quick access to personal contacts for logged in users
- [ ] if in a contract a field type is address, then need to add a possibility to paste from personal contact list
- [x] if in a contract a field type is BigNumber, then need possibility convert from/to ETH/WEI
- [ ] show a calculation average block time + add block for fast convert between some block/time
- [ ] add a validation code via uploading a zip file with contract files, contained "import" feature
- [ ] generate android + ios versions
- [ ] create browser extension to checking balance for contract and addresses, show a link for interaction
- [ ] offline transaction for sending a transaction after some block (autosending)
- [ ] create a tool for convert between units, sha3, etc.
- [ ] add an integration with hardware wallet https://digitalbitbox.com/api
- [ ] add an integration with hardware wallet https://github.com/LedgerHQ/ledger-wallet-api
- [ ] add an integration with hardware wallet http://doc.satoshilabs.com/trezor-tech/index.html
- [ ] add a subscription for notifications about contract events
- [ ] creating custom filters for notifications on events
- [ ] add a historical data in DB to create tree between all transaction in real time

# Author

[Viktorov Konstantin](https://facebook.com/kvictorov)

# Donation

[0x6CCF57D5aBaF7356dC1b6d583efDCdBE603535c8](https://etherui.net/address/0x6CCF57D5aBaF7356dC1b6d583efDCdBE603535c8)

# Submit an Issue

[New Issue](https://github.com/etherui/base/issues)
