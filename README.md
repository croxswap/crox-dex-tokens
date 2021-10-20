# CroxSwap Token List Info
## Overview
The CroxSwap Token List is a list of tokens with accurate and up-to-date information, powering additional information on the BSC.

[CroxSwap DEX](https://exchange.croxswap.com) uses token logos from this source, alongside a number of other projects.

There are also third party projects which use this source for more up-to-the minute data.

The repository contains token info from the Binance smart Chain.

## How to add token

Please note that brand new tokens are not accepted,
the projects have to be sound, with information available, and non-minimal circulation

### Requirements
Requirements: 300 holders and 1000 transactions. 

There is no processing fee for partnered tokens to get listed but we would encourage you to provide a buy link to our DEX on your website . **FREE!**




### Quick starter

**Adding an BEP20 token checklist**:
- [ ] Make sure your smartcontract has more than 300 address holders & 1000 transactions, otherwise you will be rejected. Dust attacks do not qualify.
- [ ] Fork the Github repository
- [ ] Create folder with name of token smartcontact address in [_checksum format_](https://developer.trustwallet.com/add_new_asset#checksum_format) `bsc/assets/<token_smartcontract_address>/`.
- [ ] *** MAKE SURE THE FOLDER NAME IS IN CHECKSUM FORMAT *** https://ethsum.netlify.app/
- [ ] Tell your designer that token image must be in PNG format, avoid transparent background, recommended size 256x256px, max. 512x512px, with max file size of 100kB. We use trust wallet's [image rules](https://developer.trustwallet.com/add_new_asset#image-requirements).
- [ ] Upload your logo with file named `logo.png` to previously created folder with smartcontract address, and if you done all correctly your path should look like this. `bsc/assets/0x1234567461d3f8Db7496581774Bd869C83D51c93/logo.png`
- [ ] Create `info.json` file with info about the token/project (we expand on Trustwallet's info.json, see below)
- [ ] Create a pull request to the main repo


Please do take a moment to look at an existing project to view how best to integrate into our list.

#### Format
info.json
```
{
    "name": "CroxSwap",
    "website": "https://croxswap.com/",
    "telegram": "https://t.me/croxswap",
    "discord": "https://discord.gg/croxswap",
    "twitter": "https://twitter.com/croxswap",
    "description": "CroxSwap is a fully decentralized next generation yield farming and staking protocol with a cross-chain DEX to transfer your assets across networks.",
    "explorer": "https://bscscan.com/token/0x2c094f5a7d1146bb93850f629501eb749f6ed491",
    "type": "BEP20",
    "symbol": "CROX",
    "decimals": 18,
    "slippage": 0.5,
    "status": "active",
    "id": "0x2c094F5A7D1146BB93850f629501eB749f6Ed491",
   }
```




logo.png 
```recommended size 256x256px, max. 512x512px, with max file size of 100kB.```

in a Folder named after your Smart Contract Address in Checksum format.

## What's next?
* [Open a farm on CroxSwap](https://zetj2nazjv0.typeform.com/to/xtXrqGvo)
* [Check out Crox Dual farms](https://app.croxswap.com/dualfarms)


## Disclaimer
CroxSwap allows anyone to submit new assets to this repository. However, this does not mean that we are in partnership with the projects.
CroxSawap will reject projects that are deemed as scam or fraudulent after careful review.
CroxSwap reserves the right to reject any project for any reason from listing on this platform.

## Rules
Alerts in JSON are not accepted. Only CroxSwap is permitted to add alerts to tokens.

## License
Please read License.md for details.
