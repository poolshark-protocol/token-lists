# Poolshark Token Lists

![Check](https://github.com/trustwallet/assets/workflows/Check/badge.svg)

## Overview

The repository contains token metadata from numerous blockchains and is able to pull tokens from Coingecko and other sources.

It is also sorted by total market capitalization, meaning the most liquid tokens across the entire market will appear first.

Such a large collection can be maintained only through a community effort, so _feel free to open a PR and add your token_.

**Adding an ERC20 token checklist**:

- [ ] Make sure your smartcontract has more than 100 address holders, otherwise you will be rejected
- [ ] Fork the Github repository
- [ ] Create folder with name of token smartcontact address in [_checksum format_](https://piyolab.github.io/sushiether/RunScrapboxCode/?web3=1.0.0-beta.33&code=https://scrapbox.io/api/code/sushiether/web3.js_-_Ethereum_のアドレスをチェックサム付きアドレスに変換する/demo.js) `blockchains/ethereum/assets/<token_smartcontract_address>/`.
- [ ] Tell your designer that token image must be in PNG format, preferably transparent background, recommended size 256x256px, with max file size of 100kB, for further details read [image rules](https://developer.trustwallet.com/assets/requirements).
- [ ] Upload your logo with file named `logo.png` to previously created folder with smartcontract address, and if you done all correctly your path should look like this. `blockchains/ethereum/assets/0x1234567461d3f8Db7496581774Bd869C83D51c93/logo.png`
- [ ] Create `info.json` file with info about the token/project
- [ ] Create a pull request to the main repo

## Disclaimer

The Poolshark team allows anyone to submit new assets to this repository. However, this does not mean that we are in direct partnership with any of the projects.